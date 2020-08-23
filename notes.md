## Magisk (6c8fe465) (20420)
- Support NAND based Android installation on Nintendo Switch
- Support Android 11 AVD (`emulator.sh`, development only)
- Keep module disabled when a module is upgraded
- Inherit app namespace before isolating namespace (if supported)

## Magisk Manager (65f88e4a) (294)
- Fix Play Protect blocking hidden manager installation
- Fix occasional broken animations
- Fix download notification dismissal delays on latest few Android versions
- Exclude toolbar from animations to prevent UI breakage
- Update stub APK implementation
- New feature: add pretty shortcuts to home screen after hiding the app with stub.
Since the hidden app could have cryptic name and no icon, this would be handy
- Use MediaStore API to access external storage on Android 10+.
This allow us to no longer require WRITE_EXTERNAL_STORAGE on Android 10+, and future proof
in case Scoped Storage is enforced on future Android versions.
