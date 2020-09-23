---
title: ktmutil.exe | Kernel Transaction Management Utility
excerpt: What is ktmutil.exe?
---

# ktmutil.exe 

* File Path: `C:\windows\SysWOW64\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `F33B449DAF77F40ED41707EBFBC2DED7`
SHA1 | `295403613145C1BB520D68F87683289981E7748D`
SHA256 | `0D3BEF6EF8809E17F5EB943825C76813198F32AA8BD49B3DB7E9C2B0DEC184D2`
SHA384 | `0052D67E292B44E73987F77C6E4EFA46AB1ECC19F047BEF55E5FAFCDB8A1BAE616380EDFD224E76E0175A54DC91D7C1D`
SHA512 | `E8B5DBF4B188F6C01F86397CCE804144253553BE21EBFE31C9DF3F3720DC865DE58FD867D5D7D3107CEFA67056ECD1E654299EC37765D4A792D5F3CA039809A1`
SSDEEP | `192:1PCRLNGTRxlyFfJpehFxtoXkzTVsas6Ps9NC10Fck+WRjWvzx:1PCylyFy3toXkfVnuTx5+WRjW7`

## Signature

* Status: The file C:\windows\SysWOW64\ktmutil.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ktmutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


