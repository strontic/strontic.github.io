---
title: xolehlp.dll | Microsoft Distributed Transaction Coordinator Helper APIs DLL
excerpt: What is xolehlp.dll?
---

# xolehlp.dll 

* File Path: `C:\Windows\SysWOW64\xolehlp.dll`
* Description: Microsoft Distributed Transaction Coordinator Helper APIs DLL

## Hashes

Type | Hash
-- | --
MD5 | `9C7B69FD706BA8736446E804740CA0C0`
SHA1 | `93560B04009CB26C9B189C89B205281B25161307`
SHA256 | `E47004D2C5218A1C81EF8B2906BB5F075BA70C37F805012B27DFB296845393AB`
SHA384 | `0E07CC4DC0B8D60A84F16CD22F2D44AE388E9049D28A0F5DBA359578B016CFD652E1F0B07F823ACEBA024B489F08B16C`
SHA512 | `7DFE1E81BE32644E128B0A7748A0A7C1A43D80A86AEF0D80802B997DBBC4793E0D6B46273DC238FBA0D55509B1BDC32AC749B970884876B6E9561F01473FBB85`
SSDEEP | `1536:F7fE/AhlPiE3AmGKZAOGdsUuas8T+0Qz1fPzF:pPniE3HZArdDT+VJXzF`
IMP | `9BF7827360F539A406D84FA6BEFEC954`
PESHA1 | `DD9A9FBBF641E4FED061EA0A80499AA4ADF39590`
PE256 | `37D805283F5ACF6C678EEB94B44401D3513390CE99020212DB1CEFAC83270A90`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DtcGetTransactionManager` | 5 | Exported Function
`DtcGetTransactionManagerC` | 7 | Exported Function
`DtcGetTransactionManagerEx` | 6 | Exported Function
`DtcGetTransactionManagerExA` | 10 | Exported Function
`DtcGetTransactionManagerExW` | 11 | Exported Function
`FreezeLocalTransactionManagers` | 8 | Exported Function
`GetDtcLocaleResourceHandle` | 4 | Exported Function
`ThawLocalTransactionManagers` | 9 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: XOLEHLP.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e47004d2c5218a1c81ef8b2906bb5f075ba70c37f805012b27dfb296845393ab/detection/


## Possible Misuse

*The following table contains possible examples of `xolehlp.dll` being misused. While `xolehlp.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s3 = "XOLEHLP.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


