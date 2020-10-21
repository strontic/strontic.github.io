---
title: unlodctr.exe | Unload PerfMon Counters
excerpt: What is unlodctr.exe?
---

# unlodctr.exe 

* File Path: `C:\Windows\system32\unlodctr.exe`
* Description: Unload PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `4848684A588767F7CFFCB3A4A082298C`
SHA1 | `0E0FD513510B023AE108BF6FB62F490627415B4C`
SHA256 | `9B602BD2CF08116F97E1027DD3E298CE5E2B68E80BED44F036F05B69A3FEF611`
SHA384 | `C81A4E2FE575FB05510FE0D35C4CCC6FA1312110B446F449AF6515BCF8C5A77D9D708394651F0914E52719AE473E56B9`
SHA512 | `F74D965F60FB1DA090A01A2CD79120A186AB05792FB33D97CD7475AC53DBA2E019A230368DD7DB2D373C2A3CB5FA0BF757589675545D0CEF9D173F3DE2F094AB`
SSDEEP | `768:g9NoRoVpmPn7iPm/e8JbRbUAQetzNBwSsplMcAF91hBMNfrY/6k:8lVY/eY9brQetzNBwXlMcsWNf8/6k`
IMP | `364FF6B7A19CFFA3572DE0AF156CB0D6`
PESHA1 | `B095A64F19CEA689DD863A62A0FF8DB9335A7958`
PE256 | `23453A7969F7810F45EE1622B00BDAD6066D4A13829A9DA216F1EC86F67B26DD`

## Runtime Data

### Usage (stdout):
```cmhg


UNLODCTR
    Removes counter names and explain text for the specified extensible counter.

Usage:

    UNLODCTR <driver>
        driver is the name of the device driver which is to have its
            counter name definitions and explain text removed from the system's
            registry.

    UNLODCTR /m:<manifest>
        manifest is the name of the manifest file that contains performance
            counter definitions. These counters will be removed from local system.

    UNLODCTR /g:{ProviderGuid}
        ProviderGuid identifies the performance counter provider being unloaded.

    UNLODCTR /p:<ProviderName>
        ProviderName identifies the performance counter provider being unloaded.

Note: any arguments with spaces in the names must be enclosed within
Double Quotation marks.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\loadperf.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\unlodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/9b602bd2cf08116f97e1027dd3e298ce5e2b68e80bed44f036f05b69a3fef611/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## unlodctr

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


