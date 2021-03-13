---
title: SecEdit.exe | Windows Security Configuration Editor Command Tool
excerpt: What is SecEdit.exe?
---

# SecEdit.exe 

* File Path: `C:\Windows\system32\SecEdit.exe`
* Description: Windows Security Configuration Editor Command Tool

## Hashes

Type | Hash
-- | --
MD5 | `6DC1F5DAF217A4ED53794EE6E247F3E0`
SHA1 | `6EA835178F64FBCAA2F045AEAC6A5C53E16585F0`
SHA256 | `512A82B381339F4F5772B3669E341C40C8F27474152AFD41B5412D8A5D341401`
SHA384 | `BA1FEF3F842F08BB2DF0405A030CF6DC57042599E1C1816AAC30A4B2BD465E3016419B5699BAF2B9EAA3BBC992F4783E`
SHA512 | `FD27C1DC8E418EC76F78FE0782C6CDC95EFC0D7263C9888AF66E600D2B5C8E1D7B0D8F2EB12D372F5D5E1AFD8C879D9AF438D10F4C7DFC4A21858894715901F8`
SSDEEP | `768:SiTMlU8uU6P1X33GCqMT3jhXl2M9JqT7/pXk:Oy805mC51Xl2Ma`

## Runtime Data

### Usage (stdout):
```cmhg

The syntax of this command is:

secedit [/configure | /analyze | /import | /export | /validate | /generaterollback]

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SeCEdit
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-093D5982A0E3797E6B114562541A93C8.md) | 35
[C:\WINDOWS\system32\SecEdit.exe](SecEdit.exe-6BBF766473872B90B89DA1F1578FE075.md) | 30
[C:\windows\system32\SecEdit.exe](SecEdit.exe-DE074ECCF61F37B1C3259AC2209A07EF.md) | 36
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-FE961D8056062E047BCFBD77EBD431B7.md) | 36
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-2C1D80EE80F12EF1033F8FA1E1996276.md) | 44
[C:\WINDOWS\SysWOW64\SecEdit.exe](SecEdit.exe-9DD2FA8EA70DA3B507F810D67EB5D46B.md) | 33
[C:\windows\SysWOW64\SecEdit.exe](SecEdit.exe-A075298AC8966078C2A1D2C9FE946E7C.md) | 36
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-B1FA162422034FB5E52499D0198F96B4.md) | 33
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-BFC13856291E4B804D33BBAEFC8CB3B5.md) | 35


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



MIT License. Copyright (c) 2020-2021 Strontic.


