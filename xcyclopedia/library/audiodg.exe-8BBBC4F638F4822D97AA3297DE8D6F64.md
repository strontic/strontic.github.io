---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `8BBBC4F638F4822D97AA3297DE8D6F64`
SHA1 | `3021F747D121FEDE2ACF00AB968A44E1E20941CF`
SHA256 | `97C8AAEDBA3A89174BC6DDD8B5B40504A81E7ADAE8DF6B11230EB34B150FFC3B`
SHA384 | `D116F8CBFF91C75092A5122E4268147CEE7AAA346E3AEA2AE57BDD1C2197277E1C2A4C35AB9908BB74CDBFC379A0C19F`
SHA512 | `11889940A1E989CA2D5E05CBB4668938F53D0B553E0CA1745B06274E2154A0CD4F4D6C95B2CF5C6CD1CBF824E278EF085912570A7D3940A36B2CF059CAF989ED`
SSDEEP | `12288:7ShVuOWu9UY2EsIyyAKe9BcOBscwOo5tbyH:+hVCuqYmIfAKq6ablo5tk`
IMP | `356C5FB039EB7424A518F132A23D3232`
PESHA1 | `105F308736BB958ECFC1B046C290975E4CEE7D31`
PE256 | `6D2DEB2E7004EAA74405B71B2DC18FBC75F92C70FBC3F288458ECB36B94C1532`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\audiodg.exe |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/97c8aaedba3a89174bc6ddd8b5b40504a81e7adae8df6b11230eb34b150ffc3b/detection


## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


