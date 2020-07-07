---
title: dllhost.exe | COM Surrogate
---

# dllhost.exe 

* File Path: `C:\windows\SysWOW64\dllhost.exe`
* Description: COM Surrogate
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B5A6D2FB3F4521C37D613DE52AB3467D`
SHA1 | `ACCEC11EA57BF2260D9C31C2C32D01CCA940E3D6`
SHA256 | `F95B7BA752C6452DA9D83F84CA7307AE079D220718BCB2BABF145903BAC894DD`
SHA384 | `C57856474AD5B0067A6576726CB0699C5E0B0EBC5EF67EBE103D9AA6916067E349C6D50E704CA88C897300459A4E5792`
SHA512 | `FBE13C39C6FC6CD8653F3BCE97F36104D2457F62574336A4E5FFEA0FC51A9D3FBBE657AEA8CF037F492AE4983B2141E116235208EBBBA3CB55F9C291ACB6641E`
SSDEEP | `384:3bme1zCcDlan3MNcyWL5W6RmXjDBRJadWJZ6lPUs2L:K0XBe3MNc/doXj1PaWb`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dllhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-50D5FD1290D94D46ACCA0585311E74D5.md) | 35
[C:\WINDOWS\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-E22E7BD6B146BDE93DC48643B772D8BB.md) | 30
[C:\Windows\system32\browser_broker.exe](browser_broker.exe-C7C56DB13D5F1A2BB6DE92B8BBD22CA0.md) | 30
[C:\WINDOWS\system32\dllhost.exe](dllhost.exe-680045579134D8AD9D0400A9DBE30786.md) | 35
[C:\Windows\system32\dllhost.exe](dllhost.exe-D2AB39EA2C0FCD172751F84BDA723A97.md) | 46
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-6DD5ECC82E9118B2DE1CAE3B35550E14.md) | 32
[C:\WINDOWS\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-94C10EAE7738DA6F112A6407E8C952F8.md) | 38
[C:\Windows\system32\prproc.exe](prproc.exe-7ABD17EE7B6B0F79CD4D2F3D4B4B11C2.md) | 30
[C:\WINDOWS\system32\prproc.exe](prproc.exe-BFD6335E4F61D44CA74B627A45686106.md) | 29
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 32
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-2CE65A4F9A63402F38537BE59FA1689D.md) | 32
[C:\WINDOWS\system32\SlideToShutDown.exe](SlideToShutDown.exe-C428A6CE6F4424BF148AF087C0BF4B75.md) | 33
[C:\WINDOWS\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-DD15DCECF4B1EF67B89FA0B603C7D413.md) | 30
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F8D636BD68156F0C653DBC3D69FC0F08.md) | 36
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-443AFE0E4385A46CFE2AD14890DC1FD4.md) | 29
[C:\WINDOWS\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-8E0D0D53CA176DDA94850F7A3B406408.md) | 29
[C:\WINDOWS\SysWOW64\dllhost.exe](dllhost.exe-60D0B50CFF3A0722ADC274F49FB16F14.md) | 36

## Possible Misuse

*The following table contains possible examples of `dllhost.exe` being misused. While `dllhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `            - 'C:\windows\system32\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `        ParentCommandLine\|contains: '\DllHost.exe '` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


