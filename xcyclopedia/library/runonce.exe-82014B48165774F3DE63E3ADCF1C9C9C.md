---
title: runonce.exe | Run Once Wrapper
excerpt: What is runonce.exe?
---

# runonce.exe 

* File Path: `C:\WINDOWS\system32\runonce.exe`
* Description: Run Once Wrapper

## Hashes

Type | Hash
-- | --
MD5 | `82014B48165774F3DE63E3ADCF1C9C9C`
SHA1 | `EAA08E3EAC0C7E6FA37E95D0CB413696EC74C55F`
SHA256 | `60783BDF30B026D8FB92CBE6E2FA79E8352B38EABFD21F7E4310E3522888F33F`
SHA384 | `965C001F16A17A07BE8662942511B27A62AF8E466FFD8B41503B290F2B14CE0A13E843F104A890003DABE5245BC24E0C`
SHA512 | `18790DC6619C90E147C68143C667E827407BF8C6AC94C753689172BF1F688471B74CB1C1350DD6BFF619D916C5BD4D3CA0E469F3851E8BEE51235CB398D82941`
SSDEEP | `1536:UAEVlUQH0CoVIxCvkepGvo8ahhjCCi9tJNwo1RQ4NXqDTvZqgL:UA+szVmSMo5hhF4NXKRqK`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNONCE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `runonce.exe` being misused. While `runonce.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\runonce.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `Name: Runonce.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Command: Runonce.exe /AlternateShellStartup`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\System32\runonce.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\SysWOW64\runonce.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


