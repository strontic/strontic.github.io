---
title: SettingSyncHost.exe | Host Process for Setting Synchronization
excerpt: What is SettingSyncHost.exe?
---

# SettingSyncHost.exe 

* File Path: `C:\Windows\system32\SettingSyncHost.exe`
* Description: Host Process for Setting Synchronization

## Hashes

Type | Hash
-- | --
MD5 | `080B1B825DD5C47B661795FA7AB83C6A`
SHA1 | `556DA7E1928BF4F32A9C5B550141EFC4309E9F49`
SHA256 | `73D8F23A1ACF635A39B2DCB8B37304658F6F84D1090AF961EA031EFAB833D916`
SHA384 | `D4251DA3097702CFA5E62C5130BBA1A0594C6AED273919AC97F590A4530197452885A1445111B833BA8573137233BD23`
SHA512 | `69A6FA5C93F0729BA54EE6F46E80AF09AEAB355A594EEB3CD7A830553969EADFAEF637042B1ABBD442B22F31A21E2A5F89105A6F447CEEF9BAB09424D0D9C932`
SSDEEP | `24576:I8IflK01N/Jsr8YZD73W3Jdm0TzVYf7uA6:sfqD73+JPT5Yf7uf`
IMP | `8049F9993FD0B0E41EDE568A3C5646B8`
PESHA1 | `84948592B65113C2FC2E4AE3B2F26E900B538144`
PE256 | `2C1AC310B4B9E42BA347FF11F39E4C93623FB99321D4D0C5E8076BEDDE4840B3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SettingSyncHost.exe |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SettingSyncHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/73d8f23a1acf635a39b2dcb8b37304658f6f84d1090af961ea031efab833d916/detection


## Possible Misuse

*The following table contains possible examples of `SettingSyncHost.exe` being misused. While `SettingSyncHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `title: Using SettingSyncHost.exe as LOLBin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `description: Detects using SettingSyncHost.exe to run hijacked binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `- https://www.hexacorn.com/blog/2020/02/02/settingsynchost-exe-as-a-lolbin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `Name: SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Command: SettingSyncHost -LoadAndRunDiagScript anything`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Command: SettingSyncHost -LoadAndRunDiagScriptNoCab anything`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Path: C:\Windows\System32\SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Path: C:\Windows\SysWOW64\SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- IOC: SettingSyncHost.exe should not be run on a normal workstation`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Link: https://www.hexacorn.com/blog/2020/02/02/settingsynchost-exe-as-a-lolbin/`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


