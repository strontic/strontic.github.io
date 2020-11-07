---
title: fltMC.exe | Filter Manager Control Program
excerpt: What is fltMC.exe?
---

# fltMC.exe 

* File Path: `C:\Windows\SysWOW64\fltMC.exe`
* Description: Filter Manager Control Program

## Hashes

Type | Hash
-- | --
MD5 | `B92F52CF282A7077B2F33F738CBEC322`
SHA1 | `13976D41F2E7CB57D0C524E06A541BA960CA1F06`
SHA256 | `ED93A19342F39822378F3DEC9CD3F6BF48EF44B1A26FBEA41D6932A79CE4002E`
SHA384 | `6380D69FFBBAE87B342CAC1CA1DA89B5D551F6F0C9E7E98ED128F75DA1AEBAE606583964156C0BEF55187E3C8B6F07B5`
SHA512 | `1CC06DB162D2EF32A3CE7C6F5817BAFECB846909C1A5CAAE26C123D58B82031F453728CD60EFD26D160AF97C05E3E7C1596E853BCB11E7E12BEE63FDEFD0E717`
SSDEEP | `384:lAMNUGvYUI9LwOnrnq0px6izavkJjjJ5X8cR2VWo9Wi6:lFI9LwOnrnq2oiOvk3+cR2B`
IMP | `50932E942F8E6C207BD1C02FB974B27C`
PESHA1 | `38EE17ACA629F38164981782B854580047612298`
PE256 | `CEA63BCDE1325E55C1402EC7AB66B87367854B6B7EA96471B2153F237E40D811`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\fltMC.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fltMC.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/ed93a19342f39822378f3dec9cd3f6bf48ef44b1a26fbea41d6932a79ce4002e/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\fltMC.exe](fltMC.exe-330E111C418797FC2E56F3F7E5FAAB9A.md) | 93

## Possible Misuse

*The following table contains possible examples of `fltMC.exe` being misused. While `fltMC.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\fltMC.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sysmon_driver_unload.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sysmon_driver_unload.yml) | `Image\|endswith: '\fltmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | fltmc.exe \| findstr.exe 385201 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | fltmc.exe unload #{sysmon_driver} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(fltmc.exe filters \| findstr #{sysmon_driver}) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


