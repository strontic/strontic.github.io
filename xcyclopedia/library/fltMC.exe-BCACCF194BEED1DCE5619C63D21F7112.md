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
MD5 | `BCACCF194BEED1DCE5619C63D21F7112`
SHA1 | `D687EFAFF69FDE523BF638A87CDA3011307742F7`
SHA256 | `E353C7945308C1220319CBB69E2A2370334D7849304EB3BB7B1D2FD811C4324E`
SHA384 | `6487559081277CB80496884D977BD8BB9B2991A38CBB3C74FB8660BC4DB171381BB8DA92B16BC0C907C06957A192F11E`
SHA512 | `54C725FD71AA38C573505B9544487A1144298B0E1C5B5551D2FFF3BE461DE2FDFCBFBB9D6F288D480D0665141C8E9494A93901184EE52379565EADFD79B9F1CA`
SSDEEP | `384:ootQpz/lfQ1lNMqTXLnOKY3DpcfgDBsOc3a8emPu0XfIRpBwi1WT9W:oow/lfQLNMa7nOKY1DmLXIRpBwiW`
IMP | `F3A130AFBB5F42C25DFB7D99CBAFA050`
PESHA1 | `CA3EFA517BFDF55C64D40811069B932DEEB50E21`
PE256 | `1F5E7DD2858C11EF2A2915332E5F11C7529F34BFD491D298CA0DA6AACB71E863`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fltMC.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e353c7945308c1220319cbb69e2a2370334d7849304eb3bb7b1d2fd811c4324e/detection/


## Possible Misuse

*The following table contains possible examples of `fltMC.exe` being misused. While `fltMC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\fltMC.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sysmon_driver_unload.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sysmon_driver_unload.yml) | `Image\|endswith: '\fltmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | fltmc.exe \| findstr.exe 385201 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | fltmc.exe unload #{sysmon_driver} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(fltmc.exe filters \| findstr #{sysmon_driver}) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


