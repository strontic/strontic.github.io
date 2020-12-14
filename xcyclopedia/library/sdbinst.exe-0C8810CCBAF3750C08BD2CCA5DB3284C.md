---
title: sdbinst.exe | Application Compatibility Database Installer
excerpt: What is sdbinst.exe?
---

# sdbinst.exe 

* File Path: `C:\Windows\system32\sdbinst.exe`
* Description: Application Compatibility Database Installer

## Hashes

Type | Hash
-- | --
MD5 | `0C8810CCBAF3750C08BD2CCA5DB3284C`
SHA1 | `5B96AFECE5DC243402CE9C88E14EB5E6154C726D`
SHA256 | `A64EBFEAA892EE807F2C3FE39E5A396D7129A78FA3CC358E93DFDD6E0BFEBFD3`
SHA384 | `5F87F7CAB8D4A50CDBD1C342ADB4A349136D197DF588E09F8093C5F48F398609CFE02DA371ECFBE97921BA2403CE0CC1`
SHA512 | `82DC3158E3AF131C226ED2B245A165207BFF31E4EA1F27621CA89666C9F69C1BDE68413DE1A538DF60A19B569B685995F6FC860CB3C5A9E6FF23C6CC1E383517`
SSDEEP | `384:QbwRvEwCKgGHJ6bgtYhpRkZE6SFZw7i/EpzUTQOy2BcFL1TWcgW:mwRJpQgtyIqACQOy2BcFL1D`
IMP | `5D01C40092C3C1075F7A8335CD70663B`
PESHA1 | `F741D3B820DF481EDCADC5BBE8C413F6F3C7A86C`
PE256 | `0EA1F5A7CE8283B719AC2900C77B480DED95C2A241ECE79D00D5782ED848AD09`

## Runtime Data

### Usage (stdout):
```cmhg
Error: Invalid switch --help.
Usage: C:\Windows\system32\sdbinst.exe [-?] [-q] [-u] [-g] [-p] [-n[:WIN32|WIN64]] myfile.sdb | {guid} | "name"

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sdbinst.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdbinst.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a64ebfeaa892ee807f2c3fe39e5a396d7129a78fa3cc358e93dfdd6e0bfebfd3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdbinst.exe](sdbinst.exe-111F6F0708DA82681BE2B1B25B25BED3.md) | 63

## Possible Misuse

*The following table contains possible examples of `sdbinst.exe` being misused. While `sdbinst.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `title: Possible Shim Database Persistence via sdbinst.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `description: Detects installation of a new shim using sdbinst.exe. A shim can be used to load malicious DLLs into applications.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `- '*\sdbinst.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | A list of all shims currently installed by the default Windows installer (sdbinst.exe) is kept in: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe -u #{file_path} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


