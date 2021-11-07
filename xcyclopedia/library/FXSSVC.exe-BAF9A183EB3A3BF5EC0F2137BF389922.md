---
title: FXSSVC.exe | Fax Service
excerpt: What is FXSSVC.exe?
---

# FXSSVC.exe 

* File Path: `C:\Windows\system32\FXSSVC.exe`
* Description: Fax Service

## Hashes

Type | Hash
-- | --
MD5 | `BAF9A183EB3A3BF5EC0F2137BF389922`
SHA1 | `3BCE34A2C74C7A4C0F4098ED092D15D618F4151B`
SHA256 | `F5F1381269A303798D5C879CCA0F7F627BE5081AB292FE652A86564010CD7E6E`
SHA384 | `B1D94BD45772406DFBF19C6A0CF1DC69B6E9BAE96C4150C1DA042446F4FE8B7DF4854D85898F5F79BB1D24402268A9E6`
SHA512 | `6BA73D9757243F2FEE15298AD6B631ED89B0AE93D7244B78F532D9DE20EFB0670D314732F82B51918F6CCB82AE5B94A8F1374C21B3BCCF3FC2C65A7D10C917C1`
SSDEEP | `12288:J/jWhF0YgnJdCFaUKUiWLk49cti+R8tYnHiy8Mzn4i/:N3YgnJcRTk4yti+R5dnR/`
IMP | `6F91BAF876B8AA66CF43576F7BE1E85F`
PESHA1 | `C2EA6B26A1CD008C95D3B8A9AE20640798F3996F`
PE256 | `52440B733CB7C3489A6A64BCC68DE7F962EAEFF7CB19CB6D72A9C7ECE7DB021A`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\FXSSVC.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FXSSVC.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.804 (WinBuild.160101.0800)
* Product Version: 10.0.19041.804
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/f5f1381269a303798d5c879cca0f7f627be5081ab292fe652a86564010cd7e6e/detection


## Possible Misuse

*The following table contains possible examples of `FXSSVC.exe` being misused. While `FXSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_fax_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_fax_dll.yml) | `- fxssvc.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc config Fax binPath= "C:\WINDOWS\system32\fxssvc.exe" >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


