# HUAWEI-KLVC-WFH9L

# HUAWEI-KLVC-WFH9L-i5-10210U-OC1.0.5

## The overall configuration list of my black Apple host is as follows:

| Part Type     | Part Model 
|---------------|----------------------------------------------|
| Opencore      |  1.0.5                                       |
| Version       |  macOS Sequoia15.5                           |
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

## 关于打赏

如果您认可我的工作，请通过打赏支持我后续的更新(自觉打赏的人真少啊，免费的东西长久不了,现已改为需要密码解压，需微信或支付宝打赏入群。打赏记得留言备注你的qq号，然后申请入群时，填写你的留言为验证答案就是，我确认后会通过你的验证的。PS:之所以设置打赏，并不是为了赚大钱，当然大家打赏的多是有一些零花钱。主要是维护更新不易，每次系统一更新，有问题的话，就要工作时间之外花时间去调试，解决问题。普通群最多500人，无门槛的入群，不够用，有些机友对无门槛进入还不珍惜，进退群很随意，不看相关说明，上来就问问题的又多。不多说了，理解不理解的，就这样吧。

|  微信                                                                                 |
|---------------------------------------------------------------------------------------|
| ![1](https://github.com/user-attachments/assets/06d87fea-0d11-4bf4-b9ed-034dc7f53d06) |
|                                                                                       |

|  支付宝                                                                               |
|---------------------------------------------------------------------------------------|
| ![1](https://github.com/user-attachments/assets/b99e75b4-69d3-450a-aae4-1a610760372d) |                                              |                                                                                       |

若有其他问题请加Q群： 738882434
