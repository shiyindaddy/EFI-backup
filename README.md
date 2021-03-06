# EFI-backup
EFI backup for macOS Catalina 10.15.6 with OpenCore 0.5.9 - ASUS TUF B360M - i5 9600k - UHD 630

## Setup
- MB: ASUS TUF B360M-PLUS GAMING/BR
- CPU: Intel Core i5 9600K
- GPU: Integrated Intel UHD 630
- OS: macOS Catalina 10.15.6
- BOOT: OpenCore 0.5.9

## Instructions
- Copy files to EFI partition
- Run [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to create Serial Number
- Copy and paste serial numbers generated by SMBIOS in config.plist file (find by GenSMBIOS)

## Condition
- Dual Monitor (HDMI and DVI) working
- Audio working
- USB 3.0 working
- LAN working
- Accelerated graphics working (UHD 630 up to 1536MB shared memory)
- Not working:
  - I don't know! (At least everything is working like a charm)
  
