---
title: ktmutil.exe | Kernel Transaction Management Utility
---

# ktmutil.exe 

* File Path: `C:\windows\system32\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `4EA868EA2484EB3DE0598855BA3D8926`
SHA1 | `5F8DDD3AB39B9DA65B7B77E70AFF46873360C89F`
SHA256 | `87883CF0DBE0893AE99305EC110E9B0359BF2844865BEB44706A4C2A14F72481`
SHA384 | `0FDF5628F929B741085632D3BDEC4834F96A95AE9F453F12301BBB399DE30D86A4F1016D5CB3A706090C6E6315F56C0A`
SHA512 | `AC2DFD2B4C746929B27EE2B389FC4521360F1AE519E2A4B47E5A05AE5BD6B17C0F4AC3B05C29A3A4E866F57AB28803CBA170199ACBC826193D538CEA11015B9C`
SSDEEP | `384:DRG4uefNzVpqIuf+N22emFmNdlfATsLS3FsOWIjW:AJeFV8FNNw7FsY`

## Runtime Data

### Usage (stdout):
```Batchfile
-help is an invalid parameter.
---- Commands Supported ----

tx     Commands related to transactions
tm     Commands related to transaction managers

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\ktmutil.exe](ktmutil.exe-A77A5364E36FCB1573C4D41AEB8BDCCD.md) | 63


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ktmutil

Starts the Kernel Transaction Manager utility. If used without parameters, **ktmutil** displays available subcommands.

### Syntax

```
ktmutil list tms
ktmutil list transactions [{TmGUID}]
ktmutil resolve complete {TmGUID} {RmGUID} {EnGUID}
ktmutil resolve commit {TxGUID}
ktmutil resolve rollback {TxGUID}
ktmutil force commit {GUID}
ktmutil force rollback {GUID}
ktmutil forget
```

### Examples


To force an Indoubt transaction with GUID 311a9209-03f4-11dc-918f-00188b8f707b to commit, type:

```
ktmutil force commit {311a9209-03f4-11dc-918f-00188b8f707b}
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


