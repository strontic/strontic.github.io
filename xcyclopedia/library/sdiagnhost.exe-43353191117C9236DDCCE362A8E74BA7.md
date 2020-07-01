---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
---

# sdiagnhost.exe 

* File Path: `C:\Windows\SysWOW64\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `43353191117C9236DDCCE362A8E74BA7`
SHA1 | `6A0B5CE7964379CE5019E46302EFDF6F5EC19A95`
SHA256 | `3584436E99BD2D420E9066E3A237ED1BE41E964E92FB5E1C88E052E6C834B1DA`
SHA384 | `401182DCA59A4CC3B3A28DDE61F52ADF67B28B70161EED5DE82AB34CA982F5C2742A00E520AA2F125C41E533DD3B9912`
SHA512 | `94014C6EB596222A7E72E089518AA071F24C870DEDA3050B6EB4D9A9766A0291D31A009E94CF2874AB8FCEEAC8AFBA97465D38E295874025948573648A4E732F`
SSDEEP | `384:zHm8MXAvaHQ41cJluoPk8KWreBiyj7hZxaLelgWh7DWIH:wHElu4b8j75aLeN`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-258F58247AACD6568910D85E33A07886.md) | 80
[C:\Windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-48582EF64F96E054C0CDCF3055258101.md) | 52
[C:\windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-BD954F1A95B1C1B0D68AC4AF5E427807.md) | 41

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `            - '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `            - '*\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_in_memory_powershell.yml) | `            - '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


