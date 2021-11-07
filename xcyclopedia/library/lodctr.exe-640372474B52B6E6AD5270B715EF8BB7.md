---
title: lodctr.exe | Load PerfMon Counters
excerpt: What is lodctr.exe?
---

# lodctr.exe 

* File Path: `C:\Windows\SysWOW64\lodctr.exe`
* Description: Load PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `640372474B52B6E6AD5270B715EF8BB7`
SHA1 | `4E7FC5F7D9B661870BDA024FA54504F5C7BAE269`
SHA256 | `914650F6DC5783422E107159E0B69A0917D43CD5016ECDC14F06577A11FF36F0`
SHA384 | `AE56A672D41CC78F12B613A6CEFFA298F56AB5561789DE1456A6581B992497F953122D6A2BF307988887E63E5396375A`
SHA512 | `9FC20F8B0174D5A0C50E04B8BCDE19E501ED9CDD2156050E7E743D681387A7BE15427625CA54C8461E1340E90CAF1BA4735DC13EED132DE383434045D863EDAE`
SSDEEP | `768:5C3ZlM8ZNqJEwWrGqYhv3THEDyHLeFm58VpczADyMbGegaYnHSw7tDQg:glM8qJEDSv3THEDqeFBVC5HSw7tD`
IMP | `71291F34C89AC0954E83161A791661D5`
PESHA1 | `AB1A41C2FCA99F3209E3C3BA2DDDB8F8DDFC30B7`
PE256 | `77C367EA2FC992CEBEFDA809C730001A5353E37B0D2EF85E8758C35ADE74553B`

## Runtime Data

### Usage (stdout):
```cmhg


LODCTR
    Updates registry values related to performance counters.

Usage:
    LODCTR <INI-FileName>
        INI-FileName is the name of the initialization file that contains
            the counter name definitions and explain text for an extensible
            counter DLL.

    LODCTR /S:<Backup-FileName>
        save the current perf registry strings and info to <Backup-FileName>

    LODCTR /R:<Backup-FileName>
        restore the perf registry strings and info using <Backup-FileName>

    LODCTR /R
        rebuild the perf registry strings and info from scratch based on the current
            registry settings and backup INI files.

    LODCTR /T:<Service-Name>
        set the performance counter service as trusted.

    LODCTR /E:<Service-Name>
        enable the performance counter service.

    LODCTR /D:<Service-Name>
        disable the performance counter service.

    LODCTR /Q

    LODCTR /Q:<Service-Name>
        query the performance counter service information, either query all or specified one.

    LODCTR /M:<Counter-Manifest>
        install Windows Vista performance counter provider definition XML file
            to system repository.

Note: any arguments with spaces in the names must be enclosed within
Double Quotation marks.

```

### Child Processes:
explorer.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\lodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/914650f6dc5783422e107159e0b69a0917d43cd5016ecdc14f06577a11ff36f0/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## lodctr

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Allows you to register or save performance counter name and registry settings in a file and designate trusted services.

### Syntax

```
lodctr <filename> [/s:<filename>] [/r:<filename>] [/t:<servicename>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<filename>` | Specifies the name of the initialization file that registers the performance counter name settings and explanatory text. |
| /s:`<filename>` | Specifies the name of the file to which the performance counter registry settings and explanatory text are saved. |
| /r | Restores counter registry settings and explanatory text from current registry settings and cached performance files related to the registry. |
| /r:`<filename>` | Specifies the name of the file that restores the performance counter registry settings and explanatory text.<p>**Warning:** If you use this command, you'll overwrite all performance counter registry settings and explanatory text, replacing them with the configuration defined in the specified file. |
| /t:`<servicename>` | Indicates that service `<servicename>` is trusted. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "file name 1").

#### Examples

To save the current performance registry settings and explanatory text to file *"perf backup1.txt"*, type:

```
lodctr /s:"perf backup1.txt"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


