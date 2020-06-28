---
title: sdbinst.exe | Application Compatibility Database Installer
---

# sdbinst.exe 

* File Path: `C:\Windows\system32\sdbinst.exe`
* Description: Application Compatibility Database Installer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0C8810CCBAF3750C08BD2CCA5DB3284C`
SHA1 | `5B96AFECE5DC243402CE9C88E14EB5E6154C726D`
SHA256 | `A64EBFEAA892EE807F2C3FE39E5A396D7129A78FA3CC358E93DFDD6E0BFEBFD3`
SHA384 | `5F87F7CAB8D4A50CDBD1C342ADB4A349136D197DF588E09F8093C5F48F398609CFE02DA371ECFBE97921BA2403CE0CC1`
SHA512 | `82DC3158E3AF131C226ED2B245A165207BFF31E4EA1F27621CA89666C9F69C1BDE68413DE1A538DF60A19B569B685995F6FC860CB3C5A9E6FF23C6CC1E383517`
SSDEEP | `384:QbwRvEwCKgGHJ6bgtYhpRkZE6SFZw7i/EpzUTQOy2BcFL1TWcgW:mwRJpQgtyIqACQOy2BcFL1D`

## Runtime Data

### Usage (stdout):
```Batchfile
Error: Invalid switch -help.
Usage: C:\Windows\system32\sdbinst.exe [-?] [-q] [-u] [-g] [-p] [-n[:WIN32|WIN64]] myfile.sdb | {guid} | "name"

    -? - print this help text.
    -p - Allow SDBs containing patches.
    -q - Quiet mode: prompts are auto-accepted.
    -u - Uninstall.
    -g {guid} - GUID of file (uninstall only).
    -n "name" - Internal name of file (uninstall only).

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

* Original Filename: sdbinst.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sdbinst.exe` being misused. While `sdbinst.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `title: Possible Shim Database Persistence via sdbinst.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `description: Detects installation of a new shim using sdbinst.exe. A shim can be used to load malicious DLLs into applications.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `            - '*\sdbinst.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | A list of all shims currently installed by the default Windows installer (sdbinst.exe) is kept in: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe -u #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


