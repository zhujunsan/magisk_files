## Magisk (0dc9f5c3) (20303)
- Full SELinux support added in Magisk's built-in BusyBox
- Fix full device meltdown when calling `magiskinit` in A-only 2SI devices (or A/B with recovery like OP7T)

## Magisk Manager (497efc9f) (273)
- Fix duplicating messages in modules section
- Fix APK built with release flag unable to hide manager (caused by compiler bug 😅)
- Add new theme (Fraxure), which matches the legacy design color scheme
- Make special characters in scrambled text (e.g. animation in flash screen) match character width
