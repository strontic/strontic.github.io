---
title: hnetcfg.dll | Home Networking Configuration Manager
excerpt: What is hnetcfg.dll?
---

# hnetcfg.dll 

* File Path: `C:\Windows\SysWOW64\hnetcfg.dll`
* Description: Home Networking Configuration Manager

## Hashes

Type | Hash
-- | --
MD5 | `7B92848F3BB6D42D0ABD14BC2C54710C`
SHA1 | `B2F1B0932B20DBD285256ABBA025B4354C269295`
SHA256 | `0E2E12543C8F4E64B3B6B5756BB00366C15C5A9079D69DA57FA554026AFCD9A4`
SHA384 | `093B460702379DB89E2D1B61589DF7B5B694931FE0C1D8460177A27786B5F71D0E94DD4511419A9F0165DAD3143D9656`
SHA512 | `EAFA36D2AE2F08D2B9D83CB0C01CCE913BDECA790F083D7375C58C1AEB42B792A49A352236D7386CE76432452836E8F52568F5615C71C1FD6AB7CDAF62EABF45`
SSDEEP | `6144:7EPdim985v0vf92YayCOZnJMPW4cYtxeLV6dAraz:7yJZ2+JMPWMEV6Ia`
IMP | `A0E8D03985545DC2282A5AB6B68535F1`
PESHA1 | `4A782DC5B4F11EE7E3B3CB3185FD0FF84391D397`
PE256 | `242B6C00B437390D4ACC53A15AFA1959838A308C4CF93FB135A43A0E84288EDE`

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

* Original Filename: HNETCFG.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/0e2e12543c8f4e64b3b6b5756bb00366c15c5a9079d69da57fa554026afcd9a4/detection/


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


