---
title: ktmutil.exe | Kernel Transaction Management Utility
---

# ktmutil.exe 

* File Path: `C:\Windows\SysWOW64\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `070A0079E0B0602CB63E17C41AE7ABD2`
SHA1 | `B21A37732073B350E944DC09B7D9D5A96663B27F`
SHA256 | `A436C4FF2539B2A65F4787A0AF777075A0E40EF019B78F7276273266F439873C`
SHA384 | `B036C40E3968A313D06B9670D9522493179FAE1B47511AA996216FD65201FF54ABB00B49D6ED06FF17CB3E67D07F6C49`
SHA512 | `F60B2519147C7E2EF7882BF97FC760738311370A3D37E6E015C94E0B25D9154F8ED274A8334A70CC77876ED737F7E97EF7F06722536CB1928D9C26307AD18917`
SSDEEP | `192:kSxPqeQrKDmxryckkF11Hvoz217xi1/6qWkR2m1keWIjWW1T:TxPqUarycPJv62Fx6yhhNeWIjWW1`

## Runtime Data

### Usage (stdout):
```cmhg
--help is an invalid parameter.
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

* Original Filename: ktmutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


