---
title: wmiutils.dll | WMI
excerpt: What is wmiutils.dll?
---

# wmiutils.dll 

* File Path: `C:\Windows\SysWOW64\wbem\wmiutils.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `18A3E4EB5B29BE1A4F572B1F975DF7B3`
SHA1 | `25879493F01CC65DEAAB6A46DE1931036CB46DCE`
SHA256 | `500745D653DEF66D0E6718EAF75FE696898D8E4272EA028E38A6716E8BA51F6D`
SHA384 | `958964C03AF67D9D24D585DC17E5C4AAE3119D7F4D2E2E68EC42939FF4C936CE69FAEFF3DBD4D62CC44274299189B6D0`
SHA512 | `02CA9669A254399F0A80C91D9647C75D2318632CD038933B07AF3DCBD59229C392450D46A6EF03B8221399A424ED51BB66DA7F10FDC9A620F9652B8A5F10084F`
SSDEEP | `1536:bpVE5A8hhyW0SBi3DDB6Eyb0ONFC56ulBqeaAaXTE8/C7dkjPbTQdcT5fX:b6A8GW0TB6XtNePwH/mkjPbsdAV`
IMP | `632F29208C3D36C947E43B11650C8216`
PESHA1 | `8FC03B733BD9085C394D817E2B35ED40B97DD675`
PE256 | `FCE7B5FFE2B1CAD8301B6ADB5E673725C266C50F5DE425121059E4A310D4E386`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x1000a3a0 | 0x0000a3a0
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x100050d0 | 0x000050d0
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x10010490 | 0x00010490
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x100104f0 | 0x000104f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmiutils.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/500745d653def66d0e6718eaf75fe696898d8e4272ea028e38a6716e8ba51f6d/detection/


## Possible Misuse

*The following table contains possible examples of `wmiutils.dll` being misused. While `wmiutils.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wmiutils.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wmiutils.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


