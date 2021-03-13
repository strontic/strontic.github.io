---
title: InfDefaultInstall.exe | INF Default Install
excerpt: What is InfDefaultInstall.exe?
---

# InfDefaultInstall.exe 

* File Path: `C:\windows\system32\InfDefaultInstall.exe`
* Description: INF Default Install

## Screenshot

![InfDefaultInstall.exe](screenshots/InfDefaultInstall.exe-6E4ACBE95965D394FE042E1C0B5D7206-1.png)
![InfDefaultInstall.exe](screenshots/InfDefaultInstall.exe-6E4ACBE95965D394FE042E1C0B5D7206-2.png)
![InfDefaultInstall.exe](screenshots/InfDefaultInstall.exe-6E4ACBE95965D394FE042E1C0B5D7206-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `89218DF55881B8AEFF5BCD0C09B4A1AB`
SHA1 | `4DD2B8BE7687A1F17790D7880765E6A47D8B7ED6`
SHA256 | `0B63D3764337E6898E35481AAA2FFA0F5F5B802F2EA7CC202126550B44528859`
SHA384 | `E33D51D4A68545B200DB1939B9183F65405C0B30A27AEA2F58C395DE2F34939B9BA4E9E80D38C731467BB8859274A1E0`
SHA512 | `E50233C4C29697C2761D1A4AF9603FF600591DC2F3ACA324A6E8832F0EC8593B56BE66A729BADDF32B257369605EB8FDE431696E9E12D5F108F196EBBDA34B8A`
SSDEEP | `192:TS/by2Zb+WPl8Dqz4zczpNsuzVoobDfO8DPL7pemOMsNW/GWU:e/by2J+xuz4ArsQVVDtDPL7Ee2W/GWU`

## Signature

* Status: The file C:\windows\system32\InfDefaultInstall.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: InfDefaultInstall.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.2.3668.0
* Product Version: 5.2.3668.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `InfDefaultInstall.exe` being misused. While `InfDefaultInstall.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `Name: Infdefaultinstall.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `- Command: InfDefaultInstall.exe Infdefaultinstall.inf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `- Path: C:\Windows\System32\Infdefaultinstall.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `- Path: C:\Windows\SysWOW64\Infdefaultinstall.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: InfDefaultInstall.exe .inf Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: InfDefaultInstall.exe .inf Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #4 - InfDefaultInstall.exe .inf Execution](#atomic-test-4---infdefaultinstallexe-inf-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #4 - InfDefaultInstall.exe .inf Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Test execution of a .inf using InfDefaultInstall.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Reference: https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | \| inf_to_execute \| Local location of inf file \| string \| PathToAtomicsFolder&#92;T1218&#92;src&#92;Infdefaultinstall.inf\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | InfDefaultInstall.exe #{inf_to_execute} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Invoke-WebRequest "https://github.com/redcanaryco/atomic-red-team/raw/master/atomics/T1218/src/Infdefaultinstall.inf" -OutFile "#{inf_to_execute}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


