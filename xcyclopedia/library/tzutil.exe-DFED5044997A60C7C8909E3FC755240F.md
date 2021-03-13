---
title: tzutil.exe | Windows Time Zone Utility
excerpt: What is tzutil.exe?
---

# tzutil.exe 

* File Path: `C:\Windows\SysWOW64\tzutil.exe`
* Description: Windows Time Zone Utility

## Hashes

Type | Hash
-- | --
MD5 | `DFED5044997A60C7C8909E3FC755240F`
SHA1 | `70FA72BBCE595D53D361BF0EA63C8B9EE332E4A9`
SHA256 | `D0F640BA7DB3906AE5352EEE6989BDE941B51D20FC4A61BBEB83281112B1D28A`
SHA384 | `45EC8D370E99C89CBC44F2C8BEF89E0362257A4BC4658E8DF1D31BDAD39C432E0FC23AAC88E5F17E3900C3B2C7513DCF`
SHA512 | `00AD117B4C838271D0B6CC85AFFA5A233E09DB7B9D581373E2C026FDDC8B034F92B8CDCE4854AEC7309CBD03AF5D7412540DBD350F56BFB29FE042160F4F03D5`
SSDEEP | `768:sD21FKHTiPgnw0EJJvYxcc4DRf3IVBVx8I:si14HOonwlKec4Q7Vx8I`
IMP | `C705BC50B8CCB931FC1CB5042F3DF883`
PESHA1 | `A003A3DFA64C7A590196C20B8ED602FD275D293C`
PE256 | `A6B9E4E009612A4F74C3BA91948ACC27AB249CFF2709222CB05BD823D2D4F74F`

## Runtime Data

### Usage (stdout):
```cmhg
Windows Time Zone Utility

Usage:
TZUTIL </? | /g | /s TimeZoneID[_dstoff] | /l>

Parameters:
    /? Displays usage information.

    /g Displays the current time zone ID.

    /s TimeZoneID[_dstoff]
       Sets the current time zone using the specified time zone ID.
       The _dstoff suffix disables Daylight Saving Time adjustments
       for the time zone (where applicable).

    /l Lists all valid time zone IDs and display names. The output will
       be: 
           <display name>
           <time zone ID>

Examples:
    TZUTIL /g
    TZUTIL /s "Pacific Standard Time"
    TZUTIL /s "Pacific Standard Time_dstoff"

Remarks:
    An exit code of 0 indicates the command completed successfully.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tzutil.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tzutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/d0f640ba7db3906ae5352eee6989bde941b51d20fc4a61bbeb83281112b1d28a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\CertEnrollCtrl.exe](CertEnrollCtrl.exe-56808A6D43D550A1999E1D729BE77C0F.md) | 36
[C:\Windows\SysWOW64\CertEnrollCtrl.exe](CertEnrollCtrl.exe-E24D3DC4B70286411ED6A972A0CA4900.md) | 32
[C:\Windows\SysWOW64\expand.exe](expand.exe-B245CEEC35156CB95CAB80865F1A6D56.md) | 32
[C:\Windows\SysWOW64\expand.exe](expand.exe-C5A28F44F47524452C188ED74E754095.md) | 33
[C:\Windows\SysWOW64\tzutil.exe](tzutil.exe-E2A285FBF3BEB083A8A1336C28197195.md) | 35


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tzutil

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the Windows Time Zone utility.

### Syntax

```
tzutil [/?] [/g] [/s <timezoneID>[_dstoff]] [/l]
```

#### Parameters

| Parameter | Description |
|--|--|
| /g | Displays the current time zone ID. |
| /s `<timezoneID>[_dstoff]` | Sets the current time zone using the specified time zone ID. The **_dstoff** suffix disables Daylight Saving time adjustments for the time zone (where applicable). Your value must be surrounded by quotes. |
| /l | Lists all valid time zone IDs and display names. The output appears as:<ul><li>`<display name>`</li><li>`<time zone ID>`</li></ul> |
| /? | Displays help at the command prompt. |

##### Remarks

An exit code of **0** indicates the command completed successfully.

### Examples

To display the current time zone ID, type:

```
tzutil /g
```

To set the current time zone to Pacific Standard time, type:

```
tzutil /s "Pacific Standard time"
```

To set the current time zone to Pacific Standard time and disable Daylight Saving time adjustments, type:

```
tzutil /s "Pacific Standard time_dstoff"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


