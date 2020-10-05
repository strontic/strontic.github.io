---
title: syssetup.dll | Windows NT System Setup
excerpt: What is syssetup.dll?
---

# syssetup.dll 

* File Path: `C:\Windows\SysWOW64\syssetup.dll`
* Description: Windows NT System Setup

## Hashes

Type | Hash
-- | --
MD5 | `A842EE0DFA673C3A2C2FB06DDA000A9B`
SHA1 | `7E0055D91521418596B1228D649D0D9D0D2DB3C1`
SHA256 | `33DD3B9C831B95B3904218EFAE3810FCC1583E7BDB8BA4C4FC8E1B7A8ABF1B46`
SHA384 | `24E1DE329DEE32E3818F144A789473E5DA88C8D5C05A15E2BCF4BC4AD449B01E20AB9F686C27B794D3D9895790FB91E0`
SHA512 | `10B6A6533E2F74F720C662531A8CC4693496DA4783C3E545C36DEE092E65BFF90D9A2E36D840B38CAFF2DA1C810B51796EA3D26D0CB13D3EEC4B7387AF35F63E`
SSDEEP | `192:0z6AzionRGECO7c1CgBsVnR+wavNAKFD7JZAEzaRYne0XsWUnWEIja:h7oRdCQ4dBonR+w6NAKZFm52KWUnWE0`
IMP | `F11EB280AD85AC6509A9B9FE2CED567B`
PESHA1 | `B5BD856F5CA01B1228092028CA5DDE9DD43C1FD5`
PE256 | `655F044770C914D9B3D5E56395E57E254E20364285375CFDCE63527446A449E1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SetupChangeFontSize` | 8 | Exported Function
`GetAnswerFileSetting` | 7 | Exported Function
`SetupInfObjectInstallActionW` | 9 | Exported Function
`WaitForSamService` | 11 | Exported Function
`SetupSetDisplay` | 10 | Exported Function
`AsrRestorePlugPlayRegistryData` | 6 | Exported Function
`AsrAddSifEntryW` | 2 | Exported Function
`AsrAddSifEntryA` | 1 | Exported Function
`AsrCreateStateFileA` | 3 | Exported Function
`AsrFreeContext` | 5 | Exported Function
`AsrCreateStateFileW` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SYSSETUP.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/33dd3b9c831b95b3904218efae3810fcc1583e7bdb8ba4c4fc8e1b7a8abf1b46/detection/


## Possible Misuse

*The following table contains possible examples of `syssetup.dll` being misused. While `syssetup.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `Name: Syssetup.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `- Command: rundll32.exe syssetup.dll,SetupInfObjectInstallAction DefaultInstall 128 c:\test\shady.inf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `- Command: rundll32 syssetup.dll,SetupInfObjectInstallAction DefaultInstall 128 c:\temp\something.inf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `- Path: c:\windows\system32\syssetup.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `- Path: c:\windows\syswow64\syssetup.dll` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: Rundll32 syssetup.dll Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: Rundll32 syssetup.dll Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | - [Atomic Test #5 - Rundll32 syssetup.dll Execution](#atomic-test-5---rundll32-syssetupdll-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | ## Atomic Test #5 - Rundll32 syssetup.dll Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | Test execution of a command using rundll32.exe with syssetup.dll. Upon execution, a window saying "installation failed" will be opened | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | Reference: https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | rundll32.exe syssetup.dll,SetupInfObjectInstallAction DefaultInstall 128 .\#{inf_to_execute} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


