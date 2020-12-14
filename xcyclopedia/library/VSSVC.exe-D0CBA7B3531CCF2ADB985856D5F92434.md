---
title: VSSVC.exe | Microsoft Volume Shadow Copy Service
excerpt: What is VSSVC.exe?
---

# VSSVC.exe 

* File Path: `C:\windows\system32\VSSVC.exe`
* Description: Microsoft Volume Shadow Copy Service

## Hashes

Type | Hash
-- | --
MD5 | `D0CBA7B3531CCF2ADB985856D5F92434`
SHA1 | `A568213292F5933475BF2AC581860D47AE879E1D`
SHA256 | `7FCBBCAF1AA85DCE8D75FB38DC4848AE12E8DD913CEBBC37BCD3D0123F0A3CAB`
SHA384 | `05B2F2517956DF409151CE34B151A8BA41B922038A7622B6F90C442EB8E84FA22970D64F933AE77E3B21071A9E7A963D`
SHA512 | `734DEF48F2D45781C3F226053FC365D114E8EE66EEC1A00FAA89B9F02CFB6B6252DF11EA79790AA392B208BC960189CFD7A7E0B71478203C6D0C479CB9417DCF`
SSDEEP | `24576:z1dgSii86um7SXMjN2iooZyCDm6rdiCk65Z:z1dgVi86um7S8gvl6rd/Z`

## Signature

* Status: The file C:\windows\system32\VSSVC.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


