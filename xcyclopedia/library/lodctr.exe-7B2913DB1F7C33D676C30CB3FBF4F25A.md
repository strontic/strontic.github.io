---
title: lodctr.exe | Load PerfMon Counters
---

# lodctr.exe 

* File Path: `C:\windows\SysWOW64\lodctr.exe`
* Description: Load PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7B2913DB1F7C33D676C30CB3FBF4F25A`
SHA1 | `54183893AB5146AFF27F85B55D38382FB38100D7`
SHA256 | `BE3EE03E1829DD4A86AF9037F4D85529ED32D5940AB22E2B7C4C675424CD016B`
SHA384 | `5BF5F613059C2E5795E1F258CB9D28D10638F36A51D1159A78009BA64753F3F1213A2D7AF1528185DB185827FC9B4BE8`
SHA512 | `73B91466CD100AA5B7392044F818EEB5E1B3CE06343FF217B8F28AB617C809058BE06B897BE7B34AF96A6AFEA5D9ADEF27666E2A9970101A54CC08F564610BA8`
SSDEEP | `768:DukbZlM8qG3WJqmR7YDP7Bx/W1HvcGkMowOZONNWUS1ce:JlM85iMDW1HEGkPZgNWUS1c`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\lodctr.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: LODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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

To save the current performance registry settings and explanatory text to file *perf backup1.txt*, type:

```
lodctr /s:perf backup1.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


