---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
---

# sdiagnhost.exe 

* File Path: `C:\WINDOWS\SysWOW64\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `258F58247AACD6568910D85E33A07886`
SHA1 | `FA548C1DD391B95B01DDF73BD02BE8EB5BE7BF42`
SHA256 | `54068377F0997D166285EFAB83C50AB7D17A3F1ED87B750A0F9C91D3DC95A689`
SHA384 | `1139209288EC199B8D0DBC310172694B0F3684F5B3255356C806C76D12B27F5861F4B8AB66C1B3164BCA6229C7ED1946`
SHA512 | `3EA33ADF1BCF77392A9A8E85777D9711C16373EBE3C9C56F7AF7598DDB628E3533F48A09A8E7F3C8CB35714F0E84FBCD63E15F9AF8A81207148A30BD56B5840E`
SSDEEP | `384:zXHm8MXAva54Q41cJluoAk8KWreBSe7mEZxaLelQWA7DWMH:o54EluXb47mmaLe8`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-43353191117C9236DDCCE362A8E74BA7.md) | 80
[C:\Windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-48582EF64F96E054C0CDCF3055258101.md) | 50
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


