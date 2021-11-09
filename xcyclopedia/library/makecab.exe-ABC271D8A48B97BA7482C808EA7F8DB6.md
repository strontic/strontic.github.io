---
title: makecab.exe | Microsoft Cabinet Maker
excerpt: What is makecab.exe?
---

# makecab.exe 

* File Path: `C:\WINDOWS\SysWOW64\makecab.exe`
* Description: Microsoft Cabinet Maker

## Hashes

Type | Hash
-- | --
MD5 | `ABC271D8A48B97BA7482C808EA7F8DB6`
SHA1 | `54037082692F7DFCCC3E51998929F1F23578BDF6`
SHA256 | `C02D0FDC0D2694EFE264D539345BFEE621EA173CBF4BE29E2A1D3EA282B06E69`
SHA384 | `6EDBC41A1DA918DB850A5F0D42557F42627B679A66C00FB346EBB095CF07BB21BF4F6C9C2D686BB6D864A483B1147D25`
SHA512 | `C192D63F1188B0AB3044ACF3B0A6A7717765BE3A0C0F24E42809DA4961A27AABD5E21F6E10135FCB9FA7F08597D20B103BDF0F72BE441FB1243C6A96B9058A25`
SSDEEP | `1536:iHET5V4c1lygHC6I7EXjbEEpT6gJBcg66vEgPMLCbhnGQocVKWozLHH8pdn5jCEW:sET5ac1lygHC6I7EXjbEEpT1Bcg66H0l`
IMP | `DB419917F8DBA7D951EB3BCBFC2572AA`
PESHA1 | `C1CAD6DDB4949C5A2599EB49165D3ECBBFA6C198`
PE256 | `750482750C50755302CC7FA5BAD49D8916EFF55FBA871745AA3CCD7DE3073CF9`

## Runtime Data

### Usage (stdout):
```cmhg
Cabinet Maker - Lossless Data Compression Tool

MAKECAB [/V[n]] [/D var=value ...] [/L dir] source [destination]
MAKECAB [/V[n]] [/D var=value ...] /F directive_file [...]

  source         File to compress.
  destination    File name to give compressed file.  If omitted, the
                 last character of the source file name is replaced
                 with an underscore (_) and used as the destination.
  /F directives  A file with MakeCAB directives (may be repeated). Refer to
                 Microsoft Cabinet SDK for information on directive_file.
  /D var=value   Defines variable with specified value.
  /L dir         Location to place destination (default is current directory).
  /V[n]          Verbosity level (1..3).

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\makecab.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: makecab.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c02d0fdc0d2694efe264d539345bfee621ea173cbf4be29e2a1d3ea282b06e69/detection


## Possible Misuse

*The following table contains possible examples of `makecab.exe` being misused. While `makecab.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\makecab.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_alternate_data_streams.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_alternate_data_streams.yml) | `- 'makecab '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_hafnium.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_hafnium.yml) | `Image\|endswith: '\makecab.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `Name: Makecab.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Command: makecab c:\ADS\autoruns.exe c:\ADS\cabtest.txt:autoruns.cab`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Command: makecab \\webdavserver\webdav\file.exe C:\Folder\file.txt:file.cab`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Command: makecab \\webdavserver\webdav\file.exe C:\Folder\file.cab`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Path: C:\Windows\System32\makecab.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Path: C:\Windows\SysWOW64\makecab.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- IOC: Makecab getting files from Internet`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- IOC: Makecab storing data into alternate data streams`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | makecab #{path}\autoruns.exe #{path}\cabtest.txt:autoruns.cab | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## makecab

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Package existing files into a cabinet (.cab) file.


> [!NOTE]
> This command is the same as the [diantz command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diantz.md).

### Syntax

```
makecab [/v[n]] [/d var=<value> ...] [/l <dir>] <source> [<destination>]
makecab [/v[<n>]] [/d var=<value> ...] /f <directives_file> [...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<source>` | File to compress. |
| `<destination>` | File name to give compressed file. If omitted, the last character of the source file name is replaced with an underscore (_) and used as the destination. |
| /f `<directives_file>` | A file with **makecab** directives (may be repeated). |
| /d var=`<value>` | Defines variable with specified value. |
| /l `<dir>` | Location to place destination (default is current directory). |
| /v[`<n>`] | Set debugging verbosity level (0=none,...,3=full). |
| /? | Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [diantz command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diantz.md)

- [Microsoft Cabinet format](/previous-versions/bb417343(v=msdn.10))

---



MIT License. Copyright (c) 2020-2021 Strontic.


