---
title: lodctr.exe | Load PerfMon Counters
excerpt: What is lodctr.exe?
---

# lodctr.exe 

* File Path: `C:\WINDOWS\SysWOW64\lodctr.exe`
* Description: Load PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `7B2C32D1B5721AD8EB04D2BBA06A7334`
SHA1 | `AAC7CA84562535D0DE94E7FA106F686C4DEB4732`
SHA256 | `E56D0C81EF4DF6B1C5EE32E65A60A0C692B1C54D60161D1BBAABEDF4A935D908`
SHA384 | `3CAFD70E4765E54E33ADE1262B0B9BDA39DAE3489D7A078222A45055B7256DDC329AE13D79C052D5C415236D780985C5`
SHA512 | `113D4C1EBD83437E7D9CF04666447180D83C4B3DB3D17568BF25CB25FEDB3BBDC7A56C0C6BAEBD870BAB5EC5306E3A37F756ED9540F2E4ED6468F05824B54B07`
SSDEEP | `768:Vm3ZlM8ZQYvowYAYVu/nzrhQ6X9tn5D3oA64LM5M+zRJk:klM8yOowFZnhQ6X9H564LM5Muj`
IMP | `54AA1057D85A21324690DA39AD4929E9`
PESHA1 | `1C32B0106AAA65ABE8EF2ED581D64F56F88E4AA2`
PE256 | `5219C27DFC460C7F4AC2548C6FF5F15F2267CDC1E5D7F2972B7E2061607E3E55`

## Runtime Data

### Usage (stdout):
```cmhg

 
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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\lodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/e56d0c81ef4df6b1c5ee32e65a60a0c692b1c54d60161d1bbaabedf4a935d908/detection



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


