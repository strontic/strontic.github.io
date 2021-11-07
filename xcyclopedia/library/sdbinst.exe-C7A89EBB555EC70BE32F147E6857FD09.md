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
MD5 | `C7A89EBB555EC70BE32F147E6857FD09`
SHA1 | `D6538B83132161AD07E9B74B84CE70FFB6542DDF`
SHA256 | `A4DFDCBA5A7F55AF325F8DEB61F35FC98EA70924BB94C1B0FBAEF815BA8026DE`
SHA384 | `9CCC5A4B582A090B17DD2046777B6C35417CB8C2ABF9C469424A263AEA59D9591F31B77A683A7B75CCA7C13F4324E3FA`
SHA512 | `715448FD67E38CC61ECC5CB33D604B1B56029C384FD93670EED19A49D31ECC3775DC2E2D02C05EC6BCE2B7D82AF8AEA4986B9B1F629E4E98B0468479F012C014`
SSDEEP | `384:7bwRvEgNKgGXZ/bgtIhaRkZE6SFZKhi/ECzdZl99y2Bc7zFMWYgW:HwRCJDgtChqmKdZl99y2Bc7zFe`
IMP | `5D01C40092C3C1075F7A8335CD70663B`
PESHA1 | `8E2E78E5677C99656CFD8385BF6B7563DAE4324D`
PE256 | `2E700BB78D54E1DACB58892BAB490946A86F0B13229AF9C1AD20EC000A0ADEF9`

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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a4dfdcba5a7f55af325f8deb61f35fc98ea70924bb94c1b0fbaef815ba8026de/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdbinst.exe](sdbinst.exe-0C8810CCBAF3750C08BD2CCA5DB3284C.md) | 63
[C:\Windows\system32\sdbinst.exe](sdbinst.exe-111F6F0708DA82681BE2B1B25B25BED3.md) | 88

## Possible Misuse

*The following table contains possible examples of `sdbinst.exe` being misused. While `sdbinst.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `title: Possible Shim Database Persistence via sdbinst.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `description: Detects installation of a new shim using sdbinst.exe. A shim can be used to load malicious DLLs into applications.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `Image\|endswith: '\sdbinst.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | A list of all shims currently installed by the default Windows installer (sdbinst.exe) is kept in: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe -u #{file_path} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


