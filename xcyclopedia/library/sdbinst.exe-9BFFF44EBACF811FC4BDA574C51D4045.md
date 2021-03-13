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
MD5 | `9BFFF44EBACF811FC4BDA574C51D4045`
SHA1 | `3CBB03B75BC92379499B3B24CD8F24CBD85318C1`
SHA256 | `20E69EEA897D3ABFD5CD7DF2FFECD6083961E9231FEB3D4ED1F029315E5FA88D`
SHA384 | `4E59DC33B41BDBD8378C63A3B67B61310883C436AF69A75B5FC24E17CC927E9AAA62210C2F9868750322C0CD96CA381E`
SHA512 | `C809598A094B24A92557FAAB49C67183579DA6398DD166D7B2D5C795F273CFC3A838433EE97AEC2CFA2E783D1C9D128B2255758A00EA152A70CA0F6F1B9B6E5F`
SSDEEP | `384:ZOhy/E2SJPJ4UdeW9A9y6KHSJ/fFpx1RuOQ1sHPrPDE9LWRgW:ZO8eDcW9oKHSl51YEHDPDE9S`
IMP | `DC04DAC563E65A0D0DAE0ACCC2AC61E2`
PESHA1 | `D7B06E4D14E56BCC8F25EB5BF4FA6FD3F6DB3EA9`
PE256 | `B3657C7A860B776B6DBD01DC2789DC891E9BB32F83555052DF79CBB986E13F42`

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
* File Version: 10.0.19041.572 (WinBuild.160101.0800)
* Product Version: 10.0.19041.572
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/20e69eea897d3abfd5cd7df2ffecd6083961e9231feb3d4ed1f029315e5fa88d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\sdbinst.exe](sdbinst.exe-AC31F1CA54B45D2CC5FD0CF44B07EAC2.md) | 86

## Possible Misuse

*The following table contains possible examples of `sdbinst.exe` being misused. While `sdbinst.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `title: Possible Shim Database Persistence via sdbinst.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `description: Detects installation of a new shim using sdbinst.exe. A shim can be used to load malicious DLLs into applications.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `- '*\sdbinst.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | A list of all shims currently installed by the default Windows installer (sdbinst.exe) is kept in: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe -u #{file_path} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


