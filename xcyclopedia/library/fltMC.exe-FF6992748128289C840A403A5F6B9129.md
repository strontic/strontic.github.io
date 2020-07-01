---
title: fltMC.exe | Filter Manager Control Program
---

# fltMC.exe 

* File Path: `C:\windows\system32\fltMC.exe`
* Description: Filter Manager Control Program
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FF6992748128289C840A403A5F6B9129`
SHA1 | `2AF439B55171D6E63488F9419D17B9BFF8C54C15`
SHA256 | `44D21763D35630C2CE68A2A64D4EB047B83847BCEFE4AE3911545B8FAA22EF8B`
SHA384 | `E22683DC05797B2731CB2A8AEE211A2EF3397E4E31963FDD17D1247142B36CB0BC62E4332E2C8D4C6F1ED8F8E9022ECC`
SHA512 | `231E93EF05CEC8F2D29985436671DED021FD61F8DB1B2B3FD0911B90072B1CA7A92A6CAB65D341FA8C82D8B530D569BFE18646CE44D417ED101E1D0EBE000EAB`
SSDEEP | `384:C8oSwWz/I6sxLcWN1qBzs7k5FeHGo+0bdcAS3UTOCGXew2ytEnJlWG9W:Rt/I6saWNks7EB0xSETNjCEJT`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\fltMC.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: fltMC.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `fltMC.exe` being misused. While `fltMC.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `            - '*\Windows\System32\fltMC.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sysmon_driver_unload.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sysmon_driver_unload.yml) | `        Image\|endswith: '\fltmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | fltmc.exe \| findstr.exe 385201 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | fltmc.exe unload #{sysmon_driver} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(fltmc.exe filters \| findstr #{sysmon_driver}) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


