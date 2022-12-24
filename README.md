# ASUS-Prime-B250M-A-OpenCore-EFI
Asus Prime B250M-A OpenCore EFI running on ver 0.8.7, i5-6500, HD 530, B250. turns out kaby lake chipsets dont mix well with skylake cpus so i had to use another platform-id as seen in the config.plist of the EFI.



Specs :
Motherboard : ASUS Prime B250M-A
CPU : i5-6500
iGPU : Intel HD Graphics 530
SMBIOS : MacMini8,1
RAM : 8GB SingleSlot
BIOS ver : 0809

iGPU setup :
AAPL,ig-platform-id : 05003B19
device-id : 3B190000
model : Intel HD Graphics 530
bootarg needed : igfxonln=1




SMBIOS used macmini8,1 due to artifacts with iMac17,1/18,1

Make sure to use GenSMBIOS to gen a new SMBIOS and serial and then do a clean snapshot with ProperTree

MacSerial has been blanked due to iCloud reasons.
