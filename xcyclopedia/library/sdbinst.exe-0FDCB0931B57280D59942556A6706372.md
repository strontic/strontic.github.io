---
title: sdbinst.exe | Application Compatibility Database Installer
---

# sdbinst.exe 

* File Path: `C:\windows\SysWOW64\sdbinst.exe`
* Description: Application Compatibility Database Installer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0FDCB0931B57280D59942556A6706372`
SHA1 | `7FA30FEEB87001A6DCC46E160CD93E2486A07FD6`
SHA256 | `820AE49D5CA9B263A6B1C54CC0BC69654CDED6591C37924E8CB116B2A5566179`
SHA384 | `AB046A62D21B502100B8910291DB62A82B50195540C93879B204BE1F58015DB28907AC5D1BF465C245169CF6F8F47B78`
SHA512 | `D8B8663E4938A5CB7318FC93EDB0306244948B6C1722240E6EECECA8E28987F01CE21841905DA01E17484F7A99D89165034A878A7DB568CE197595919F8F3779`
SSDEEP | `384:4hhA/E3kBRp47HUEEP66GmA/kxdmXvb0y2E9P8VxcayRRHfW5gWc:G6q7H/y66GT/pb0FE9P8r/yRRHO`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\sdbinst.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sdbinst.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sdbinst.exe` being misused. While `sdbinst.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `title: Possible Shim Database Persistence via sdbinst.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `description: Detects installation of a new shim using sdbinst.exe. A shim can be used to load malicious DLLs into applications.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sdbinst_shim_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sdbinst_shim_persistence.yml) | `            - '*\sdbinst.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | A list of all shims currently installed by the default Windows installer (sdbinst.exe) is kept in: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | sdbinst.exe -u #{file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


