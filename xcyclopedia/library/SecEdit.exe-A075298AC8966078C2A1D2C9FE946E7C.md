---
title: SecEdit.exe | Windows Security Configuration Editor Command Tool
---

# SecEdit.exe 

* File Path: `C:\windows\SysWOW64\SecEdit.exe`
* Description: Windows Security Configuration Editor Command Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A075298AC8966078C2A1D2C9FE946E7C`
SHA1 | `77546D98280BF8B28942ED334C6132018DD98D6C`
SHA256 | `14376DDD07CF8DF48803A3C0E606A66F6250BBE56E6FD99E83553ED617FFFED8`
SHA384 | `DBD7B7AA6ABBD8CC9006F7B799EF80E440CAC01ED7050B70DF7760C77F15F6EA9DB9A11CDF5135F2A748D07DD4CFDBCF`
SHA512 | `BD25DF7B82922F20A050C7829252D302B1DC74BA5583A997EF55277B52AEF2217BA0EB0F182452212D3558286D6BC9C692F61F3F06396FDD77D7C49672133EE4`
SSDEEP | `384:ZaqZ0IEi2/3IIOhnmQqeokOXc/bEi0cv4bWezHiW/aXq0lDf2Bh7/oSXkoQfwXyk:Z5OEmUokTDEiBv4hsJqT7/pXkuZ`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\SecEdit.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: SeCEdit
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-093D5982A0E3797E6B114562541A93C8.md) | 33
[C:\WINDOWS\system32\SecEdit.exe](SecEdit.exe-6BBF766473872B90B89DA1F1578FE075.md) | 32
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-6DC1F5DAF217A4ED53794EE6E247F3E0.md) | 36
[C:\windows\system32\SecEdit.exe](SecEdit.exe-DE074ECCF61F37B1C3259AC2209A07EF.md) | 44
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-FE961D8056062E047BCFBD77EBD431B7.md) | 38
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-2C1D80EE80F12EF1033F8FA1E1996276.md) | 49
[C:\WINDOWS\SysWOW64\SecEdit.exe](SecEdit.exe-9DD2FA8EA70DA3B507F810D67EB5D46B.md) | 38
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-B1FA162422034FB5E52499D0198F96B4.md) | 38
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-BFC13856291E4B804D33BBAEFC8CB3B5.md) | 47


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## secedit



Configures and analyzes system security by comparing your current configuration to specified security templates.

### Syntax

```
secedit
[/analyze /db <database file name> /cfg <configuration file name> [/overwrite] /log <log file name> [/quiet]]
[/configure /db <database file name> [/cfg <configuration filename>] [/overwrite] [/areas [securitypolicy | group_mgmt | user_rights | regkeys | filestore | services]] [/log <log file name>] [/quiet]]
[/export /db <database file name> [/mergedpolicy] /cfg <configuration file name> [/areas [securitypolicy | group_mgmt | user_rights | regkeys | filestore | services]] [/log <log file name>]]
[/generaterollback /db <database file name> /cfg <configuration file name> /rbk <rollback file name> [/log <log file name>] [/quiet]]
[/import /db <database file name> /cfg <configuration file name> [/overwrite] [/areas [securitypolicy | group_mgmt | user_rights | regkeys | filestore | services]] [/log <log file name>] [/quiet]]
[/validate <configuration file name>]
```

##### Parameters

|Parameter|Description|
|---------|-----------|
|[Secedit:analyze](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-analyze.md)|Allows you to analyze current systems settings against baseline settings that are stored in a database.  The analysis results are stored in a separate area of the database and can be viewed in the Security Configuration and Analysis snap-in.|
|[Secedit:configure](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-configure.md)|Allows you to configure a system with security settings stored in a database.|
|[Secedit:export](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-export.md)|Allows you to export security settings stored in a database.|
|[Secedit:generaterollback](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-generaterollback.md)|Allows you to generate a rollback template with respect to a configuration template.|
|[Secedit:import](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-import.md)|Allows you to import a security template into a database so that the settings specified in the template can be applied to a system or analyzed against a system.|
|[Secedit:validate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-validate.md)|Allows you to validate the syntax of a security template.|

### Remarks

For all filenames, the current directory is used if no path is specified.

When a security template is created using the Security Template snap-in and the Security Configuration and Analysis snap-in is run, the following files are created:


|           File           |                                                                                                                                                                                                                                                               Description                                                                                                                                                                                                                                                                |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        Scesrv.log        |                                                                                                                             **Location**: %windir%\security\logs</br>**Created by**: operating system</br>**File type**: text</br>**Refresh rate**: Overwritten when secedit /analyze, /configure, /export or /import are run.</br>**Content**: Contains the results of the analysis grouped by policy type.                                                                                                                             |
| *User-selected name*.sdb |                                                                                    **Location**: %windir%\*user account<em>\Documents\Security\Database</br></em>*Created by*<em>: running the Security Configuration and Analysis snap-in</br></em>*File type*<em>: proprietary</br></em>*Refresh rate*<em>: Updated whenever a new security template is created.</br></em>*Content*\*: Local security policies and user-created security templates.                                                                                    |
| *User-selected name*.log | **Location**: User-defined but defaults to %windir%\*user account<em>\Documents\Security\Logs</br></em>*Created by*<em>: Running the /analyze and /configure subcommands (or using the Security Configuration and Analysis snap-in)</br></em>*File type*<em>: text</br></em>*Refresh rate*<em>: Running the /analyze and /configure subcommands (or using the Security Configuration and Analysis snap-in); overwritten.</br></em>*Content*\*:</br>1.  Log file name</br>2.  Date and time</br>3.  Results of analysis or investigation. |
| *User-selected name*.inf |                                                                                     **Location**: %windir%\*user account<em>\Documents\Security\Templates</br></em>*Created by*<em>: running the Security Template snap-in</br></em>*File type*<em>: text</br></em>*Refresh rate*<em>: each time the security template is updated</br></em>*Content*\*: Contains the set up information for the template for each policy selected using the snap-in.                                                                                     |

> [!NOTE]
> The Microsoft Management Console (MMC) and the Security Configuration and Analysis snap-in are not available on Server Core.

### Additional References

For examples of how this command can be used, see the examples section in any of the subcommand files.
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


