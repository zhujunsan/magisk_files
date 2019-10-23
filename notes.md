## Magisk (5c7b5952) (20003)
- Fix incorrect boot headers causing Samsung vbmeta errors
- Introduce component agnostic communication (to support stubs)
- Add support for SPRD DTBs

## Magisk Manager (5c7b5952) (248)
- Support using stub APKs to load full Magisk Manager.
Magisk Manager will use stub APKs to hide itself when it is feasible
- When hiding Magisk Manager, the new hidden app will be signed with
a randomly generated key to prevent detection
- Support customizing app name when hiding Magisk Manager
