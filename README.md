# OpenCore configuration
## Last update: August 2022  
Current OS: macOS Big Sur  
Motherboard: Asus H61M-K.  
CPU: Intel Xeon E3-1220v2 (4c/4t).
GPU: AMD Radeon HD 6570 2GB with patched VBIOS for support GOP.
GPU: NVIDIA Quadro P400 2GB. 

Replace unfilled fields with valid data for your config.   
AppleSecureBoot disabled in config, because OpenCore cant boot macOS after installation.   
My PS/2 keyboard not working with VoodooPS2Controller.kext. Sad but true. 

## Used patches:
-- [OpenCore Legacy Patcher](https://dortania.github.io/OpenCore-Legacy-Patcher/): Patched Root Volume to use my gpus in modern macos (official gpu support ended on High Sierra)

