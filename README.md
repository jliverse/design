# Tools & Resources for Designers
## Generate App Icons for iOS & watchOS
For app developers who create app icons for use in XCode asset catalogs, this Photoshop CC-compatible PSD provides a single embedded master image for generating a directory of derived image sizes.

[Download the 12.7MB PSD](generate-icons-ios7-watchos2.psd)

![Preview of PSD](generate-icons-ios7-watchos2-preview.png)

Use File ▶ Generate ▶ Image Assets to generate images in Adobe Photoshop CC 14+.

```
$ find generate-icons-ios7-watchos2-assets -name "*.png" -print0 -exec identify -ping -format ' (%[fx:w]x%[fx:h]px)\n' {} \;
generate-icons-ios7-watchos2-assets/ipad/Icon-76.png (76x76px)
generate-icons-ios7-watchos2-assets/ipad/Icon-76@2x.png (152x152px)
generate-icons-ios7-watchos2-assets/ipad/Icon-83.5@2x.png (167x167px)
generate-icons-ios7-watchos2-assets/ipad/Icon-Small-40.png (40x40px)
generate-icons-ios7-watchos2-assets/ipad/Icon-Small-40@2x.png (80x80px)
generate-icons-ios7-watchos2-assets/ipad/Icon-Small.png (29x29px)
generate-icons-ios7-watchos2-assets/ipad/Icon-Small@2x.png (58x58px)
generate-icons-ios7-watchos2-assets/iphone/Icon-60@2x.png (120x120px)
generate-icons-ios7-watchos2-assets/iphone/Icon-60@3x.png (180x180px)
generate-icons-ios7-watchos2-assets/iphone/Icon-Small-40@2x.png (80x80px)
generate-icons-ios7-watchos2-assets/iphone/Icon-Small-40@3x.png (120x120px)
generate-icons-ios7-watchos2-assets/iphone/Icon-Small@2x.png (58x58px)
generate-icons-ios7-watchos2-assets/iphone/Icon-Small@3x.png (87x87px)
generate-icons-ios7-watchos2-assets/iTunesArtwork.png (512x512px)
generate-icons-ios7-watchos2-assets/iTunesArtwork@2x.png (1024x1024px)
generate-icons-ios7-watchos2-assets/watch/Companion-29@2x.png (58x58px)
generate-icons-ios7-watchos2-assets/watch/Companion-29@3x.png (87x87px)
generate-icons-ios7-watchos2-assets/watch/Home-40@2x.png (80x80px)
generate-icons-ios7-watchos2-assets/watch/Notification-38mm-24@2x.png (48x48px)
generate-icons-ios7-watchos2-assets/watch/Notification-42mm-27.5@2x.png (55x55px)
generate-icons-ios7-watchos2-assets/watch/Short-Look-38mm-86@2x.png (172x172px)
generate-icons-ios7-watchos2-assets/watch/Short-Look-42mm-96@2x.png (196x196px)
```
