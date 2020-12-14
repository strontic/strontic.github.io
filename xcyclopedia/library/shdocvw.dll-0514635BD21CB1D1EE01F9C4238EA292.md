---
title: shdocvw.dll | Shell Doc Object and Control Library
excerpt: What is shdocvw.dll?
---

# shdocvw.dll 

* File Path: `C:\Windows\system32\shdocvw.dll`
* Description: Shell Doc Object and Control Library

## Hashes

Type | Hash
-- | --
MD5 | `0514635BD21CB1D1EE01F9C4238EA292`
SHA1 | `0BDD6BFAB0D6FB84D295A322210148855CCFF00B`
SHA256 | `340505D3B12B73EA74D111F8522BA85E1957C0593516CAE08F2682E2522AE77D`
SHA384 | `FCF34D223AAADB4BF5E7398CCBF91AC661B5CAECFEBD2BBD8AD5668CEA42EE4D4B0E094C4A184A494C05FBC598512B4F`
SHA512 | `BDDB941ED74B6D7E3B3CA97C044F47B3CB1B965C894E249C9AFB8CFD9B89B6EDD746843D0DD0756028BF4941D25165EA46B7443EC3A38034B45B566C7B03913C`
SSDEEP | `6144:fy4+l30qgq8J+0V0EEbNtVFAZyl48pArv8kEAxihTlyRmo:fy4+lhgq8J+ROyl48pArv8cx06m`
IMP | `976A58162EC56583A031B05BE5951CDB`
PESHA1 | `832DC5CC0B9F931AE669319A15E132F239304F8D`
PE256 | `E2A00041FD8D4A68879027F70F9071D07EB15442FFE0371ADBDF8C6CC26A00FF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`OpenURL` | 154 | Exported Function
`SafeOpenPromptForShellExec` | 228 | Exported Function
`SetQueryNetSessionCount` | 156 | Exported Function
`HlinkFrameNavigate` | 133 | Exported Function
`HlinkFrameNavigateNHL` | 134 | Exported Function
`ImportPrivacySettings` | 144 | Exported Function
`SoftwareUpdateMessageBox` | 166 | Exported Function
`URLQualifyA` | 168 | Exported Function
`URLQualifyW` | 182 | Exported Function
`SetShellOfflineState` | 157 | Exported Function
`SHAddSubscribeFavorite` | 163 | Exported Function
`SHGetIDispatchForFolder` | 155 | Exported Function
`HlinkFindFrame` | 132 | Exported Function
`DllGetVersion` | 109 | Exported Function
`DllRegisterWindowClasses` | 112 | Exported Function
`DoAddToFavDlg` | 113 | Exported Function
`AddUrlToFavorites` | 106 | Exported Function
`DllCanUnloadNow` | 107 | Exported Function
`DllGetClassObject` | 108 | Exported Function
`DoOrganizeFavDlg` | 127 | Exported Function
`DoOrganizeFavDlgW` | 128 | Exported Function
`DoPrivacyDlg` | 129 | Exported Function
`DoAddToFavDlgW` | 114 | Exported Function
`DoFileDownload` | 124 | Exported Function
`DoFileDownloadEx` | 126 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SHDOCVW.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/340505d3b12b73ea74d111f8522ba85e1957c0593516cae08f2682e2522ae77d/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\shdocvw.dll](shdocvw.dll-D302FEDA2281C40E331399742BB0FB69.md) | 61

## Possible Misuse

*The following table contains possible examples of `shdocvw.dll` being misused. While `shdocvw.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `Name: Shdocvw.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `- Command: rundll32.exe shdocvw.dll,OpenURL "C:\test\calc.url"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `- Path: c:\windows\system32\shdocvw.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `- Path: c:\windows\syswow64\shdocvw.dll` | 



MIT License. Copyright (c) 2020 Strontic.


