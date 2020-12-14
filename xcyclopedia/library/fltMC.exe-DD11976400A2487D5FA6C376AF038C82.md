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
MD5 | `DD11976400A2487D5FA6C376AF038C82`
SHA1 | `2175910A7D7A607ADAAB00BEEB151F0499E2E608`
SHA256 | `074A471560CDC15AD2D982CADCE9D3A081F70E11AC69E6B73111AF2C02C6375E`
SHA384 | `ADCA62886ACC7002F07950845C8B7D5571651C9693383E506638F95DF80CFC86B41FD56DA5C8B8DB97859E22BF9FA080`
SHA512 | `8A6C0547BFEBF9233C9DE678345780B0AF748C5B8A1C5F8D813E8DDCF674D10278B50F5F3CA987DCF74B03EE7C20311315FE0FF8451BA4DA8531EB6A24B3E504`
SSDEEP | `768:uvaG/rqYhWazMp48VU4zR2jz93cRCcXdCR:8LULO832v93cRL8R`
IMP | `D9C40185EFB3517F3A8819033083C33B`
PESHA1 | `594C7AC16509313812FC005958E9301077631A4D`
PE256 | `C63AE8487E3C2D98711544F0B59DF16158153BC04C464D1014369A66DD07BEEC`

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

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/074a471560cdc15ad2d982cadce9d3a081f70e11ac69e6b73111af2c02c6375e/detection/


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


