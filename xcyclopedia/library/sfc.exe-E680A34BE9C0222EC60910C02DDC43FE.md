---
title: sfc.exe | System Integrity Check and Repair
excerpt: What is sfc.exe?
---

# sfc.exe 

* File Path: `C:\windows\system32\sfc.exe`
* Description: System Integrity Check and Repair

## Hashes

Type | Hash
-- | --
MD5 | `E680A34BE9C0222EC60910C02DDC43FE`
SHA1 | `C5FC211EE541A6B0C190A25EC87BAA3E911D9B5D`
SHA256 | `95D582C79421497C848D8406757F18ACF4E8CC690D6FB5096CDEDAD4DE6DB660`
SHA384 | `474AAA0696CE1ACC70095DB3A26BEAA8765C2489AB81B9DB06132A5D8FFF41C18B98F8EBA2192D55D3870B07B9F5A99F`
SHA512 | `1338DF7866C836D8091B1521866FA919DA3E6DE03631FC001F980F4DC517CE83354CF95F291D11DE252B23DD9F961BDA1505124C158F840FAFF891E8B5570A63`
SSDEEP | `768:8pTRZd8QEYVx+Dlu2HICbxlCNtsFiXrf9n+GKyHkXi3FNzq+2qBWRm2cbpVUsx9:IjdLP+Dl9HhxcZbFn+GKisqFNZBWMXfz`

## Signature

* Status: The file C:\windows\system32\sfc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sfc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `sfc.exe` being misused. While `sfc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s4 = "\\sfc.exe" fullword ascii /* score: '11.005' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## sfc

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Scans and verifies the integrity of all protected system files and replaces incorrect versions with correct versions. If this command discovers that a protected file has been overwritten, it retrieves the correct version of the file from the **systemroot\system32\dllcache** folder, and then replaces the incorrect file.

> [!IMPORTANT]
> You must be logged on as a member of the Administrators group to run this command.

### Syntax

```
sfc [/scannow] [/verifyonly] [/scanfile=<file>] [/verifyfile=<file>] [/offwindir=<offline windows directory> /offbootdir=<offline boot directory>]
```

#### Parameters

| Parameter | Description |
|--|--|
| /scannow | Scans the integrity of all protected system files and repairs files with problems when possible. |
| /verifyonly | Scans the integrity of all protected system files, without performing repairs. |
| /scanfile `<file>` | Scans the integrity of the specified file (full path and filename) and attempts to repair any problems if they're detected. |
| /verifyfile `<file>` | Verifies the integrity of the specified file (full path and filename), without performing repairs. |
| /offwindir `<offline windows directory>` | Specifies the location of the offline windows directory, for offline repair. |
| /offbootdir `<offline boot directory>` | Specifies the location of the offline boot directory for offline repair. |
| /? | Displays help at the command prompt. |

### Examples

To verify the *kernel32.dll file*, type:

```
sfc /verifyfile=c:\windows\system32\kernel32.dll
```

To set up the offline repair of the *kernel32.dll* file with an offline boot directory set to *D:\* and an offline windows directory set to *D:\windows*, type:

```
sfc /scanfile=D:\windows\system32\kernel32.dll /offbootdir=D:\ /offwindir=d:\windows
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


