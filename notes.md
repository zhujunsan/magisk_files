## Magisk (0850bca9) (20416)
- Update `magiskpolicy` to support adding new attributes
- Add support for lz4 compressed DTBs
- Redesign of MagiskSU's selinux model: 2 additional new selinux types are created to allow more fine grained control and better security
- Update uninstaller scripts for better error messages in LOS recovery and LRAP

## Magisk Manager (0850bca9) (285)
- Resolve `raw.githubusercontent.com` URLs with Cloudflare DNS-over-HTTPS service to workaround DNS pollution issue in China
- Fix direct install on devices using NAND
- Fix colors in su request dialog
- Support the redesigned MagiskSU selinux model
