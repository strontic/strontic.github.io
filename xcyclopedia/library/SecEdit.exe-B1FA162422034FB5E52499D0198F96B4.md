---
title: SecEdit.exe | Windows Security Configuration Editor Command Tool
excerpt: What is SecEdit.exe?
---

# SecEdit.exe 

* File Path: `C:\Windows\SysWOW64\SecEdit.exe`
* Description: Windows Security Configuration Editor Command Tool

## Hashes

Type | Hash
-- | --
MD5 | `B1FA162422034FB5E52499D0198F96B4`
SHA1 | `161CEC4D2B3FDD3A804AB9B8DA2B1C2B005A68AF`
SHA256 | `343E8924EA917F83DED38FFF89675A233011D82B2ABA9D4A9675C24A039F5BE5`
SHA384 | `0ADD4B725C05F6FE7F32E972DBCA09F72F415EF1F70E68D10B10F48A232D2867B947BD14D61CE67CD49F88C5D767F3F3`
SHA512 | `1DAA11B669CA33ABA0077FD1C2ED7CF5B2F43FA44A72DDC6E57FF474D84F1F0C55CB5958A87A76514630521B2F5AC05F91CE7F35C75A05B961C136E343B64B03`
SSDEEP | `768:jhvDE20EyZuhDQzXgPGJ4uJqT7/pXkBEz:tg20Ez0zwPGJ4dgE`

## Runtime Data

### Usage (stdout):
```cmhg

The syntax of this command is:

secedit [/configure | /analyze | /import | /export | /validate | /generaterollback]

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\SecEdit.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SeCEdit
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-093D5982A0E3797E6B114562541A93C8.md) | 40
[C:\WINDOWS\system32\SecEdit.exe](SecEdit.exe-6BBF766473872B90B89DA1F1578FE075.md) | 35
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-6DC1F5DAF217A4ED53794EE6E247F3E0.md) | 33
[C:\windows\system32\SecEdit.exe](SecEdit.exe-DE074ECCF61F37B1C3259AC2209A07EF.md) | 33
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-FE961D8056062E047BCFBD77EBD431B7.md) | 40
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-2C1D80EE80F12EF1033F8FA1E1996276.md) | 36
[C:\WINDOWS\SysWOW64\SecEdit.exe](SecEdit.exe-9DD2FA8EA70DA3B507F810D67EB5D46B.md) | 54
[C:\windows\SysWOW64\SecEdit.exe](SecEdit.exe-A075298AC8966078C2A1D2C9FE946E7C.md) | 38
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


