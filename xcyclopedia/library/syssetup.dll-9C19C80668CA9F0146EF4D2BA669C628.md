---
title: syssetup.dll | Windows NT System Setup
excerpt: What is syssetup.dll?
---

# syssetup.dll 

* File Path: `C:\Windows\system32\syssetup.dll`
* Description: Windows NT System Setup

## Hashes

Type | Hash
-- | --
MD5 | `9C19C80668CA9F0146EF4D2BA669C628`
SHA1 | `6F71EE29229FC0A3602297E96F602914B20CE1C0`
SHA256 | `9268F6A26D8F2A82344680A95C241BE06CA53F27BC266A4C8D1274D4A7E128FE`
SHA384 | `2A122CBFD961F8E77D579CF473F1A492765BC22649809A2BEE5B0B5D489A56113A8C63D7ADE5B91D5D262B21C0EF937D`
SHA512 | `470DEE5CA0D0970C0BDF26F9F595D9DD213BC4641190DCD69FBDC13E475D1451FED9D2CFBB1B9112E3C7BA1103EB3A5E5E40F94FDF0AC5E1993E90BEB3B46920`
SSDEEP | `384:02GwAzIhh/MOLqyoOEhdZ93Wh2lnqWUnW:h0IUpnzQSY`
IMP | `FE9AFF7B41A154AC9D71AB2967CC3EED`
PESHA1 | `A42138619FFCFFAF9A770A5BD32ABCBEF83B13F3`
PE256 | `691CAD7767257520E9339F4C8937F32E7349C124916BFE6B7B51BDE37A677611`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`AsrAddSifEntryA` | 1 | Exported Function
`AsrAddSifEntryW` | 2 | Exported Function
`AsrCreateStateFileA` | 3 | Exported Function
`AsrCreateStateFileW` | 4 | Exported Function
`AsrFreeContext` | 5 | Exported Function
`AsrRestorePlugPlayRegistryData` | 6 | Exported Function
`GetAnswerFileSetting` | 7 | Exported Function
`SetupChangeFontSize` | 8 | Exported Function
`SetupInfObjectInstallActionW` | 9 | Exported Function
`SetupSetDisplay` | 10 | Exported Function
`WaitForSamService` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/9268f6a26d8f2a82344680a95c241be06ca53f27bc266a4c8d1274d4a7e128fe/detection/


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


