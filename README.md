# HUAWEI-KLVC-WFH9L

# HUAWEI-KLVC-WFH9L-i5-10210U-OC1.0.5

## The overall configuration list of my black Apple host is as follows:

| Part Type     | Part Model 
|---------------|----------------------------------------------|
| Opencore      |  1.0.5                                       |
| Version       |  macOS Sequoia15.5Beta4                      |
| Motherboard   |  HUAWEI-KLVC-WFH9L                           |
| Hard disk     |  Coiorful CN600 1T M2                        |
| Graphics      |  Intel UHD620                                |
| CPU           |  Intel Core i5 10210U                        |
| Memory        |  ADATA 2133 16G*1 LPDDR3                     |
| Wireless      |  network card: ntel AX210                    |
| Sound card    |  ALC256                                      |
| SMBIOS        |  MacBookPro 16.3                             |
| Touchpad      |  SYNA7813                                    |


#HUAWEI-KLVC-WFH9L Series Motherboards MacOS 15.5. Completeness:

The graphics card supports HDMI/DP display output

Sleep wake-up is normal

Intel UHD 620 is normal

Brightness Control is normal

Backlight shortcuts is normal

USB is normal

Internal speaker is normal

Headphone output is normal

Internal Mic is normal

Touchpad is normal

Intel WIFI/Bluetooth

Solution 1: The onboard intel AX210 Bluetooth and WIFi can be driven, and the network speed is very good, but it does not support air-car. MacOS 15 requires the HELIPORT APP to use the WIFI function

Solution 2: The onboard intel AX210 Bluetooth and WIFi can be driven, and the network speed is very good, but it does not support air-carry; MacOS 15 requires OCLP patching here using option 2

I won't talk about them one by one

## What's not working

Nvidia MX250

### OpenCore Configuration

### ACPI

| ACPIs                                    |
|--------------------------|
|  SSDT-AWAC               |
|  SSDT-HPET               |
|  SSDT-PS2K               |
|  SSDT-RMNE               |
|  SSDT-XOSI               |
|  SSDT-PNLFCFL            |
|  SSDT-EC.aml             |
|  SSDT-UIAC.aml           |
|  SSDT-PLUG.aml           |
|  SSDT-SBUS.aml           |
|  SSDT-PTSWAKTTS.aml      |
|  SSDT-GPUPP.aml          |

### Drivers

| Driver Name     |
|-----------------|
| HfsPlus         |
| OpenCanopy      |
| OpenRuntime     |
| ResetNvramEntry |
| ToggleSipEntry  |

### Kexts


| Kext Name                        |
|----------------------------------|
| Lilu                             |
| VirtualSMC                       |
| WhateverGreen                    |
| AppleALC                         |
| SMCBatteryManager                |
| NVMeFix                          |
| NoTouchID                        |
| SMCLightSensor                   |
| VoodooPS2Controller              |
| SMCProcessor                     |
| SMCSuperIO                       |
| BrightnessKeys                   | 
| VerbStub                         | 
| HibernationFixup                 | 
| VoodooI2C                        | 
| VoodooI2CHID                     | 
| DebugEnhancer                    | 
| IO80211FamilyLegacy              | 
| IOSkywalkFamily                  |
| AirportItlwm-15.5Sequoia         | 
| IntelBTPatcher                   | 
| IntelBluetoothFirmware           |
| BlueToolFixup                    |
| AMFIPass                         |
| CPUFriend                        |
| CPUFriendDataProvider            |
| RestrictEvents                   |

bios 设置参考：

Internal graphics >enable

Security

Intel Platform Trust Technology: Unchecked

Intel Software Guard Extension (SGX): Disabled

Thunderbold Security Level: Legacy mode

Boot

Secure Boot: Disabled

Fast Boot: Unchecked

若有其他问题请加Q群： 738882434
