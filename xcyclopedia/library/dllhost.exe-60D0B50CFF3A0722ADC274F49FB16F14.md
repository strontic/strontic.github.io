---
title: dllhost.exe | COM Surrogate
---

# dllhost.exe 

* File Path: `C:\WINDOWS\SysWOW64\dllhost.exe`
* Description: COM Surrogate
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `60D0B50CFF3A0722ADC274F49FB16F14`
SHA1 | `E04E8DEB73F29F336A68FA62CEC8AE863EEFAB90`
SHA256 | `4B878483EB200C8731F95096EEF036F285BD36AB916FE550DD484B872E60D037`
SHA384 | `6E9BC7DC5C3C9FFBC3F81144668399BD60E4C28D127B5CB8679513CB04F7AAED79ADBE48183987ABDEC9D0FEB5E20056`
SHA512 | `934A1D0CE45FB6EDBF0FF25325CBA44A8A99202FAF3B5B1024DECF41E46DE0F3C6FDFBF300CAB1E2FDFD592A6EABFE786FA7E9602C308C6E71A6C26F8403D034`
SSDEEP | `384:TnrG6z40eYJnRB/cCWx5WzbnmXjDBRJPraLbBlwA4BN:nR5eYRRB/cF6bmXj1P0b4`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dllhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-E22E7BD6B146BDE93DC48643B772D8BB.md) | 30
[C:\Windows\system32\browser_broker.exe](browser_broker.exe-C7C56DB13D5F1A2BB6DE92B8BBD22CA0.md) | 29
[C:\WINDOWS\system32\dllhost.exe](dllhost.exe-680045579134D8AD9D0400A9DBE30786.md) | 43
[C:\WINDOWS\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-94C10EAE7738DA6F112A6407E8C952F8.md) | 35
[C:\WINDOWS\system32\prproc.exe](prproc.exe-BFD6335E4F61D44CA74B627A45686106.md) | 38
[C:\WINDOWS\system32\SlideToShutDown.exe](SlideToShutDown.exe-C428A6CE6F4424BF148AF087C0BF4B75.md) | 33
[C:\WINDOWS\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-DD15DCECF4B1EF67B89FA0B603C7D413.md) | 35
[C:\WINDOWS\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-8E0D0D53CA176DDA94850F7A3B406408.md) | 25
[C:\WINDOWS\SysWOW64\dllhst3g.exe](dllhst3g.exe-F4597A01D79661E2813C7F9858F70E40.md) | 47

## Possible Misuse

*The following table contains possible examples of `dllhost.exe` being misused. While `dllhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `        ParentCommandLine: '*\DllHost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_adsi_cache_usage.yml) | `            - 'C:\windows\system32\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


