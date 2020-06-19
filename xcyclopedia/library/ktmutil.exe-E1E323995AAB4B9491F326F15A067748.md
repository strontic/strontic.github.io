
# ktmutil.exe 

* File Path: `C:\Windows\system32\ktmutil.exe`
* Description: Kernel Transaction Management Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E1E323995AAB4B9491F326F15A067748`
SHA1 | `D4C9BB80E016DE127287B3C84F81C37AF38A5564`
SHA256 | `8567448C90730513C238D6EFB0350E0A645EBC23CBC4A69E88AD78CD5F70CDEB`
SHA384 | `CB7B8929F1B9D34C7395A68ACE2163ACF97D406351CACBAA6DF1DBE7062D999C44ACCB1F29659C9E0942E3D5EBA87067`
SHA512 | `6FB2BC407014FE3F6E03431F6A1DE4F00158C1B0C7D9E108DF3BC09D95323994FADF555CFAA16BAD30EFB318F53849B17E092F135D261B02ABBD8B13BEBC3318`
SSDEEP | `384:qbzPHplMV00/RJWZtq6Ext6+NQfA+D2XSPf+mW8jW:qbDzMVPQZjEvNDI2CP2k`

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


