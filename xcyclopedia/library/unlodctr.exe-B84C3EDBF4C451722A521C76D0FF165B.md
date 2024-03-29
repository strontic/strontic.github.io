﻿---
title: unlodctr.exe | Unload PerfMon Counters
excerpt: What is unlodctr.exe?
---

# unlodctr.exe 

* File Path: `C:\WINDOWS\system32\unlodctr.exe`
* Description: Unload PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `B84C3EDBF4C451722A521C76D0FF165B`
SHA1 | `F58A55B1E550B8E361D9F6F94FA352FF9A83182B`
SHA256 | `706E3960A71410262D58E5C3FA31B1F0122D3D0694ED9D9CAC14D2795F0B5881`
SHA384 | `909FF07ED208B1ECBA225EE839C84C639F7941A7D1C220AE2BB1A7057990F10E38D9EAE77DA6B1BE509E91CA3CF90B2E`
SHA512 | `47DCB7990D4F564642CD66A634CEDBB07D2380E2CEBAF5C8BFDA9604D09675781FC3BD5BE89D85A2A0140E0E6AD28CB75975581AB1463DE64E0BF80A041D0619`
SSDEEP | `768:z9N+RoJpmPn7ilm/Q8JbRbUPQqtzNBwMplMcA49DM5fseF2k:ZzJm/QY9bMQqtzNBwOlMcHI5fpF2k`

## Runtime Data

### Usage (stdout):
```cmhg

 
UNLODCTR 
       uninstalls a performance counter provider. 
Usage: 
       UNLODCTR <service-name> 
             uninstalls the v1.0 performance counter provider associated 
             with the <service-name> service.
       UNLODCTR /m:<manifest> 
             uninstall a v2.0 performance counter provider using the 
             provider GUID from the specified XML manifest.
       UNLODCTR /g:{ProviderGuid} 
             uninstall a v2.0 performance counter provider using the 
             specified provider GUID. The GUID should be specified in 
             registry form, i.e. {nnnnnnnn-nnnn...}
       UNLODCTR /p:<ProviderName> 
             uninstall a v2.0 performance counter provider matching the 
             specified provider name.

Note: any arguments with spaces in the names must be enclosed within double 
quotation marks.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## unlodctr

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Removes **Performance counter names** and **Explain text** for a service or device driver from the system registry.

> [!WARNING]
> Incorrectly editing the registry may severely damage your system. Before making changes to the registry, you should back up any valued data on the computer.

### Syntax

```
unlodctr <drivername>
```

#### Parameters

| Parameter | Description |
|--|--|
| `<drivername>` | Removes the **Performance counter name** settings and **Explain text** for driver or service `<drivername>` from the Windows Server registry. If your `<drivername>` includes spaces, you must use quotation marks around the text, for example "Driver name". |
| /? | Displays help at the command prompt. |

### Examples

To remove the current **Performance counter names** and **Explain text** for the Simple Mail Transfer Protocol (SMTP) service, type:

```
unlodctr SMTPSVC
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


