---
title: wlanext.exe | Windows Wireless LAN 802.11 Extensibility Framework
excerpt: What is wlanext.exe?
---

# wlanext.exe 

* File Path: `C:\WINDOWS\system32\wlanext.exe`
* Description: Windows Wireless LAN 802.11 Extensibility Framework

## Hashes

Type | Hash
-- | --
MD5 | `A7D21DC33F8196CE5C8E29A5275B485B`
SHA1 | `1BA262997B31ED07034D0B3C6BE24F9CAA174C2B`
SHA256 | `15E02869B1C820C3F67145902D8A53C483EDCA1B5564B3D68FB278BA5DFA9595`
SHA384 | `D0A544738645A49459DAF94EC04BC4AFA0F8407C7822D6BDC59CF2E3E74E0A665C45A789995F62AB407194C6A2EC64A2`
SHA512 | `61C6D442C158C3A88E80ECCFCF7632010A1DC40EE8F91E866B6A53D1C41664B5E21E678D0ED35E54CADA32B326929DC7B1C5A9334CB763B6602B56DDFCA472A8`
SSDEEP | `1536:0k1Bqq14AczBdboMiKBMqiu15rj+42/lUWZmaWGRLWDbpbAtL:0iBqFASoMV5i++42/nEa5+b5AJ`
IMP | `1D3B6671C13D5AB37840F806C274ED8D`
PESHA1 | `82D463CEB24B709F5E56E4B1A2C08ADBE1E74582`
PE256 | `B7167A613ACB442351A1621B592004730243E7A1A819D6475389702474B0A005`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\wlanext.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanext.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/15e02869b1c820c3f67145902d8a53c483edca1b5564b3d68fb278ba5dfa9595/detection


## Possible Misuse

*The following table contains possible examples of `wlanext.exe` being misused. While `wlanext.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\wlanext.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\wlanext.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


