## Magisk (9b297b75) (20104)
- Properly solve the connection problem: first use ContentProvider method, then fallback to Activity mode if failure
- Support managing apps not installed in owner profile in multiuser owner managed mode

## Magisk Manager (9b297b75) (256)
- Fix `BootSigner` unable to run on pre Android 9.0 devices
- Rewritten parts of code for handling su requests and magisk database
