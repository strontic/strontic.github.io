---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\system32\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `E30D46B57775A96BA95C278B5585F461`
SHA1 | `E2FD0D30BEC1BCB79DE2F475974AE4D7EFD09375`
SHA256 | `B903052E0D28C704BB0D7C1A36ECED237369C7AE0418145D4BB65C63005CDA2F`
SHA384 | `C9BB2BE934B5AF711E9299548EF766CA2028CBEF1FBC06CEEDF33F43603AA4758242119A8D1E7F08EEE9416FD1BDE8BC`
SHA512 | `C611460732311640FAF595FC5EA0D4BA425E3A1F1F8CE29C14AFCDDE347A75572BDD27ADD0E397112AE07F96E0FD325D3E415580F878F0F88ED8D54A40F63766`
SSDEEP | `12288:ZKjQS7zj4CAjH0cQNMLazUrFRtyFEvEo3uXDMhHncRqRLr:ZKj5dAjH0cjLazUJR8Fv9U3`
IMP | `E9FDC6BDE106C2C586A88FF5CCC36209`
PESHA1 | `9025BF3BDD1F065EBB6563A82E0FDF60B291E60A`
PE256 | `42F4262A2217DB3AFEAF292313BA34C9771ADE8768CD4412C125134B81225D52`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/b903052e0d28c704bb0d7c1a36eced237369c7ae0418145d4bb65c63005cda2f/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


