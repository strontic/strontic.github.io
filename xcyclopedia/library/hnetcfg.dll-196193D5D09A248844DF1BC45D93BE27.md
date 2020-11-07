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

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 4 | Exported Function
`DllGetClassObject` | 5 | Exported Function
`DllRegisterServer` | 6 | Exported Function
`DllUnregisterServer` | 7 | Exported Function
`HNetDeleteRasConnection` | 1 | Exported Function
`HNetFreeSharingServicesPage` | 2 | Exported Function
`HNetGetFirewallSettingsPage` | 8 | Exported Function
`HNetGetSharingServicesPage` | 3 | Exported Function
`HNetSharedAccessSettingsDlg` | 9 | Exported Function
`HNetSharingAndFirewallSettingsDlg` | 10 | Exported Function
`RegisterClassObjects` | 11 | Exported Function
`ReleaseSingletons` | 12 | Exported Function
`RevokeClassObjects` | 13 | Exported Function
`WinBomConfigureWindowsFirewall` | 14 | Exported Function


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


