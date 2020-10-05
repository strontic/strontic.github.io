---
title: wab32.dll | Microsoft (R) Contacts DLL
excerpt: What is wab32.dll?
---

# wab32.dll 

* File Path: `C:\Program Files\Common Files\System\wab32.dll`
* Description: Microsoft (R) Contacts DLL

## Hashes

Type | Hash
-- | --
MD5 | `4CFD750BB8AEE13DD09C0B0143A076C9`
SHA1 | `8D9BB8E3384F1E9F920B704111B98205EDBFE651`
SHA256 | `C19070B2B39678D7ABAEA720B117FB6E255B240683798AF1331173A7834E131C`
SHA384 | `0654AEA583CAD5D49E0A1933CFAD19B47B20A70A275B56497C37B20149E46796D5C6094263C514F0899E643FC373DCAD`
SHA512 | `76AF1AFD62B68FA368CF37F28EEFA4928CA81D71F31E1640E85DA9B1E3A4198DB941D92265FB76C677447988801AF1495846A9CA3A97709C0B9E1AE21B7715CC`
SSDEEP | `12288:Oi8jY6MJt0m14TL47neVghh/yIKr4HSmnXodRKbBuaBoyiCLRN0bklkl/BMLhBb+:Omdhh/y/5cXCwlklZMLbHFvv1008TH`
IMP | `C675A428E57574351E2EE5B20E9F2684`
PESHA1 | `EF41F48B51891A31889C79B5D6F220075B01B4D3`
PE256 | `2323F5C0575CF626249FA4A09E29B0DAF0F5D34BE91CA3DFCBF862A2AC73A789`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ShellUICommand_OnImportW` | 16 | Exported Function
`ShellUICommand_OnNewContactW` | 13 | Exported Function
`ShellUICommand_OnExportW` | 17 | Exported Function
`Ordinal9` | 9 | Exported Function
`ShellUICommand_OnEditW` | 15 | Exported Function
`WABOpen` | 2 | Exported Function
`WABOpenEx` | 4 | Exported Function
`WABCreateIProp` | 3 | Exported Function
`ShellUICommand_OnNewEmailW` | 12 | Exported Function
`ShellUICommand_OnNewGroupW` | 14 | Exported Function
`Ordinal8` | 8 | Exported Function
`Ordinal11` | 11 | Exported Function
`Ordinal22` | 22 | Exported Function
`Ordinal10` | 10 | Exported Function
`DllCanUnloadNow` | 18 | Exported Function
`DllGetClassObject` | 19 | Exported Function
`Ordinal6` | 6 | Exported Function
`Ordinal7` | 7 | Exported Function
`Ordinal5` | 5 | Exported Function
`Ordinal23` | 23 | Exported Function
`Ordinal24` | 24 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WAB32.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/c19070b2b39678d7abaea720b117fb6e255b240683798af1331173a7834e131c/detection/

## Possible Misuse

*The following table contains possible examples of `wab32.dll` being misused. While `wab32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s0 = "C:\\Program Files\\Common Files\\System\\wab32" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


