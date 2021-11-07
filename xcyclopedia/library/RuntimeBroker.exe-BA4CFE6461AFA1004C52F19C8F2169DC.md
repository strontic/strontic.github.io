---
title: RuntimeBroker.exe | Runtime Broker
excerpt: What is RuntimeBroker.exe?
---

# RuntimeBroker.exe 

* File Path: `C:\Windows\system32\RuntimeBroker.exe`
* Description: Runtime Broker

## Hashes

Type | Hash
-- | --
MD5 | `BA4CFE6461AFA1004C52F19C8F2169DC`
SHA1 | `AB8539EF6B2A93FF9589DEC4B34A0257B6296C92`
SHA256 | `E86870769EE6C797E09457BD99C58D9BF2303CF0193A24EF9B1222C2C3DAF628`
SHA384 | `0517170E5A7C8135A8E6B2B2821A5E1BFDEAFEF0065929BAA6FF8DD13960EF8E0398C0FD3DCCB8A24BE4F48213F98242`
SHA512 | `2C5190D7609767237311260F241C619B82434CA640F396BB9710D356286844F82F320F9E05525A38707F2A52977790C0C3E2A217B36A7F0095A87C138B939AF0`
SSDEEP | `1536:l5gC0wSKok6UAeVEBFgvozLmwCedFpQHI8PXjYlTx/2whBGE/5K5/EJD2VEUcO8h:sC+vEArBCgmejo8X/2whRJDAE2r+e`
IMP | `D4D98ACF3243E0C97C83C6548571A44E`
PESHA1 | `33DD6986DD0D2706E0B2762EAC864A275EDB0EBF`
PE256 | `59E66176A13D0537E6DF321BEE2BBD205D958494F62B3B5D561404D7513CF4D1`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\RuntimeBroker.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/e86870769ee6c797e09457bd99c58d9bf2303cf0193a24ef9b1222c2c3daf628/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\RuntimeBroker.exe](RuntimeBroker.exe-42CB264897445970C7FBE4C60AC74987.md) | 35

## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\runtimebroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


