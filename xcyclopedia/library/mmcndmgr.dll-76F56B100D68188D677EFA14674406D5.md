---
title: mmcndmgr.dll | MMC Node Manager DLL
excerpt: What is mmcndmgr.dll?
---

# mmcndmgr.dll 

* File Path: `C:\Windows\SysWOW64\mmcndmgr.dll`
* Description: MMC Node Manager DLL

## Hashes

Type | Hash
-- | --
MD5 | `76F56B100D68188D677EFA14674406D5`
SHA1 | `5FF4B4032DB52CAF82F7F02EADF46A051A6BB72C`
SHA256 | `AE2A0B2A31305674A22369AFB30C1CC645E52B0C87D7A90ACF4F4B924444FDAC`
SHA384 | `35673E2E14A643D829F565C5C3D526109E2459CFC5B5D108AA060DED3360468359ABAE6880C19C00D9C3FD62A6D0DBBC`
SHA512 | `2FDDFC6DD746084BD84FCE09C118AAFE20EBFA9C9CA15D53A8FCEF37C903E627F0FD73CF048F46907EE7BC4D323A62F2B30581FD785D3223F7E143AB9AA7F7B6`
SSDEEP | `49152:3yuTQPv5vI4g7kCeSy4Nv/1qQsCjukf4Kq5DX142uTDrBe5xC1T:rIhIC34Nv/1qQsCjukwKq5DXSH8`
IMP | `1828CC50B913B9C91CC056D4ECB9FE8A`
PESHA1 | `FD0398EA70E72E52091BC79BAA433B40A328A856`
PE256 | `45C93C005D4C7952A51E33AEE1ABFA85846A4A1BDF130286085260B09032C9C4`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 4 | Exported Function
`DllUnregisterServer` | 5 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`CreateExecutivePlatform` | 1 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mmcndmgr.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/ae2a0b2a31305674a22369afb30c1cc645e52b0c87d7a90acf4f4b924444fdac/detection/


## Possible Misuse

*The following table contains possible examples of `mmcndmgr.dll` being misused. While `mmcndmgr.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_win_privesc.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_win_privesc.yar) | $s2 = "(([System.IconExtractor]::Extract(\"mmcndmgr.dll\", 126, $true)).ToBitMap()).Save($env:temp + \"\\Other.png\")    " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


