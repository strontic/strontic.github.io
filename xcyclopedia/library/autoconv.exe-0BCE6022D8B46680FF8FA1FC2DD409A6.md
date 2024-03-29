﻿---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\system32\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `0BCE6022D8B46680FF8FA1FC2DD409A6`
SHA1 | `32E731935BED82384AEDE89CE879A6DA05B7B1A0`
SHA256 | `3A2ED5EBD7D053C3328ECFFA4FC7D8A9608329B21449AE901D18BCF5034D5DE5`
SHA384 | `E970427F69E16FC09C29C1655FE30BF2C0F8B39B3DED587D4F6BAEE4AD57D678FEE86B356F18563025271BC5B27D0EBE`
SHA512 | `064CF0A6B5D8A0ED91E900952792EC256DE5305D3CB7D0C3535F60620A10219D6266873027C28D5D4202C2392596157F94FA713AAD0B6F3902AD8C46B0CD3F34`
SSDEEP | `12288:/u58hRuHsVJ8ENoekZ88Z+IdU8gu3Z4ERetAbbJ5UCYD1X:/u5+RuMVTfkZ88Z+Idr3D6YfUC81`

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
* File Version: 10.0.14393.1532 (rs1_release_d.170711-1840)
* Product Version: 10.0.14393.1532
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




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


