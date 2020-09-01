---
title: lodctr.exe | Load PerfMon Counters
---

# lodctr.exe 

* File Path: `C:\Windows\SysWOW64\lodctr.exe`
* Description: Load PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `D6F483494305B33B5AD931C00B687CC3`
SHA1 | `8FFC384315387F8BBCE2211785285578BB2AF387`
SHA256 | `E64C1CE04A6CE1CFB212C723564B1FAEE575DF75CB51C4E52FBE139BBEABAB92`
SHA384 | `F9FC4D2DEA5F1486F54EA6FEF02564D55B1E9D135F20749A85A235A15F1CD9765730C527189B06F354F37AD5BC1FE7B2`
SHA512 | `95AB79BFE487F88E79FFFE4A11402964F58C61CEA79567B844CB1D46367013CAB06501F0F5928B045769AADB1FD8A4D503DD4C2F4B2D6D0906A3130C330DE42C`
SSDEEP | `768:OmzMb5lM8ZI+u4ov9+nZDl8jBTKcKWi0Mof6NI3tQaQbuxU:mlM8Z3ur8Zyj9KWi0l6oQaQbux`

## Runtime Data

### Usage (stdout):
```Batchfile


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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## lodctr

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


