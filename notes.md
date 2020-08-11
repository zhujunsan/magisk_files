## Magisk (6c8fe465) (20420)
- Support NAND based Android installation on Nintendo Switch
- Support Android 11 AVD (`emulator.sh`, development only)
- Keep module disabled when a module is upgraded
- Inherit app namespace before isolating namespace (if supported)

## Magisk Manager (6c8fe465) (292)
- Workaround crashes on older Android devices (AOSP documentation error)
- Fix crashes when there is no internet connection
- Sign APKs with Signature Scheme v2 when repackaging (Android 11 requires v2)
- Many UI tweaks for better usability
