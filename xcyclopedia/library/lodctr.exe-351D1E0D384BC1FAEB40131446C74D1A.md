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
MD5 | `351D1E0D384BC1FAEB40131446C74D1A`
SHA1 | `3DEC174F08F22FACFCB53D4BD8993D0AB9DA5EAE`
SHA256 | `3915BFB4520C2947E3DC9B4BDD4AF56AABDEDA1923B60F17A6E742A2231EA50D`
SHA384 | `286C2BC641F35AA94809F4F19196C76E94387CF4637D412E5291DCA47D9CE75E809206847BE84269943A8277405F8D2D`
SHA512 | `B4EDD7D5050491E0A706F2BD9E56C564E599FBC03ED84D24CE4A36261A99D34B87899791E551FE14C17E35E9AD15A3911410318BC9836C8C273BCA831BD78A8B`
SSDEEP | `768:qJ3ZlM8ZvQ0RrAs8fkk6IrHYUZgMkuwm8VcMDwFZ/hiKMAZnEOw9i:ulM8FFrANHHYUyMku4VKhJB1EOw9i`
IMP | `FDABB1B17742D7066DE0358591144052`
PESHA1 | `2E22CFA2967A876B932A4FDD287FDB2B35F733F0`
PE256 | `4F1377C128E97EC6726D5D2B9C0CCA1DD029D02A26757AC347FD24D3FC58E7DB`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\lodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/3915bfb4520c2947e3dc9b4bdd4af56aabdeda1923b60f17a6e742a2231ea50d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\lodctr.exe](lodctr.exe-CF8FC7C3E40105C13B6294418D1CB670.md) | 35


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



MIT License. Copyright (c) 2020-2021 Strontic.


