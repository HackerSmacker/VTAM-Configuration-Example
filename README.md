# ACF/VTAM Example Configuration Files!!!!

### These are mainly for ACF/VTAM 4.2 on VM/CMS, but work elsewhere and on newer versions.
OS/390 and VSE/ESA require a LOT more configuration, and files will be hopefully added in
later iterations of this repository.

Some things to note:
- VMVTAM GCS and PROFILE GCS are slightly modified from the P/390 ADCD default
- ASMUSS EXEC provides an easy way to reassemble your login screen assembler programs
- This is a simple network consisting of VM/ESA talking to OS/390 and VSE/ESA over CTCAs
- Windows NT and OS/2 are talked to with APPN over Ethernet links
- AGWPROF GCS is for AVSVM
