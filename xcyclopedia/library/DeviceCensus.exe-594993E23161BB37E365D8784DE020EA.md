﻿---
title: DeviceCensus.exe | Device Census
excerpt: What is DeviceCensus.exe?
---

# DeviceCensus.exe 

* File Path: `C:\Windows\system32\DeviceCensus.exe`
* Description: Device Census

## Hashes

Type | Hash
-- | --
MD5 | `594993E23161BB37E365D8784DE020EA`
SHA1 | `72B068446C47C606A257E6BFC43EDD3BE211F2DA`
SHA256 | `D26DEFA5D3E01EAC5E4CCADD9BA79F21C6B044EB2381642043A1BE34B14C0599`
SHA384 | `882D57486B73504764362C152CD861601283E793B7B80D57DF7AF9A2C6D38599B25791824FFFE0B57D7C6CB37F763362`
SHA512 | `3130A62B76DA644A1142F26A4B8FC1644E0F74A6903194296C9E6278D63DC1CB9BA9361E6F3406AF8E209E5D73E80613285BDD70BE1C6CBBA0EFAB8C9D44CA57`
SSDEEP | `768:g6RydRhNvtP2x3zmCil09N8kdyXXdauXXNI1PRCy:LRy3DFELi+v5cXXcEXKPJ`
IMP | `C0994637A5C4AC857D13AC9D826088E3`
PESHA1 | `31877796CBF4108A25121F86C27BA7735599A104`
PE256 | `B9937EB0B38FC9AAAB30D0FDBC1027A673390C6380E0AF96A626E61F113A354D`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\DeviceCensus.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d26defa5d3e01eac5e4ccadd9ba79f21c6b044eb2381642043a1be34b14c0599/detection/


## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\DeviceCensus.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_win_reg_telemetry_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_win_reg_telemetry_persistence.yml) | `- '\system32\DeviceCensus.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


