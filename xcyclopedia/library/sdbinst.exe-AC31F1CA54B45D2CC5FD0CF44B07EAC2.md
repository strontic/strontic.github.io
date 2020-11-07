---
title: sdbinst.exe | Application Compatibility Database Installer
excerpt: What is sdbinst.exe?
---

# sdbinst.exe 

* File Path: `C:\Windows\SysWOW64\sdbinst.exe`
* Description: Application Compatibility Database Installer

## Hashes

Type | Hash
-- | --
MD5 | `AC31F1CA54B45D2CC5FD0CF44B07EAC2`
SHA1 | `E1253BDBAF0CA5D8213FEE8A0913C1302C0998A3`
SHA256 | `F26BFC0B4FEF00A7DFF35FAC89139BB96CAE1052BBACF7FE1D858F8917F8B232`
SHA384 | `3BAB9727FB5E788321BC8F2F17FF79FD7EF5E7B5727B1AFA4304A883316A39B87689D8EC210C3DA729461F26E63B79B8`
SHA512 | `791BDEDA308D88B1972D0904295CD94F5ADD85A196C8340491D36CA64C744ECBB06970521F68F3C7D8273FF60EC2D991E8AB43D330C95EF2E8998C613AAEB5FD`
SSDEEP | `384:eOhy/ErSJPJ4UdeW9A9y6KHSJ/fFpx1RuOQ1slFPDE67WcgW:eO1eDcW9oKHSl51YElFPDE67`
IMP | `DC04DAC563E65A0D0DAE0ACCC2AC61E2`
PESHA1 | `2EBBBFCB8E58E72BB84E16C6E64DB1D3722CFD27`
PE256 | `7D8D4711474B27C9094AC27922D9D07409AEB4A16258380AF9BA293115F160E7`

## Runtime Data

### Usage (stdout):
```cmhg
Error: Invalid switch --help.
Usage: C:\Windows\SysWOW64\sdbinst.exe [-?] [-q] [-u] [-g] [-p] [-n[:WIN32|WIN64]] myfile.sdb | {guid} | "name"

    -? - print this help text.
    -p - Allow SDBs containing patches.
    -q - Quiet mode: prompts are auto-accepted.
    -u - Uninstall.
    -g {guid} - GUID of file (uninstall only).
    -n "name" - Internal name of file (uninstall only).

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\sdbinst.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdbinst.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/f26bfc0b4fef00a7dff35fac89139bb96cae1052bbacf7fe1d858f8917f8b232/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\sdbinst.exe](sdbinst.exe-9BFFF44EBACF811FC4BDA574C51D4045.md) | 86

## Possible Misuse

*The following table contains possible examples of `sdbinst.exe` being misused. While `sdbinst.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `title: Possible Shim Database Persistence via sdbinst.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `description: Detects installation of a new shim using sdbinst.exe. A shim can be used to load malicious DLLs into applications.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `- '*\sdbinst.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | A list of all shims currently installed by the default Windows installer (sdbinst.exe) is kept in: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe -u #{file_path} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


