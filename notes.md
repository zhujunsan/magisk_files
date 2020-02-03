## Magisk (ed58cf95) (20304)
- Support device dtbs that require specific paddings to boot
- Fix mounting system in `magiskinit` on devices using Tegra partition naming
- Improve scripts for installation on Android 10 in custom recoveries
- Remove erroneously forced core-only mode pre KitKat (Jellybean support modules!)
- Fix `libsqlite.so` dynamic loading on some devices
- Support `genfscon` rules in `magiskpolicy`
- Fix Android version detection on some dumb ass devices (e.g. Realme)
- Workaround `readlinkat` returning bogus values on dumb ass x86 devices

## Magisk Manager (ed58cf95) (274)
- Fix uncentered dialogs
- Make su request match app theme
