---
title: hnetcfg.dll | Home Networking Configuration Manager
excerpt: What is hnetcfg.dll?
---

# hnetcfg.dll 

* File Path: `C:\Windows\system32\hnetcfg.dll`
* Description: Home Networking Configuration Manager

## Hashes

Type | Hash
-- | --
MD5 | `196193D5D09A248844DF1BC45D93BE27`
SHA1 | `56A38E91446DD9B22A87E70C4F674BED2FB5F86E`
SHA256 | `566020B35F754B3F7FF5140A0CFFE003BAAB527DCD8552198686427B43D47922`
SHA384 | `8E20F06A3A763CAE715454FA294FC5848C8A3610505B819FC4607F4A07742AD43AEFEE3E5CD20A5AF28DC747B09ED8F1`
SHA512 | `0EE8A33551353158A9AAA209FE6789A17CD4A29F10131E4EBF002BE940B4D1548047E820C866C4E560D8A0BF04F9722FA9A9C3FF66F8A3BFADBB738EAFC933FF`
SSDEEP | `6144:T+d0M2iQwZ0vSWRzVchRWJAaTPXt+yx3LhXxmqjIeurEq:T+H2iIv1RzVc7i3lxZoEINj`
IMP | `C5AE27FE6894CC68A46B577997EB7590`
PESHA1 | `890273B338F9471355DB53A5A4553DE0FA45F094`
PE256 | `086D9AF6F3D160E30BD9A4D1A8F5C31F26D640331C2BCC4AADF414857D95E58C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 4 (0x4) | Exported Function | 0x000000018000b020 | 0x0000b020
`DllGetClassObject` | 5 (0x5) | Exported Function | 0x000000018000b060 | 0x0000b060
`DllRegisterServer` | 6 (0x6) | Exported Function | 0x00000001800013b0 | 0x000013b0
`DllUnregisterServer` | 7 (0x7) | Exported Function | 0x00000001800013b0 | 0x000013b0
`HNetDeleteRasConnection` | 1 (0x1) | Exported Function | 0x000000018000c410 | 0x0000c410
`HNetFreeSharingServicesPage` | 2 (0x2) | Exported Function | 0x0000000180027a30 | 0x00027a30
`HNetGetFirewallSettingsPage` | 8 (0x8) | Exported Function | 0x00000001800268b0 | 0x000268b0
`HNetGetSharingServicesPage` | 3 (0x3) | Exported Function | 0x0000000180027b70 | 0x00027b70
`HNetSharedAccessSettingsDlg` | 9 (0x9) | Exported Function | 0x000000018002bfd0 | 0x0002bfd0
`HNetSharingAndFirewallSettingsDlg` | 10 (0xa) | Exported Function | 0x000000018002c170 | 0x0002c170
`RegisterClassObjects` | 11 (0xb) | Exported Function | 0x00000001800200d0 | 0x000200d0
`ReleaseSingletons` | 12 (0xc) | Exported Function | 0x0000000180020240 | 0x00020240
`RevokeClassObjects` | 13 (0xd) | Exported Function | 0x0000000180020310 | 0x00020310
`WinBomConfigureWindowsFirewall` | 14 (0xe) | Exported Function | 0x000000018000c7a0 | 0x0000c7a0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HNETCFG.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/566020b35f754b3f7ff5140a0cffe003baab527dcd8552198686427b43d47922/detection/


## Possible Misuse

*The following table contains possible examples of `hnetcfg.dll` being misused. While `hnetcfg.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s0 = "%SystemRoot%\\system32\\hnetcfg.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s0 = "hnetcfg.HNetGetSharingServicesPage" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s1 = "hnetcfg.IcfGetOperationalMode" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s2 = "hnetcfg.IcfGetDynamicFwPorts" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s3 = "hnetcfg.HNetFreeFirewallLoggingSettings" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s4 = "hnetcfg.HNetGetShareAndBridgeSettings" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s5 = "hnetcfg.HNetGetFirewallSettingsPage" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


