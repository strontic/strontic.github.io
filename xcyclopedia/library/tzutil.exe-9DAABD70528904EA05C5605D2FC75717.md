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
MD5 | `9DAABD70528904EA05C5605D2FC75717`
SHA1 | `3B4BAB8731706768D412CF75376DA23283EA1602`
SHA256 | `C65E9D883299477C6F26AFC78139038B81D33A03CFED9172410D9FEBE5576C12`
SHA384 | `24DCF30A45BA3F7C4F50AE676D2D2A03614C4D235CEC83B0E8739779235CA788C26128BBD964F5B3E0B4EDE17794907B`
SHA512 | `AC326949F3399CE7CF5EAFB742AB3BF8DF8AA696F6BDCA4BD4946868125A126945F31FC5E054AD9D4AFA08F1892DE99364F7C4D253A395AD103DB2293450053C`
SSDEEP | `768:kEhcXK5+RltDFBkyX29DhPMkQRjprTllDyVO1vTzwSI1YCmoBoD2O:JhcX+Yl3+o2WHuYHwAX2oD2O`
IMP | `2F5915A9C19B98144A69C2036DC4B667`
PESHA1 | `BC652A6687703FB6DAEAA673A8B7E5BFC631A049`
PE256 | `F8D8CE39C78321FA3A1FC23C465A7DAEA4C1F87D962728C7EB245CA32CE66B25`

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
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\tzutil.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tzutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/c65e9d883299477c6f26afc78139038b81d33a03cfed9172410d9febe5576c12/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\CertEnrollCtrl.exe](CertEnrollCtrl.exe-021F0494762A3060149B29038373347B.md) | 36
[C:\Windows\system32\CertEnrollCtrl.exe](CertEnrollCtrl.exe-D9DE355599A2CD57600B1C4932D12F3A.md) | 33
[C:\Windows\system32\expand.exe](expand.exe-7395D1ACEAC1FD7790DD59F12DFCDEFB.md) | 40
[C:\Windows\system32\tzutil.exe](tzutil.exe-F152E16FC4FE1EDF606D9DFAD92C5242.md) | 38


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


