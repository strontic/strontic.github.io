---
title: fltMC.exe | Filter Manager Control Program
excerpt: What is fltMC.exe?
---

# fltMC.exe 

* File Path: `C:\Windows\system32\fltMC.exe`
* Description: Filter Manager Control Program

## Hashes

Type | Hash
-- | --
MD5 | `6AB08CADCE7DF971A043DCD1257D7374`
SHA1 | `27BF9EB6969D40910AAF6C1B9E4A424F2D8ED88D`
SHA256 | `D127CC48C864A84DF91C3132314EC9698855DFBB6E9AFF97AB13023E9EAFF8B4`
SHA384 | `FE3ABEE003D9B1CA6427CA142B909E9F51A2322B19B3291741DFF808D091225AFD4EE1B94E5388671BCC94C51DEEE2B5`
SHA512 | `6905AF58DA34B02A28C174BD8F5464B32614AF0A6D8E83CCD75110B56DADD2FC40F0E116B1139EC871082A955698F6BD451FC1473C766E8DF85B67E2FFEB8EFF`
SSDEEP | `768:ovTzG/rqYhvazMpo8VUIzRAjzQ6cRsG1zJ:MYr9Le8HAvQ6cRsGpJ`
IMP | `D9C40185EFB3517F3A8819033083C33B`
PESHA1 | `5426D7B257FBC50A7801FEF89F1C6A768BC0FDFF`
PE256 | `79603696C604367217EFBE973A7510316DFF0A1836B2B48AD4F781E36F238874`

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
C:\Windows\system32\fltMC.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fltMC.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/d127cc48c864a84df91c3132314ec9698855dfbb6e9aff97ab13023e9eaff8b4/detection


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


