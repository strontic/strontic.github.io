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
MD5 | `E2A285FBF3BEB083A8A1336C28197195`
SHA1 | `B0C1A838A6D4D0862289B4A2FB4DA375BE389077`
SHA256 | `DA67C992ECD1330FE32C2FF3A4D6E77CE6A5A51927FBDBB3C7E8FFFDC32877EF`
SHA384 | `AB2861C319B3E7A5211BB86BEF74395D515933A5157EEFABE731B2D9376197D8824B3A1D90C46FDC812C72506DA13E28`
SHA512 | `58A8669E5571911390EB1A1C6FC01DAEE32C9E48E9DA43A75F70F0CA166338ABAEC6685A172E9677121DA1E5E62B21C59AB110B71C361B644BA59F79127996C7`
SSDEEP | `768:bfpKHTiPgnw1VzDtG+6Jc1Ra5yg8U/jGwWyu9:gHOonw3DtsJcLa5ygrrJWyu9`

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

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tzutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\CertEnrollCtrl.exe](CertEnrollCtrl.exe-56808A6D43D550A1999E1D729BE77C0F.md) | 27
[C:\Windows\SysWOW64\CertEnrollCtrl.exe](CertEnrollCtrl.exe-E24D3DC4B70286411ED6A972A0CA4900.md) | 32
[C:\Windows\SysWOW64\expand.exe](expand.exe-B245CEEC35156CB95CAB80865F1A6D56.md) | 25
[C:\Windows\SysWOW64\expand.exe](expand.exe-C5A28F44F47524452C188ED74E754095.md) | 38
[C:\Windows\SysWOW64\tzutil.exe](tzutil.exe-DFED5044997A60C7C8909E3FC755240F.md) | 35


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tzutil

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


