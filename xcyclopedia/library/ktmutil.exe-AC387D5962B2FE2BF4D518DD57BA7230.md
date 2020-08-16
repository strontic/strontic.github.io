---
title: ktmutil.exe | Kernel Transaction Management Utility
---

# ktmutil.exe 

* File Path: `C:\Windows\SysWOW64\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `AC387D5962B2FE2BF4D518DD57BA7230`
SHA1 | `511D913F817DD36995035DFA64FB2D7F171CCDCB`
SHA256 | `180305260DA3DD77215DCA061C10B869CD69307E9D0CFFFCAFA27CCEC0AF71B3`
SHA384 | `91CC0961810E5F582A1E8C02E6ADA1ACBCA44378CF2628CAEAE5EE90B2EBEB545D1CBF7144B137CD77CE8B2CB3591402`
SHA512 | `57F0AD17B3C0B05FD228672CDB72DF0DEDC3AED176CB5D29152A99665C250A72231FCE3631C5FEABB4820B16A27749CC840B4B89091DB5DE38A8503F8DE69263`
SSDEEP | `192:yj5P8awg3p4VZycwkCdwGZp/CBzqtQrdxrtWOPZsTkOWjjWTI:Y5P9SZycLSp/C9qtMQOTOWjjW`

## Runtime Data

### Usage (stdout):
```Batchfile
--help is an invalid parameter.
---- Commands Supported ----

tx     Commands related to transactions
tm     Commands related to transaction managers

```

## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\ktmutil.exe](ktmutil.exe-F84E4F0AA4164FE40433C03D20618952.md) | 65


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


