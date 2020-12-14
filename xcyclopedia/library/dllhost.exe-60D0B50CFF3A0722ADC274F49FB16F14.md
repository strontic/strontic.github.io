---
title: dllhost.exe | COM Surrogate
excerpt: What is dllhost.exe?
---

# dllhost.exe 

* File Path: `C:\WINDOWS\SysWOW64\dllhost.exe`
* Description: COM Surrogate

## Hashes

Type | Hash
-- | --
MD5 | `60D0B50CFF3A0722ADC274F49FB16F14`
SHA1 | `E04E8DEB73F29F336A68FA62CEC8AE863EEFAB90`
SHA256 | `4B878483EB200C8731F95096EEF036F285BD36AB916FE550DD484B872E60D037`
SHA384 | `6E9BC7DC5C3C9FFBC3F81144668399BD60E4C28D127B5CB8679513CB04F7AAED79ADBE48183987ABDEC9D0FEB5E20056`
SHA512 | `934A1D0CE45FB6EDBF0FF25325CBA44A8A99202FAF3B5B1024DECF41E46DE0F3C6FDFBF300CAB1E2FDFD592A6EABFE786FA7E9602C308C6E71A6C26F8403D034`
SSDEEP | `384:TnrG6z40eYJnRB/cCWx5WzbnmXjDBRJPraLbBlwA4BN:nR5eYRRB/cF6bmXj1P0b4`

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
[C:\Program Files (x86)\Common Files\microsoft shared\Ink\TabTip32.exe](TabTip32.exe-725AAEFD55B6DEA9663EEAA04E881C0E.md) | 30
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-50D5FD1290D94D46ACCA0585311E74D5.md) | 33
[C:\WINDOWS\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-E22E7BD6B146BDE93DC48643B772D8BB.md) | 30
[C:\Windows\system32\browser_broker.exe](browser_broker.exe-C7C56DB13D5F1A2BB6DE92B8BBD22CA0.md) | 29
[C:\WINDOWS\system32\dllhost.exe](dllhost.exe-680045579134D8AD9D0400A9DBE30786.md) | 43
[C:\Windows\system32\dllhost.exe](dllhost.exe-D2AB39EA2C0FCD172751F84BDA723A97.md) | 38
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-6DD5ECC82E9118B2DE1CAE3B35550E14.md) | 38
[C:\WINDOWS\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-94C10EAE7738DA6F112A6407E8C952F8.md) | 35
[C:\Windows\system32\prproc.exe](prproc.exe-7ABD17EE7B6B0F79CD4D2F3D4B4B11C2.md) | 35
[C:\WINDOWS\system32\prproc.exe](prproc.exe-BFD6335E4F61D44CA74B627A45686106.md) | 38
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 33
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-2CE65A4F9A63402F38537BE59FA1689D.md) | 32
[C:\WINDOWS\system32\SlideToShutDown.exe](SlideToShutDown.exe-C428A6CE6F4424BF148AF087C0BF4B75.md) | 33
[C:\WINDOWS\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-DD15DCECF4B1EF67B89FA0B603C7D413.md) | 35
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F8D636BD68156F0C653DBC3D69FC0F08.md) | 36
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-443AFE0E4385A46CFE2AD14890DC1FD4.md) | 27
[C:\WINDOWS\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-8E0D0D53CA176DDA94850F7A3B406408.md) | 25
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-B5A6D2FB3F4521C37D613DE52AB3467D.md) | 36
[C:\WINDOWS\SysWOW64\dllhst3g.exe](dllhst3g.exe-F4597A01D79661E2813C7F9858F70E40.md) | 47

## Possible Misuse

*The following table contains possible examples of `dllhost.exe` being misused. While `dllhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `- 'C:\windows\system32\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `title: Dllhost Internet Connection` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `description: Detects Dllhost that communicates with public IP addresses` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `Image: '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `ParentCommandLine\|contains: '\DllHost.exe '` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) | $s7 = "dllhost.dat" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


