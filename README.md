# Big Sur on Gigabyte H170n with OpenCore (0.6.4)
Verified working macOS 11.0.1 Big Sur

<img src="https://github.com/ChrisMJSong/OpenCore_H170n/blob/master/Doc/systemImage_1.png?raw=true" width="586">

## System Enviroment
* OS: Big Sur (11.0.1)
* CPU: Intel i5-6600 (Skylake)
* Mainboard: GA-H170n-WiFi
  * WiFi Adapter: BCM94352Z
* GPU: Sapphire Radeon RX 590 Intro+
* RAM: SAMSUNG 8GB 2400 MHz DDR4 * 2 ea
* SSD: SAMSUNG SSD 860 EVO0

## Working
* USB
* dGPU
* Wi-Fi
* Airdrop
* Handoff
* Bluetooth
* Sleep / Wake
* Ethernet(LAN)

## Not Checked
* Speed step
* Dual Monitor

## Used Kext
* AirportBrcmFixup.kext
* AppleALC.kext
* BrcmBluetoothInjector.kext
* BrcmFirmwareData.kext
* BrcmPatchRAM3.kext
* IntelMausi.kext
* Lilu.kext
* SMCProcessor.kext
* SMCSuperIO.kext
* USBPorts.kext
* VirtualSMC.kext
* WhateverGreen.kext

## Have to update SMBIOS before use
PlatformInfo > Generic in Config.plist file
