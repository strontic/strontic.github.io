---
title: tzutil.exe | Windows Time Zone Utility
excerpt: What is tzutil.exe?
---

# tzutil.exe 

* File Path: `C:\Windows\system32\tzutil.exe`
* Description: Windows Time Zone Utility

## Hashes

Type | Hash
-- | --
MD5 | `F152E16FC4FE1EDF606D9DFAD92C5242`
SHA1 | `F18018561FE70713083BC2E269D3395A737A0861`
SHA256 | `82DD94761865BE53BA3122E0542BA05D373445B376AFACAF20B6E3AF2B33CE79`
SHA384 | `984F05065462B54596E1F715311259F1AC8D9A02112C5CD25B1E3F7C121DBD53FE2D1CA40E4B57318E9BD4C3A1C6E4DA`
SHA512 | `0DF4988648DD1123E8C83DFD885D75FF2EA4CDE06DAE2ED69B7A4F686079C8855539BC2827142096E48D378D6321AA4120A94DAD6344F21A6D45DFE52529089D`
SSDEEP | `768:Jy3gEqgeQNCkA2Qe75rpcPGqKlLtqljprTllDyVO1vTzwabxFu5TwgtL4:gwEqgJNCkA2Lrpa5fHuYHwREgtL4`

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
[C:\Windows\system32\CertEnrollCtrl.exe](CertEnrollCtrl.exe-021F0494762A3060149B29038373347B.md) | 33
[C:\Windows\system32\CertEnrollCtrl.exe](CertEnrollCtrl.exe-D9DE355599A2CD57600B1C4932D12F3A.md) | 36
[C:\Windows\system32\expand.exe](expand.exe-700328EA375572AA173E72932AAC389E.md) | 32
[C:\Windows\system32\expand.exe](expand.exe-7395D1ACEAC1FD7790DD59F12DFCDEFB.md) | 36
[C:\Windows\system32\tzutil.exe](tzutil.exe-9DAABD70528904EA05C5605D2FC75717.md) | 38


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


