---
title: unlodctr.exe | Unload PerfMon Counters
excerpt: What is unlodctr.exe?
---

# unlodctr.exe 

* File Path: `C:\Windows\SysWOW64\unlodctr.exe`
* Description: Unload PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `F27AEE2E93F96E6DF370C0D83CF31D97`
SHA1 | `0973E0BCB0CE3D7390953A21C5530AFD400C18AD`
SHA256 | `47CF991CA0F91ADCD98AF1BADE9E2BCE82600D842237404BD6A5313A539B2E13`
SHA384 | `D544A44EE41BBD2FEE5A75190AED821284F5DFBDE383E4AA61A02BE346EA3AA07DD5985582BA3F89276AF7A9B2FFDAFE`
SHA512 | `8BCBD26F616D54441650DF2A83DBD20714F6674B83BB04B891C45C6F18600ABCB07371A852EAE8779FFB0AD22D376158337658F7E0F0033FD6F3507BA8C04111`
SSDEEP | `768:uZlM8QUUYOByqUZvtUPWVj9RjGd+QfHP:8lM81UrovtUPa9VG0QfHP`
IMP | `54DCED0AF2D07BD064A46424718177C1`
PESHA1 | `B7836D58305BF46E088BC7B348ABE48EA69FF12C`
PE256 | `CC31630D72678D59FEF60C123846AFC9BDA754688A33E0F828777F69BCAF0579`

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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/47cf991ca0f91adcd98af1bade9e2bce82600d842237404bd6a5313a539b2e13/detection/



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


