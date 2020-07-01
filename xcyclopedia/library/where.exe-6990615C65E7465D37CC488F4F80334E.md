---
title: where.exe | Where - Lists location of files
---

# where.exe 

* File Path: `C:\windows\SysWOW64\where.exe`
* Description: Where - Lists location of files
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6990615C65E7465D37CC488F4F80334E`
SHA1 | `39782671DC173C8713F07FE4C10470C4B9F87E65`
SHA256 | `9323D73E1129EEBDA48815D13B944098BF4FBA87713A086C49DD53BF2ED70103`
SHA384 | `951C86D66191C7E92809915EDB3253709488442C7DCD0742B82B482F0972AF7DFC216C322F4142217FE34A5AAC6E0C69`
SHA512 | `1C48C0B212FFC9EC48B77BF4029704B844DDF779B879629D35D2106D9FDA4C509D59AC73365EC7B947AEF9D5C48B2C9C6C25EEA3C58919CBB891D8B57CE788FE`
SSDEEP | `768:7BBXPb5lTv/ji71ZJqxQVH2LXtgePpzvAT0A5xYx1MA:7BBXPbPvOpzMMWLXtpOHxYxCA`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\where.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: where.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `where.exe` being misused. While `where.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") { C:\Windows\Sysmon.exe -accepteula -i } else | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


