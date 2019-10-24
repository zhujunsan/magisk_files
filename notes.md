## Magisk (5c7b5952) (20003)
- Fix incorrect boot headers causing Samsung vbmeta errors
- Introduce component agnostic communication (to support stubs)
- Add support for SPRD DTBs

## Magisk Manager (7fc7809c) (249)
- **If you were using stubs, you have to restore Magisk Manager and then re-hide the app in order to update due to a bug in the previous version!!**
- Fix upgrading main app in stub
- Add support to upgrade stub app if available
- Fix stub APKs unable to receive root requests
