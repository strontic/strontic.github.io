---
title: shdocvw.dll | Shell Doc Object and Control Library
excerpt: What is shdocvw.dll?
---

# shdocvw.dll 

* File Path: `C:\Windows\SysWOW64\shdocvw.dll`
* Description: Shell Doc Object and Control Library

## Hashes

Type | Hash
-- | --
MD5 | `D302FEDA2281C40E331399742BB0FB69`
SHA1 | `519C55D3EF5691017D76F42C1FA3CF8EE6150B8C`
SHA256 | `1FE182809BB3BD3FCC2A0A0AB1989032D36111B2512D89AEB01E63534CC7D006`
SHA384 | `36D50D6237770F4B63AB804D82782B48E50C83B99848AFC8D2DAC3D21E9D526C358562CD0F0E2F4CB470AB0A1B648EA2`
SHA512 | `B6072283F98EF30E0E0FE0953D4B00A2B0B8DF0CE4E70CA65B53C9D18A224F2DC81DF5C906E0AE0A584C255C59FD0752C4DD362B114F6D3E495DB31C22A185F3`
SSDEEP | `6144:lG2EqKgMs3lyl48pArv8kEVrxihTlyRmo:lG25Vyl48pArv8Jx06m`
IMP | `308EBA2447EACC50E0D138F9631F08F3`
PESHA1 | `8C1462C01FCBB01120D217451D7B2AC5CF213D95`
PE256 | `522AE6F8D502CB3B300B6566185481A379B0C68E1D9045D2A52BAF67BAF04A6F`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`AddUrlToFavorites` | 106 | Exported Function
`SoftwareUpdateMessageBox` | 166 | Exported Function
`SHGetIDispatchForFolder` | 155 | Exported Function
`SHAddSubscribeFavorite` | 163 | Exported Function
`SetShellOfflineState` | 157 | Exported Function
`SetQueryNetSessionCount` | 156 | Exported Function
`SafeOpenPromptForShellExec` | 228 | Exported Function
`OpenURL` | 154 | Exported Function
`ImportPrivacySettings` | 144 | Exported Function
`HlinkFrameNavigateNHL` | 134 | Exported Function
`HlinkFrameNavigate` | 133 | Exported Function
`URLQualifyA` | 168 | Exported Function
`HlinkFindFrame` | 132 | Exported Function
`DoOrganizeFavDlgW` | 128 | Exported Function
`DoOrganizeFavDlg` | 127 | Exported Function
`DoFileDownloadEx` | 126 | Exported Function
`DoFileDownload` | 124 | Exported Function
`DoAddToFavDlgW` | 114 | Exported Function
`DoAddToFavDlg` | 113 | Exported Function
`DllRegisterWindowClasses` | 112 | Exported Function
`DllGetVersion` | 109 | Exported Function
`DllGetClassObject` | 108 | Exported Function
`DllCanUnloadNow` | 107 | Exported Function
`DoPrivacyDlg` | 129 | Exported Function
`URLQualifyW` | 182 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SHDOCVW.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/1fe182809bb3bd3fcc2a0a0ab1989032d36111b2512d89aeb01e63534cc7d006/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\shdocvw.dll](shdocvw.dll-0514635BD21CB1D1EE01F9C4238EA292.md) | 61

## Possible Misuse

*The following table contains possible examples of `shdocvw.dll` being misused. While `shdocvw.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `Name: Shdocvw.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `- Command: rundll32.exe shdocvw.dll,OpenURL "C:\test\calc.url"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `- Path: c:\windows\system32\shdocvw.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shdocvw.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shdocvw.yml) | `- Path: c:\windows\syswow64\shdocvw.dll` | 



MIT License. Copyright (c) 2020 Strontic.


