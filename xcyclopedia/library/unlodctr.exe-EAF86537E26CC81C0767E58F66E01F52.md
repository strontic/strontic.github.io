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
MD5 | `EAF86537E26CC81C0767E58F66E01F52`
SHA1 | `D9F24D699714586148342700F4490F7597AB0E7B`
SHA256 | `68E5607D0AA1A52BFF70FE53C7EB0C5D27B342886BCBFEA7FBFEFD4168951F9B`
SHA384 | `E797E79E9DF90E0A881B1253E0FE5C39C83F09C4A53BB242C3D3C1B2BF4149793D53268D684B09284A9D85FCC708CCDC`
SHA512 | `75E591DBAC45ED1559559A47405D2E934D3D41D1E37CBB712F575DBF140509C3C60FE335E60006331C8E694558CE8635E116E7EDD244D5105664EAE79BFC2524`
SSDEEP | `768:jZlM8QoRNUQ8QkY6krH0CUEGuDSnhTUflUk:9lM8XUVYH0Cyu+nxUflU`
IMP | `6A4B1735A0F46C1BF9026F6600020288`
PESHA1 | `23D8C0A6C8293D7D67DC2F7019C9F114C28F994D`
PE256 | `690A1C81EC98F8D4F8A9E5D6D19038654AE8F0D087F6200AA342150D3D246492`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\unlodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/68e5607d0aa1a52bff70fe53c7eb0c5d27b342886bcbfea7fbfefd4168951f9b/detection/



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


