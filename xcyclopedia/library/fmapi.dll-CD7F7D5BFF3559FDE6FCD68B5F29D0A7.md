---
title: fmapi.dll | File Management API
excerpt: What is fmapi.dll?
---

# fmapi.dll 

* File Path: `C:\Windows\system32\fmapi.dll`
* Description: File Management API

## Hashes

Type | Hash
-- | --
MD5 | `CD7F7D5BFF3559FDE6FCD68B5F29D0A7`
SHA1 | `54DAAA8D71C723B96A658D07B804F305204AC57B`
SHA256 | `CD375AEAB416E68C62ED19BC2F2C5E59725CE3BE1F92F2DAAEA0C8298917D4ED`
SHA384 | `11DCB5A1231B6841C159F4BAA14694EB7C16B2F95AB5FDA0B841E69127FF55F0148C8C7EFE99233E8EFFD870DEC11DA8`
SHA512 | `9916FC444F6D9BB50F470ED2D2288518A984B8A908293AFD52E9A15C39F00DC2CCE9663ABCBBC940303C49C68D33A5A7B0D13636956F468B2863F39737B8CF0F`
SSDEEP | `1536:RkMyR7TMzLXqUoyNegAjFlgk5zXXceHJ:RLyRngLaQUR55TZJ`
IMP | `9285E8E2DCDE852BFE955DEEE3B50ADB`
PESHA1 | `ED10535D5D53B09107C098B879A5B4D3774F0DFB`
PE256 | `7C4B6058FBA68674B9060B694649FAE75DEEA02CCA09C1041E4608272D62EA57`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CloseFileRestoreContext` | 1 | Exported Function
`CreateFileRestoreContext` | 2 | Exported Function
`DetectBootSector` | 3 | Exported Function
`DetectEncryptedVolume` | 4 | Exported Function
`DetectEncryptedVolumeEx` | 5 | Exported Function
`RestoreFile` | 6 | Exported Function
`ScanRestorableFiles` | 7 | Exported Function
`SupplyDecryptionInfo` | 8 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FMAPI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/cd375aeab416e68c62ed19bc2f2c5e59725ce3be1f92f2daaea0c8298917d4ed/detection/


## Possible Misuse

*The following table contains possible examples of `fmapi.dll` being misused. While `fmapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`fmapi.dll`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


