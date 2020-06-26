---
title: lodctr.exe | Load PerfMon Counters
---

# lodctr.exe 

* File Path: `C:\WINDOWS\system32\lodctr.exe`
* Description: Load PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E97FE5FF0994B1C2DDE3B8F2456AEBFC`
SHA1 | `E98B29513DEE1ADA5FAD6D4E953D2E60D6D195B3`
SHA256 | `AF64080AAA7F5B9841828DDD6AFCF78E03980445707C77917A20E5DA7D407E9E`
SHA384 | `F10F9D50D66ECE39B549FA605315FE7F319DFC109838B79A571475A132BECA791587FFC5265E0C8F7D8F3892E325A846`
SHA512 | `9B03F9052B59A168B4EA45EB17DDCB5837AED9F17F3F262724ACB626EA8902B59E517BE670E693018C76FD220DDD97C8405725F357983920400116739E0AEAC7`
SSDEEP | `768:PFh9FLaBm3z0uI4y6XlnFAsoKq6iomo2TIMOm7tHplMcJr2HJHzwjvHlk:L8q1rBX3UomHIMOm7vlMc0pHzwjHlk`

## Runtime Data

### Usage (stdout):
```Batchfile

 
LODCTR 
       Updates registry values related to performance counters. 
Usage: 
       LODCTR <INI-filename> 
             Installs counter text strings. INI-filename is the name of the 
             initialization file that contains the counter name definitions 
             and explain text for an extensible counter DLL.

       LODCTR /C:<filename> 
             Upgrades counter text strings using <filename>

       LODCTR /H:<filename> 
             Upgrades help text strings using <filename>

       LODCTR /L:<LangID> 
             Specifies the language for the /C and /H commands

       LODCTR /S:<Backup-filename> 
             Saves the current perf registry strings and info to 
             <Backup-filename>

       LODCTR /R 
             Rebuilds perf registry from scratch based on current registry 
             settings and backup INI files.

       LODCTR /R:<filename> 
             Restores perf registry strings & info using <filename>

       LODCTR /T:<service-name> 
             Sets the specified performance counter provider as trusted.

       LODCTR /Q 
             Displays performance counter provider information.

       LODCTR /Q:<service-name> 
             Displays performance counter provider information for a 
             specific provider.

       LODCTR /E:<service-name> 
             Enables the performance counter provider.

       LODCTR /D:<service-name> 
             Disables the performance counter provider.

       LODCTR /M:<Counter-Manifest> [<Installation-Path>]
             Installs a v2.0 performance counter provider using the specified 
             XML manifest. 

             The installation requires a full path to the DLL containing the 
             performance counter resources (localized  strings). The path 
             to the DLL will be determined as follows:

             If the applicationIdentity attribute in the manifest is a full 
             path, that will be used.

             Otherwise, if <Installation-Path> is provided and is a full 
             path, that will be used.

             Otherwise, if <Counter-Manifest> is a full path, the directory 
             from <Counter-Manifest> will be combined with the DLL name from 
             the applicationIdentity attribute in the manifest.

             Otherwise, the current directory will be combined with the DLL 
             name from the applicationIdentity attribute in the manifest.

Note: Any arguments with spaces in the names must be enclosed within double 
quotation marks.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


