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
MD5 | `BFC13856291E4B804D33BBAEFC8CB3B5`
SHA1 | `C6DFD5A7AEC5C4BB068C2FD4E5A4F4B17A65EA7A`
SHA256 | `56CB815F0FDA92C4658296692E4F70DEE557137528482FE7A834296BFDB710C0`
SHA384 | `D1B6025BD34255297627235485CE4FABDC69AFBFAAC13EE7BA329168245315A3016F612B14D1DFF4FA8B982BA9A1CF9E`
SHA512 | `F6E169D040CD8FA6B4FB52A88255D1525B58685A55669B7487499A05D4FB21708DBCEC3C21CA4A1AA5B7AC94CADC91E8B28C2E347821723505C6242D06CB06CA`
SSDEEP | `384:xkqy2KUDuQAi1KVf8JWN00KIPyeBQekXMkPGWDWQzHiWeaXq0lDf2Bh7/oSXkoQ3:xr3KHV0JWNbHyiQzXpPGW7dJqT7/pXk`
IMP | `615449A6A25801F47AE0D7578EB950B4`
PESHA1 | `575CDB3E7EA92EFD24452C53759503B6E0DD9FDC`
PE256 | `0A546395B921D0E93DA026D04B4E43822DD1FAD5FD09C5CD6385DF69CDE59F8F`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/56cb815f0fda92c4658296692e4f70dee557137528482fe7a834296bfdb710c0/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-093D5982A0E3797E6B114562541A93C8.md) | 40
[C:\WINDOWS\system32\SecEdit.exe](SecEdit.exe-6BBF766473872B90B89DA1F1578FE075.md) | 38
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-6DC1F5DAF217A4ED53794EE6E247F3E0.md) | 35
[C:\windows\system32\SecEdit.exe](SecEdit.exe-DE074ECCF61F37B1C3259AC2209A07EF.md) | 33
[C:\Windows\system32\SecEdit.exe](SecEdit.exe-FE961D8056062E047BCFBD77EBD431B7.md) | 41
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-2C1D80EE80F12EF1033F8FA1E1996276.md) | 49
[C:\WINDOWS\SysWOW64\SecEdit.exe](SecEdit.exe-9DD2FA8EA70DA3B507F810D67EB5D46B.md) | 52
[C:\windows\SysWOW64\SecEdit.exe](SecEdit.exe-A075298AC8966078C2A1D2C9FE946E7C.md) | 47
[C:\Windows\SysWOW64\SecEdit.exe](SecEdit.exe-B1FA162422034FB5E52499D0198F96B4.md) | 47


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


