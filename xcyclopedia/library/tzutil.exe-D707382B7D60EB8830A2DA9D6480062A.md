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
MD5 | `D707382B7D60EB8830A2DA9D6480062A`
SHA1 | `4C721616200B2CD92D7716981999D94F549732A8`
SHA256 | `BF331CDF306FE1D01A5B4B81B898A268D0D1C8461C4AEDA19D5C67F5FAD981B1`
SHA384 | `416AE7EB5677B7760067892AC4019ADFEC6B26A49FCD57F70667B606A8E2D26DC19F6A28D5EDBC533AF8D54F2510254E`
SHA512 | `3341C6AE65C4604792ED64900BB4E7E713E60148ECB9AAB88C0108F1E6C21AF2311289137C2D5D6F32A1CDDF3157E8B52FDE55FB607719D0D47F64B1A77F2D51`
SSDEEP | `768:r4gjGXBwJDkHlyVm9h8oxpIHskL9sl7R8FNjprT3lxyVO1VTO+Uvxxi8oOWx:kgjG2JDkQYbBpyskLSKBHuiE5oOWx`
IMP | `B4940EAAD48DE4C33FFFA56E15249A7A`
PESHA1 | `C30C6920FD54287234AE20051EF4752F17E0F38F`
PE256 | `43F52E3DED69A9053B30359DA961E55A42CFEAB492DDA173D935A800BD7B8FFE`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tzutil.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tzutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/bf331cdf306fe1d01a5b4b81b898a268d0d1c8461c4aeda19d5c67f5fad981b1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\bootsect.exe](bootsect.exe-4A59BDA770A1683A7BC5A913EA1D74AB.md) | 30
[C:\Windows\system32\DriverStore\FileRepository\tsgenericusbdriver.inf_amd64_6b86bbc412f35fe7\TsUsbGDCoInstaller.dll](TsUsbGDCoInstaller.dll-4D45B865AB970A8A3C1BFEF2EA59C4FF.md) | 40
[C:\Windows\system32\TsUsbGDCoInstaller.dll](TsUsbGDCoInstaller.dll-4D45B865AB970A8A3C1BFEF2EA59C4FF.md) | 40
[C:\WINDOWS\system32\tzutil.exe](tzutil.exe-BBE2C493401937EABC8D1408305E2D0A.md) | 33


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


