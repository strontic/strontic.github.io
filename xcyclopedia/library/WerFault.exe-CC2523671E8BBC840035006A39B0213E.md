---
title: WerFault.exe | Windows Problem Reporting
excerpt: What is WerFault.exe?
---

# WerFault.exe 

* File Path: `C:\Windows\system32\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `CC2523671E8BBC840035006A39B0213E`
SHA1 | `A357534826805BEF1B5D92E8D6DE3F3A25D0E270`
SHA256 | `05EE1A3CE81C001F5B175B60C35D6A91EE8766DB9A18BCEFA8CE9B4B160182DB`
SHA384 | `25CB9635401BB7880EB3AE70953D0B45E7CB741ABF3B82014F30CD9AC377070774D0D55FF99752B2BEC2A51B78118DB7`
SHA512 | `5C443108C0205C83D360419AC83720C3F369A2FE4F99465250411700E3FF5B5F853A2753EB5231437FC4F5936CF1B7B50B5E8B19A3D2EEF3D20E3CCC7BCD5260`
SSDEEP | `6144:XGz8dLTD3OoG+4ahurV4oAWHxbHozjQZkxkEwQWFL6qJdVdLKl2JRg+6FL1VJyBe:uF46LAWxbHozClQWFddgDFLzc2Hywv`
IMP | `862AFF0B51DFEEABAB0230D4F6D5ADDD`
PESHA1 | `A95360724E56D737FC4C7DEB34F65F1FDDB0FB46`
PE256 | `17D22A16DE63C2E3AE6C64F128AB7ED958FD8AC8B42C701BA94ED88F1B4440BE`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\WerFault.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/05ee1a3ce81c001f5b175b60c35d6a91ee8766db9a18bcefa8ce9b4b160182db/detection/


## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


