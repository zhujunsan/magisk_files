## Magisk (99ef2062) (20412)
- Fix bug in collect module logic, should fix module unable to disable
- Move vendor prop hiding to boot completed to prevent bootlooping OnePlus devices
- Remove prop `ro.build.selinux` for hiding since it no longer exists in AOSP, and multiple dumb ass detections expect different values

## Magisk Manager (87de0e7a) (284)
- Update internal scripts
- Remove all code for dtb/dtbo/dtbs partition patching
