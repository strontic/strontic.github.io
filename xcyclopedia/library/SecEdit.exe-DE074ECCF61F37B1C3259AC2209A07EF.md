---
title: SecEdit.exe | Windows Security Configuration Editor Command Tool
---

# SecEdit.exe 

* File Path: `C:\windows\system32\SecEdit.exe`
* Description: Windows Security Configuration Editor Command Tool

## Hashes

Type | Hash
-- | --
MD5 | `DE074ECCF61F37B1C3259AC2209A07EF`
SHA1 | `7DC7E37755761EE59974AF5490C5EA7B35C247DF`
SHA256 | `D24642E2194D6F09B886990EAFA0A40803EE53EA3F9D142435B5214291DBA062`
SHA384 | `B4D1D1A52A7D2A6A64E106158CB4A7540BBCC54AB229FB2168963CD06723D16096B79A6A87A3A38CF48E137F09E5359B`
SHA512 | `E185F6F54E5D83D682E4F91189BF491EFD980DBCF5DD6679ECF7D61DC5FE54506ABAB1947A9666A13CBED54C0F026F6646112968449966E86425405536005EF0`
SSDEEP | `768:OaHJU1+UAoZ+xuHToXN33Qx+wBqI1bRvwJsJqT7/pXk:kqoZcuYAx+kqIpRvwJf`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\SecEdit.exe |


## Signature

* Status: The file C:\windows\system32\SecEdit.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-093D5982A0E3797E6B114562541A93C8.md) | 35
[C:\WINDOWS\system32\SecEdit.exe](SecEdit.exe-6BBF766473872B90B89DA1F1578FE075.md) | 30
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-6DC1F5DAF217A4ED53794EE6E247F3E0.md) | 36
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-FE961D8056062E047BCFBD77EBD431B7.md) | 33
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-2C1D80EE80F12EF1033F8FA1E1996276.md) | 36
[C:\WINDOWS\SysWOW64\SecEdit.exe](SecEdit.exe-9DD2FA8EA70DA3B507F810D67EB5D46B.md) | 30
[C:\windows\SysWOW64\SecEdit.exe](SecEdit.exe-A075298AC8966078C2A1D2C9FE946E7C.md) | 44
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-B1FA162422034FB5E52499D0198F96B4.md) | 33
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-BFC13856291E4B804D33BBAEFC8CB3B5.md) | 33


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


