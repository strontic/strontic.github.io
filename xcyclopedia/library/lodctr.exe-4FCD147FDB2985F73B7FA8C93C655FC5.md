---
title: lodctr.exe | Load PerfMon Counters
---

# lodctr.exe 

* File Path: `C:\windows\system32\lodctr.exe`
* Description: Load PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `4FCD147FDB2985F73B7FA8C93C655FC5`
SHA1 | `94DC43EB604194B88789464446468F791A38D735`
SHA256 | `7810A59464D4BD915B3225471FF32F8B4CEC67D09BBBC90C67326AB264B96007`
SHA384 | `2BF3F6272E00524B9A3562308CE1E8E2B1A5562961AB373E36D6AB26DE58E5574867CF30E3A741D664B48F4A3A2B4B6D`
SHA512 | `6716C5C1BFC7CC2D4F6298F15F93116C08691AAE94358E499B2CF1EBB05171AE564D3FF168C28B2D69E07E7D4A6DBBCD6FD227900F604F8213D126E039801006`
SSDEEP | `768:nFh9FLaBw3r06I4y6XlnLAsoUq6iomo2TjMDmOtHplMcJc2mJHfwNAdAk:T8AJrBtBUomHjMDmOvlMcZ8HfwCdAk`

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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\lodctr.exe](lodctr.exe-E97FE5FF0994B1C2DDE3B8F2456AEBFC.md) | 74


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

To save the current performance registry settings and explanatory text to file *perf backup1.txt*, type:

```
lodctr /s:perf backup1.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


