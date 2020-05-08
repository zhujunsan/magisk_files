## Magisk (a62bdc58) (20409)
- Fix overlay.d yet AGAIN
- Update `resetprop` internal implementation
- Support Safe Mode detection: all modules and magiskhide will be disabled when you boot into Safe Mode.
The disabling of modules and magiskhide will persist through the next normal boot, which is useful for
dealing with rogue modules causing bootloops.

## Magisk Manager (87de0e7a) (284)
- Update internal scripts
- Remove all code for dtb/dtbo/dtbs partition patching
