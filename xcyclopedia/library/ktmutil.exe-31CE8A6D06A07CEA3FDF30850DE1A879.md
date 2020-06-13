
# ktmutil.exe 

* File Path: `C:\Windows\SysWOW64\ktmutil.exe`
* Description: Kernel Transaction Management Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `31CE8A6D06A07CEA3FDF30850DE1A879`
SHA1 | `679BD65109B5B2787C0BD302AAEB8FCE57BAEF15`
SHA256 | `A86D1E0C37653BC2E0419D745F15D592AB953FF73DBAC70FCA1745A92F2F4A97`
SHA384 | `88065B16BCA2EDE7E2C99516BDF18FF4888312B7406CB7EC8EE7AFF3A33DC66A60CA3DE04C801C6A6A4EBBC3F11452AA`
SHA512 | `9FA74AF2C6A5121182ED63EC330387D7E8FC104DCD36EE95F63E228607CA511FFF689ECA776E05EA79669844EB1665F1B751C33F2B916A297B6CD6DC4F5016D8`
SSDEEP | `192:ePWd2FYLuezTfOywJk/lPpeH9YXEuSsTtj/IBulj1WavTInklAW8jWj5KiaC:eP92p/Oywuto9YXEtWtj/fgtkWW8jW9`

## Runtime Data

### Usage (stdout):
```Batchfile
-help is an invalid parameter.
---- Commands Supported ----

tx     Commands related to transactions
tm     Commands related to transaction managers

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# ktmutil

Starts the Kernel Transaction Manager utility. If used without parameters, **ktmutil** displays available subcommands.

## Syntax

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

## Examples


To force an Indoubt transaction with GUID 311a9209-03f4-11dc-918f-00188b8f707b to commit, type:

```
ktmutil force commit {311a9209-03f4-11dc-918f-00188b8f707b}
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


