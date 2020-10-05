---
title: SecEdit.exe | Windows Security Configuration Editor Command Tool
excerpt: What is SecEdit.exe?
---

# SecEdit.exe 

* File Path: `C:\windows\SysWOW64\SecEdit.exe`
* Description: Windows Security Configuration Editor Command Tool

## Hashes

Type | Hash
-- | --
MD5 | `A075298AC8966078C2A1D2C9FE946E7C`
SHA1 | `77546D98280BF8B28942ED334C6132018DD98D6C`
SHA256 | `14376DDD07CF8DF48803A3C0E606A66F6250BBE56E6FD99E83553ED617FFFED8`
SHA384 | `DBD7B7AA6ABBD8CC9006F7B799EF80E440CAC01ED7050B70DF7760C77F15F6EA9DB9A11CDF5135F2A748D07DD4CFDBCF`
SHA512 | `BD25DF7B82922F20A050C7829252D302B1DC74BA5583A997EF55277B52AEF2217BA0EB0F182452212D3558286D6BC9C692F61F3F06396FDD77D7C49672133EE4`
SSDEEP | `384:ZaqZ0IEi2/3IIOhnmQqeokOXc/bEi0cv4bWezHiW/aXq0lDf2Bh7/oSXkoQfwXyk:Z5OEmUokTDEiBv4hsJqT7/pXkuZ`

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

## secedit commands

Configures and analyzes system security by comparing your current security configuration against specified security templates.

> [!NOTE]
> The Microsoft Management Console (MMC) and the Security Configuration and Analysis snap-in are not available on Server Core.

### Syntax

```
secedit /analyze
secedit /configure
secedit /export
secedit /generaterollback
secedit /import
secedit /validate
```

#### Parameters

| Parameter | Description |
|--|--|
| [secedit /analyze](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-analyze.md) | Allows you to analyze current systems settings against baseline settings that are stored in a database.  The analysis results are stored in a separate area of the database and can be viewed in the Security Configuration and Analysis snap-in. |
| [secedit /configure](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-configure.md) | Allows you to configure a system with security settings stored in a database. |
| [secedit /export](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-export.md) | Allows you to export security settings stored in a database. |
| [secedit /generaterollback](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-generaterollback.md) | Allows you to generate a rollback template with respect to a configuration template. |
| [secedit /import](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-import.md) | Allows you to import a security template into a database so that the settings specified in the template can be applied to a system or analyzed against a system. |
| [secedit /validate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/secedit-validate.md) | Allows you to validate the syntax of a security template. |

##### Remarks

- If there is no filepath specified, all filenames will default to the current directory.

- Your analysis results are stored in a separate area of the database and can be viewed in the Security Configuration and Analysis snap-in to the MMC.

- If your security templates are created by using the Security Template snap-in, and if you run the Security Configuration and Analysis snap-in against those templates, the following files are created:

    | File | Description |
    |--|--|
    | scesrv.log | <ul><li>**Location:** `%windir%\security\logs`</li><li>**Created by:** Operating system</li><li>**File type:** Text</li><li>**Refresh rate:** Overwritten when `secedit analyze`, `secedit configure`, `secedit export` or `secedit import` is run.</li><li>**Content:** Contains the results of the analysis grouped by policy type.</li></ul> |
    | *user-selected name*.sdb | <ul><li>**Location:** `%windir%\<user account>\Documents\Security\Database`</li><li>**Created by:** Running the Security Configuration and Analysis snap-in</li><li>**File type:** Proprietary</li><li>**Refresh rate:** Updated whenever a new security template is created.</li><li>**Content:** Local security policies and user-created security templates.</li></ul> |
    | *user-selected name*.log | <ul><li>**Location:** User-defined, but defaults to `%windir%\<user account>\Documents\Security\Logs`</li><li>**Created by:** Running the `secedit analyze` or `secedit configure` commands, or by using the Security Configuration and Analysis snap-in.</li><li>**File type:** Text</li><li>**Refresh rate:** Overwritten when `secedit analyze` or `secedit configure` is run, or by using the Security Configuration and Analysis snap-in.</li><li>**Content:** Log file name, date and time, and the results of the analysis or investigation.</li></ul> |
    | *user-selected name*.inf | <ul><li>**Location:** `%windir%\*<user account>\Documents\Security\Templates`</li><li>**Created by:** Running the Security Template snap-in.</li><li>**File type:** Text</li><li>**Refresh rate:** Overwritten each time the security template is updated.</li><li>**Content:** Contains the set up information for the template for each policy selected using the snap-in.</li></ul> |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


