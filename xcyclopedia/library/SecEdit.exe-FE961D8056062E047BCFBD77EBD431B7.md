---
title: SecEdit.exe | Windows Security Configuration Editor Command Tool
---

# SecEdit.exe 

* File Path: `C:\Windows\system32\SecEdit.exe`
* Description: Windows Security Configuration Editor Command Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FE961D8056062E047BCFBD77EBD431B7`
SHA1 | `2CD7718827C793F8CA53C9FE0CC11D09E450EA67`
SHA256 | `58348E21FB9AE1582E68AA07BF21F87D58DB03FE12123B0DF5BFB3A7E168DB26`
SHA384 | `FA57EEE9D6F92DCAD9C55C6B62ED419AB2908222C94F94AE7AC058B5F76B479F1A58AB23BC5BD7FA5A185F452E643E31`
SHA512 | `C4EE99BA9AD4E3B725404E564628196A0F68DE0C46D267C29FB33007C850A9A79875D007AE12C946E4BA34398B29183327438DC63A23D3F97F8D0702C32B142A`
SSDEEP | `768:TjqyEE2/b/6zzHDn82pvU14B+uKGWzdJqT7/pXk:NEE2D/6zzjvUmhKGWz6`

## Runtime Data

### Usage (stdout):
```Batchfile

The syntax of this command is:

secedit [/configure | /analyze | /import | /export | /validate | /generaterollback]

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

* Original Filename: SeCEdit
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\SecEdit.exe](SecEdit.exe-6BBF766473872B90B89DA1F1578FE075.md) | 35
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-6DC1F5DAF217A4ED53794EE6E247F3E0.md) | 36
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-2C1D80EE80F12EF1033F8FA1E1996276.md) | 36
[C:\WINDOWS\SysWOW64\SecEdit.exe](SecEdit.exe-9DD2FA8EA70DA3B507F810D67EB5D46B.md) | 38
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-BFC13856291E4B804D33BBAEFC8CB3B5.md) | 41


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


