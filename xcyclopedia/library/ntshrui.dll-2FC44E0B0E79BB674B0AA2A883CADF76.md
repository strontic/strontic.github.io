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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CanShareFolder` | 1 (0x1) | Exported Function | 0x0000000180020b00 | 0x00020b00
`DllCanUnloadNow` | 2 (0x2) | Exported Function | 0x000000018000a000 | 0x0000a000
`DllGetClassObject` | 3 (0x3) | Exported Function | 0x000000018000eef0 | 0x0000eef0
`GetLocalPathFromNetResource` | 4 (0x4) | Exported Function | 0x0000000180020c00 | 0x00020c00
`GetLocalPathFromNetResourceA` | 5 (0x5) | Exported Function | 0x0000000180020c00 | 0x00020c00
`GetLocalPathFromNetResourceW` | 6 (0x6) | Exported Function | 0x0000000180020c30 | 0x00020c30
`GetNetResourceFromLocalPath` | 7 (0x7) | Exported Function | 0x0000000180020c00 | 0x00020c00
`GetNetResourceFromLocalPathA` | 8 (0x8) | Exported Function | 0x0000000180020c00 | 0x00020c00
`GetNetResourceFromLocalPathW` | 9 (0x9) | Exported Function | 0x000000018000ece0 | 0x0000ece0
`IsFolderPrivateForUser` | 10 (0xa) | Exported Function | 0x00000001800495d0 | 0x000495d0
`IsPathShared` | 11 (0xb) | Exported Function | 0x0000000180020c00 | 0x00020c00
`IsPathSharedA` | 12 (0xc) | Exported Function | 0x0000000180020c00 | 0x00020c00
`IsPathSharedW` | 13 (0xd) | Exported Function | 0x000000018000eba0 | 0x0000eba0
`SetFolderPermissionsForSharing` | 14 (0xe) | Exported Function | 0x0000000180049860 | 0x00049860
`ShowShareFolderUI` | 15 (0xf) | Exported Function | 0x0000000180020c90 | 0x00020c90


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


