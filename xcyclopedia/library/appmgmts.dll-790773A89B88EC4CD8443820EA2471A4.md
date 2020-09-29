---
title: appmgmts.dll | Software installation Service
excerpt: What is appmgmts.dll?
---

# appmgmts.dll 

* File Path: `C:\Windows\SysWOW64\appmgmts.dll`
* Description: Software installation Service

## Hashes

Type | Hash
-- | --
MD5 | `790773A89B88EC4CD8443820EA2471A4`
SHA1 | `718AA275EA26E31B7723C55463014CAB5219CF18`
SHA256 | `59F2B32C3426856EDADD9F4EBF02B502E1677F171284F57E4241D57244F09D4D`
SHA384 | `6AEC834A35144DCE7AFF6702D41EEB9EA089802AB0CCBFEF552B78A301C739B8F5EE2FA01D5446C8BE05EDBA2A46D1F7`
SHA512 | `63884A7415A014541649CBE19719FCFEE007EB3165808539E07168F3AE913455616F68917C3F4C5D9AF0CE44F482054C56D385DB28C2574399BF4E3B1BC5ADA9`
SSDEEP | `3072:zr+FC/+9BeIvPBX671o/Ps68Xi2xN9ldCcI/jlDlpHbSqNLAOZYNM4:n8BHNmo/UPi2xNscwjlDlpHbSqNLAOZy`
IMP | `15314AA9903DAACD3E92A4114D8315FE`
PESHA1 | `8557AA708AFA825000250E6D1BF67F272245879C`
PE256 | `8BDB6FC4371543FC8316E40A70ABD1FBCB8E21A90206CCC7174FD0C2A1474D8F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CsCreateClassStore` | 2 (0x2) | Exported Function | 0x739149f0 | 0x000149f0
`ReleasePackageDetail` | 17 (0x11) | Exported Function | 0x73914ea0 | 0x00014ea0
`ReleaseAppCategoryInfoList` | 16 (0x10) | Exported Function | 0x73914e20 | 0x00014e20
`ProcessGroupPolicyObjectsEx` | 15 (0xf) | Exported Function | 0x7390ca30 | 0x0000ca30
`IID_IClassAdmin` | 14 (0xe) | Exported Function | 0x73903b08 | 0x00003b08
`GenerateGroupPolicy` | 13 (0xd) | Exported Function | 0x7390ce10 | 0x0000ce10
`DllGetClassObject` | 12 (0xc) | Exported Function | 0x73913350 | 0x00013350
`DllCanUnloadNow` | 11 (0xb) | Exported Function | 0x73913330 | 0x00013330
`ReleasePackageInfo` | 18 (0x12) | Exported Function | 0x73914d20 | 0x00014d20
`CsUnregisterAppCategory` | 10 (0xa) | Exported Function | 0x73914b90 | 0x00014b90
`CsServerGetClassStore` | 9 (0x9) | Exported Function | 0x73914ad0 | 0x00014ad0
`CsRegisterAppCategory` | 8 (0x8) | Exported Function | 0x73914b20 | 0x00014b20
`CsGetClassStorePath` | 7 (0x7) | Exported Function | 0x73914c70 | 0x00014c70
`CsGetClassStore` | 6 (0x6) | Exported Function | 0x73914ab0 | 0x00014ab0
`CsGetClassAccess` | 5 (0x5) | Exported Function | 0x739148f0 | 0x000148f0
`CsGetAppCategories` | 4 (0x4) | Exported Function | 0x73914c00 | 0x00014c00
`CsEnumApps` | 3 (0x3) | Exported Function | 0x73914930 | 0x00014930
`CsSetOptions` | 1 (0x1) | Exported Function | 0x73915060 | 0x00015060
`ServiceMain` | 19 (0x13) | Exported Function | 0x7390e470 | 0x0000e470


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: appmgmts.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/59f2b32c3426856edadd9f4ebf02b502e1677f171284f57e4241d57244f09d4d/detection/


## Possible Misuse

*The following table contains possible examples of `appmgmts.dll` being misused. While `appmgmts.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $z5 = "\\appmgmts.dll" fullword ascii /* score: '11.0' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


