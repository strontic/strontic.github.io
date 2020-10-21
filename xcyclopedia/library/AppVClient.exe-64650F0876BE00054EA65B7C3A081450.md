---
title: AppVClient.exe | Microsoft Application Virtualization Client Service
excerpt: What is AppVClient.exe?
---

# AppVClient.exe 

* File Path: `C:\Windows\system32\AppVClient.exe`
* Description: Microsoft Application Virtualization Client Service

## Hashes

Type | Hash
-- | --
MD5 | `64650F0876BE00054EA65B7C3A081450`
SHA1 | `488520C688D96219E057D54942DBCC23D7F5C881`
SHA256 | `B9D349C732032C405415B2F85A9365526D3EAE3007E404042957B73D647F534A`
SHA384 | `BE6EA327942ECD8DF49CCB3EC79D48FF36B45B5FD06FA0671931092F970FB244D5377C3E0539CDDFAE9CB61877E42AD1`
SHA512 | `B0A5E5DAB0DB46E142F3444E8D003F9D7BA11472CB2733CDEEF97297EAC8BB954A21F4B95C7190146508C0458B5DEF7A95A5EFA0A7CDB93350CB4D6B2ABB431C`
SSDEEP | `12288:EA3NOjSfAJuWjHArR57r/zmCGNUbTNR0MXsJl:EA3uXJdHArR57rmMX0l`
IMP | `5054081A378EFBE521A9C039EA173CC4`
PESHA1 | `E63B2CF784F590789E9F0822DCA650316BDCBFD5`
PE256 | `DB408A265F7159AFC433653C2D3B1F48911F2A5357F406D2D587364A2F185767`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\AppVClient.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVClient.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1007 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1007
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/b9d349c732032c405415b2f85a9365526d3eae3007e404042957b73d647f534a/detection/


## Possible Misuse

*The following table contains possible examples of `AppVClient.exe` being misused. While `AppVClient.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `- AppvClient` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


