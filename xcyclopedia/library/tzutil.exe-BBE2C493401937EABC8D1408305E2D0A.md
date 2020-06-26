---
title: tzutil.exe | Windows Time Zone Utility
---

# tzutil.exe 

* File Path: `C:\WINDOWS\system32\tzutil.exe`
* Description: Windows Time Zone Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `BBE2C493401937EABC8D1408305E2D0A`
SHA1 | `6AA8313AEF33EA25731D3D9C35A75E87C6E54BDF`
SHA256 | `3317945B70147AFC4FEC63E9863022B1D24A74D63E0A85A0758BD15CC8906803`
SHA384 | `150888E32359D02A0825FECD88E6186A84958F8165FD06CD47194BE79BCF5621176ADDB9AC2693784E00A666D709A3D9`
SHA512 | `757B5502A8554D72F4B0CC6DF616582F33F0DE6549DDCB4BE2B544B53197931E574E923BBA1229C388141639A77DAA44C16BFCD32AE46C286B46CBD12946194C`
SSDEEP | `768:v/ufIZh6SUHcrjEYvp7E1SFPuxCOF2oSX2xjprT3lxyVO1vT3w8Y3ss+ms8oP4:3ufIZhxFrjpE1Sc9k2HuYbwV3oP4`

## Runtime Data

### Usage (stdout):
```Batchfile
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

* Original Filename: tzutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tzutil

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the Windows Time Zone utility.

### Syntax
```
tzutil [/?] [/g] [/s <timeZoneID>[_dstoff]] [/l]
```
##### Parameters
|Parameter|Description|
|-------|--------|
|/?|Displays help at the command prompt.|
|/g|Displays the current time zone ID.|
|/s \<timeZoneID>[_dstoff]|Sets the current time zone using the specified time zone ID. The **_dstoff** suffix disables Daylight Saving time adjustments for the time zone (where applicable).|
|/l|lists all valid time zone IDs and display names. The output will be:<p>-   \<display name><br />-   \<time zone ID>|

### Remarks
An exit code of **0** indicates the command completed successfully.

### Examples
To display the current time zone ID, type:
```
tzutil /g
```
To set the current time zone to Pacific Standard time, type:
```
tzutil /s Pacific Standard time
```
To set the current time zone to Pacific Standard time and disable Daylight Saving time adjustments, type:
```
tzutil /s Pacific Standard time_dstoff
```
### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)


---



MIT License. Copyright (c) 2020 Strontic.


