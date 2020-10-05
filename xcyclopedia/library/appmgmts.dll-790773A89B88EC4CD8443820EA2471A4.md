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

Function Name | Ordinal | Type
-- | -- | --
`GenerateGroupPolicy` | 13 | Exported Function
`IID_IClassAdmin` | 14 | Exported Function
`DllCanUnloadNow` | 11 | Exported Function
`DllGetClassObject` | 12 | Exported Function
`ProcessGroupPolicyObjectsEx` | 15 | Exported Function
`ReleasePackageInfo` | 18 | Exported Function
`ServiceMain` | 19 | Exported Function
`ReleaseAppCategoryInfoList` | 16 | Exported Function
`ReleasePackageDetail` | 17 | Exported Function
`CsUnregisterAppCategory` | 10 | Exported Function
`CsGetAppCategories` | 4 | Exported Function
`CsGetClassAccess` | 5 | Exported Function
`CsCreateClassStore` | 2 | Exported Function
`CsEnumApps` | 3 | Exported Function
`CsGetClassStore` | 6 | Exported Function
`CsServerGetClassStore` | 9 | Exported Function
`CsSetOptions` | 1 | Exported Function
`CsGetClassStorePath` | 7 | Exported Function
`CsRegisterAppCategory` | 8 | Exported Function


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


