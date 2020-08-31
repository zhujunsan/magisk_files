## Magisk (6c8fe465) (20420)
- Support NAND based Android installation on Nintendo Switch
- Support Android 11 AVD (`emulator.sh`, development only)
- Keep module disabled when a module is upgraded
- Inherit app namespace before isolating namespace (if supported)

## Magisk Manager (fbaf2bde) (297)
- Fix several bugs in manager upgrade logic.
It should now successfully upgrade under all circumstances after this build.
If you ran into "cannot parse package" error, clear the app cache and try again.
- Allow arbitrary package name and app label length for repackaging
