---
title: ntshrui.dll | Shell extensions for sharing
excerpt: What is ntshrui.dll?
---

# ntshrui.dll 

* File Path: `C:\Windows\system32\ntshrui.dll`
* Description: Shell extensions for sharing

## Hashes

Type | Hash
-- | --
MD5 | `2FC44E0B0E79BB674B0AA2A883CADF76`
SHA1 | `2FB5E33DBCB9C3FD3AC68F99D50C9AC1BE691B58`
SHA256 | `926A49877FA1062180DF67AEBD5CB7B9340E75F9FB265CEC54EC6640101558CA`
SHA384 | `29C0089DEFF1911547123B1F8CE2DABCF463511D62315B57C40A4A480D948F5898B1A57846E5887BB679F2F6C06CF93D`
SHA512 | `DF8A7B604AE5C11776F3C954E2278B3CF7C57AD5E5B95F340CA68C4A99695DBA6474E1A9C905C10F023BEB8BBED12137DB3D7ED8840BA47B9535E04625E35099`
SSDEEP | `12288:/5c5uhLEaKGzo0vB7i5Td49hAylRzIo2Mhf:awT/JcTy9hA8REo2+`
IMP | `E5D50A1E1DCB2985F3BEAF081E0FE694`
PESHA1 | `079A3DA3B1CB43436DFF9CBA35E245965DA242D5`
PE256 | `78FA49167B5E4CBAD577734E90714790F49AC73085D4C37E198B56E0D782B00D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`IsPathShared` | 11 | Exported Function
`IsFolderPrivateForUser` | 10 | Exported Function
`GetNetResourceFromLocalPathW` | 9 | Exported Function
`IsPathSharedA` | 12 | Exported Function
`ShowShareFolderUI` | 15 | Exported Function
`SetFolderPermissionsForSharing` | 14 | Exported Function
`IsPathSharedW` | 13 | Exported Function
`GetNetResourceFromLocalPathA` | 8 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function
`CanShareFolder` | 1 | Exported Function
`GetLocalPathFromNetResource` | 4 | Exported Function
`GetNetResourceFromLocalPath` | 7 | Exported Function
`GetLocalPathFromNetResourceW` | 6 | Exported Function
`GetLocalPathFromNetResourceA` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntshrui.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/926a49877fa1062180df67aebd5cb7b9340e75f9fb265cec54ec6640101558ca/detection/


## Possible Misuse

*The following table contains possible examples of `ntshrui.dll` being misused. While `ntshrui.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [groundbait](https://github.com/eset/malware-ioc/blob/master/groundbait/README.adoc) | `- `%WINDIR%\ntshrui.dll`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


