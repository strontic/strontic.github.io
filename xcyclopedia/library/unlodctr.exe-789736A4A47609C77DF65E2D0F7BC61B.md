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
MD5 | `789736A4A47609C77DF65E2D0F7BC61B`
SHA1 | `7879DE7ABFBACE22C691F7C05C21A9518C28DDEF`
SHA256 | `E8EEAC85A29EB75A4CF41509EA982AE1B6256D0C7CDFF3299ED3DF3CE34356D9`
SHA384 | `3D7CA89804A9A75FC54F18C362E3426BFC58CE6462CEE8ED7BDAE82BD454991BDEFCE59ED166226289A13204D2A10A2C`
SHA512 | `35FF07C6038C74399176454416118853B48257BF003646E91C10F4D59DE31D4BB5BC502F5D2701C3E8576CB750530D2825C1688DD3C2B59C80BEDFAB5266758C`
SSDEEP | `768:Urp1PX8kHsc3L2CK7JhIlqyTDwI+pXn7M9DdRMTdplMcAujMFwf/wEdk:81PXtHZlqy4IMXn49DdRMTTlMcrCwf4x`
IMP | `F1D5D1A81E34EB75E2AF99A4FB939D87`
PESHA1 | `6A9664A1C14EAD8825F1190C0399D76835956390`
PE256 | `C2AD349F097C56B509D21AB502FDD8100CA627ED25A8FBC06F8A0E830243F59C`

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\unlodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e8eeac85a29eb75a4cf41509ea982ae1b6256d0c7cdff3299ed3df3ce34356d9/detection/



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


