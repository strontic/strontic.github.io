---
title: ktmutil.exe | Kernel Transaction Management Utility
excerpt: What is ktmutil.exe?
---

# ktmutil.exe 

* File Path: `C:\WINDOWS\SysWOW64\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `8F497AF3D407A2EA99F565E770381AB6`
SHA1 | `6A71475BEDAA68F8F5B789CA7B646B099169EC59`
SHA256 | `E37F0E57BAC96DF33550E435CF01370EC85B04746E9AFAF129F2D981A7A89086`
SHA384 | `0C895E738A9FDB0128D194DFBC0991058797B1A2FE8BDD972174FE2FEADB73D820C691DE51F3B433B054ADC03974AEFD`
SHA512 | `D906AA0115F98243AA8E6F463472D4B3368B166148CFC2CA40402A11CDF470A76BF1949E98170A177A55E5D7CD4A7011CBCA80ACC062888ABBCFEA991875F669`
SSDEEP | `192:PI/PIy9gY/DeFe5r50ktx4czUkyA8kQGgJh8hXnkeWcjWqcG:Q/PneFm5ftLUkyAIJHeWcjWx`
IMP | `F5B0BFF689194F5FCA291D9A9715C853`
PESHA1 | `2CEFCAA023FC31E0FCEC39BC7EDBF7AD04F2400B`
PE256 | `1B076AAF7F7697F119FA1423D4EBB52CCDCA4C0BE2B5493B9A4E3A207A7B868E`

## Runtime Data

### Usage (stdout):
```cmhg
--help is an invalid parameter.
---- Commands Supported ----

tx     Commands related to transactions
tm     Commands related to transaction managers

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\ktmutil.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e37f0e57bac96df33550e435cf01370ec85b04746e9afaf129f2d981a7a89086/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


