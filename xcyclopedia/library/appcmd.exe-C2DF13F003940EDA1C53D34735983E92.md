---
title: appcmd.exe | Application Server Command Line Admin Tool
---

# appcmd.exe 

* File Path: `C:\windows\SysWOW64\inetsrv\appcmd.exe`
* Description: Application Server Command Line Admin Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C2DF13F003940EDA1C53D34735983E92`
SHA1 | `633CDE96E4D5AF88B19A7126499039FB7E9B979F`
SHA256 | `E1997829E5A0D5EC1327B68F194B803C5EA30AD9B42BA42D54387E16D3AE53F5`
SHA384 | `363DA8DA14626F2D6B8C06F6CFAD1E6DD298BDEE16B56F43CC8BC4E78442442712EACA1D8BAD901FD57B5ADB2F2AE1D0`
SHA512 | `EE42995DD53986437F31615BDF5BA4B7BE999FEFD7D5DD4D8A2BA18A6B7E4D8A84F91B7B23A416F9A84B36AA78826C7D9410DFD49D0C3A06005A05AFC415CDFF`
SSDEEP | `3072:VzV5li/qcZuZ4fihdXMpUbFBW2Q1q0we8lULMlA4ah:7vgu4fiEpWK2O42`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\inetsrv\appcmd.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: appcmd.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 8.5.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 8.5.9600.16384
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `appcmd.exe` being misused. While `appcmd.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_iss_module_install.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_iss_module_install.yml) | `            - '*\APPCMD.EXE install module /name:*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:true | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:false | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


