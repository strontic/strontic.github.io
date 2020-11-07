---
title: acledit.dll | Access Control List Editor
excerpt: What is acledit.dll?
---

# acledit.dll 

* File Path: `C:\Windows\system32\acledit.dll`
* Description: Access Control List Editor

## Hashes

Type | Hash
-- | --
MD5 | `7C2B65E0756E0DC59E0BE5D9EFD25DA0`
SHA1 | `F6303B5239DD8BD5153E7F7C3593CAD714462373`
SHA256 | `B89C8B36A4AF02D835DC07B7A905E1A3F95308AAC92F614810DD69EB71D9FFFB`
SHA384 | `2FD4209C7BBBF87514A775C62D4B0871968BDAA58E306303939B420622A9BBF1AA38F98F2B7635284A0982593E00A21E`
SHA512 | `3C76ACD4F5963BD3AD7A14449DAB8BD16E4BB6F8DF01070D3907398BE65BE56935C8CF204FC1D47C12CE1EB5EACEBC098845C6D4543189455C75F18D638F0CFA`
SSDEEP | `96:lYEn2RqMoqNGINrOp2Q96GOGZgmPlx2sVN2est7hnlCdCEW1YTWw9:iE2Qt8/9hGOG7L2WUNhnlgPW2TW`
IMP | `02F6FC922B46BF9B846109DCFB249D30`
PESHA1 | `9C2AD3553AE3DDC4F202E3AEF89717FCCFE5F00C`
PE256 | `9BCBB9DD596431B352C4258C965DA2307A3D47A8A4B9F6DCE71BB1F9F9436DCF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllMain` | 5 | Exported Function
`EditAuditInfo` | 1 | Exported Function
`EditOwnerInfo` | 2 | Exported Function
`EditPermissionInfo` | 3 | Exported Function
`FMExtensionProcW` | 4 | Exported Function
`SedDiscretionaryAclEditor` | 6 | Exported Function
`SedSystemAclEditor` | 7 | Exported Function
`SedTakeOwnership` | 8 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: acledit.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/b89c8b36a4af02d835dc07b7a905e1a3f95308aac92f614810dd69eb71d9fffb/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\acledit.dll](acledit.dll-4A2E04302B180C7C6F42ACC015DA5E59.md) | 35

## Possible Misuse

*The following table contains possible examples of `acledit.dll` being misused. While `acledit.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.acledit.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


