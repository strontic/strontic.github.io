﻿---
title: fltMC.exe | Filter Manager Control Program
excerpt: What is fltMC.exe?
---

# fltMC.exe 

* File Path: `C:\WINDOWS\system32\fltMC.exe`
* Description: Filter Manager Control Program

## Hashes

Type | Hash
-- | --
MD5 | `5DF5037E16319A6F6E21562C7B4F679C`
SHA1 | `096F9EB6FCC92DD18797E1F553257D0A89FDDDE1`
SHA256 | `FA85855B3CC7E02B4874304BDCEBE7ECE715DD03802970EEDD1C4A88E5B814D4`
SHA384 | `55269EEE6BA2FD27F162C9E1C3C7B97B95222608CE4FD941F1B1FEE02FCAFC1A3E0951E394493D29F70BF424427C6184`
SHA512 | `43455728E6F9D7BC302346B3622F7842C70283F65BD89D08390AFA6C8377CA2A3C2C6BA46ABB979498E33784D719D272EEB6845E5A53E990ADA18F7FC1F15368`
SSDEEP | `384:Q/h6z/vnI1cksqTXLbPY39DxsOdCPs7UsOt8d8n+XfvRpBi4VWp9W:Q56/vnI6ksa7bPYVL7jgGvRpBi4g`

## Runtime Data

### Usage (stdout):
```cmhg

** Invalid command
Valid commands:
    load        Loads a Filter driver
    unload      Unloads a Filter driver
    filters     Lists the Filters currently registered in the system
    instances   Lists the Instances for a Filter or Volume currently
                registered in the system
    volumes     Lists all volumes/RDRs in the system
    attach      Creates a Filter Instance to a Volume
    detach      Removes a Filter Instance from a Volume

    Use fltmc help [ command ] for help on a specific command

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fltMC.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `fltMC.exe` being misused. While `fltMC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\System32\fltMC.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `description: Detects the use of stordiag.exe to execute schtasks.exe systeminfo.exe and fltmc.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `- '\fltmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sysmon_driver_unload.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sysmon_driver_unload.yml) | `Image\|endswith: '\fltmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [FltMC.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/FltMC.yml) | `Name: fltMC.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [FltMC.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/FltMC.yml) | `- Command: fltMC.exe unload SysmonDrv`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [FltMC.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/FltMC.yml) | `- Path: C:\Windows\System32\fltMC.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [FltMC.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/FltMC.yml) | `- IOC: 4688 events with fltMC.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `Description: Once executed, Stordiag.exe will execute schtasks.exe systeminfo.exe and fltmc.exe - if stordiag.exe is copied to a folder and an arbitrary executable is renamed to one of these names, stordiag.exe will execute it.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `- IOC: systeminfo.exe, fltmc.exe or schtasks.exe being executed outside of their normal path of c:\windows\system32\ or c:\windows\syswow64\`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | fltmc.exe \| findstr.exe 385201 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | fltmc.exe unload #{sysmon_driver} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(fltmc.exe filters \| findstr #{sysmon_driver}) { exit 0 } else { exit 1 } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


