---
title: ktmutil.exe | Kernel Transaction Management Utility
---

# ktmutil.exe 

* File Path: `C:\WINDOWS\SysWOW64\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `F84E4F0AA4164FE40433C03D20618952`
SHA1 | `1EF34E4056F6E525A27F486250274118253A8BA1`
SHA256 | `D5E6AB8F2C873F0A62E14E05A74DB3B671657F417D7143B04C743543B76577DB`
SHA384 | `5644542CBC0940A85C02D02E932EAA016FEFE15095E84D1CE99C3323CD34F058D8F4635155F6CF6C1A0842747E21C551`
SHA512 | `AA910D6520564E79773EBE6FF2CF91452FD10BBA773EBD0521F2023357F429327327768CB2428033EAE3934A769BC42FE4F43DA66FA1178DA6FBE755E39B5EE0`
SSDEEP | `192:L7RP5w/3p4VZycwkCdwGZpvCBzqtQrdl/6qWuR2m1k+W+jWyI:/RP8SZycLSpvC9qtwyhDN+W+jW`

## Runtime Data

### Usage (stdout):
```Batchfile
The KTMUTIL utility requires that you have administrative privileges.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\ktmutil.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ktmutil.exe](ktmutil.exe-AC387D5962B2FE2BF4D518DD57BA7230.md) | 65


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


