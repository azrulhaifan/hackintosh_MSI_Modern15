# Hackintosh MSI Modern 15 with Opencore
Star this repo if this help you. this repo is still w.i.p, do with your own risk

# Specifications :
- Model : A10RBS
- Bios version : E1551IMS.10E
- Processor : Intel Core i5 10210U
- IGPU : Intel UHD Graphics 10Th Gen
- eGPU : Nvidia MX350
- RAM : 8GB DDR4 PC21300 (2667Mhz) x 2
- Storage : 1x NVME Micron 2210 512GB and 1x NVME Adata SX8200Pro 512GB
- Wifi : Intel AC 9560 and Bluetooth
- Audio : Realtek ALC235
- Ethernet : None
- Keyboard Backlight : Yes
- Boot Mode : UEFI GPT
- Screen Size : 15.6"
- Display Resolution : 1920 x 1080
- Bootloader : OpenCore r0.6.9
- OS : macOS Big Sur 11.4 Build 20F71

# Work??
- QE/CI of Intel UHD Graphics 10Th Gen
- Internal Speaker, Headphone and Internal Microphone (internal speaker no sound after reboot from windows)
- Touchpad
- Brightness
- Battery Indicator
- FN + Brightness Button Up / Down
- Keyboard Backlight
- All USB Port
- HDMI Out (need to re-plug cable after sleep / from booting)
- HDMI Audio
- Wifi
- Bluetooth (disable for now as it can causing slow boot due to firmware loading)
- Restart, Sleep and Shutdown 
- Built-in Camera
- Etc

# Not Work??
- Nvidia MX350 (Nvidia Optimus is not Supported by Hackintosh)
- Etc

# Not Tested
- Card Reader


# Tips

- Make sure you have disabled secure boot in bios.
- You had to disabled CFG Lock in bios.
- At startup press delete key to enter in bios.
- **Go to Advanced menu & press the magic combo keys**
- Press LEFT ALT + RIGHT CTRL + RIGHT SHIFT together then (still pressing 3 btn) press F2 for see hidden feature
- Note (press also fn keys depend on your fn lock or not)
- go to advanced->power & Performance ->CPU - Power Management Control ->CPU lock Configuration ->CFG lock

# Thanks

- **AndresGarciaSobrado91** https://github.com/AndresGarciaSobrado91 and **hla63** https://github.com/hla63 for efi core