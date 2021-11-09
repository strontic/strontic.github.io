---
title: RuntimeBroker.exe | Runtime Broker
excerpt: What is RuntimeBroker.exe?
---

# RuntimeBroker.exe 

* File Path: `C:\WINDOWS\system32\RuntimeBroker.exe`
* Description: Runtime Broker

## Hashes

Type | Hash
-- | --
MD5 | `B2050C10311377B83B278E9514D7FDFA`
SHA1 | `34F7FD750777DD86485E9FCA0EE6E7B648036CEB`
SHA256 | `032233B9EFFCAF9A5446687FF76885CE2F69C89A277FD3BEF36C3ABE763F29E9`
SHA384 | `DE82C02FC3032C55938D21ED70A4BED2063F0E25997C64F17592B0BEBDAB1972E45BE2FC66DA77A8D04BB650F5004561`
SHA512 | `DF9481DFB45790D84F7EF868334C30BE33C1887B60439C77F30EFAAD28DFD8414CC08A87A85C33809718BC69749CABE0E65EFBB173F48CEC82C8A451EB68EC9F`
SSDEEP | `1536:157mJ2Oj4oFbSQCYwh0aw0ckaWO22u3E53NLyX7Winj3fGdddQhddd2ddsRyP/M6:1ZhOjJo0awXk6+EviTfu/MdSCe2W/9`
IMP | `3F4BB1A7349681128ED3F6B00184F43C`
PESHA1 | `494FDF21500A63521C24887CCF8DC8E0C10A1FCA`
PE256 | `57AD7AB7CB184A408C9DE0EDD99088EBDFBC4A6182286C7C2D4E0998D75BB938`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\RuntimeBroker.exe |
C:\WINDOWS\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/032233b9effcaf9a5446687ff76885ce2f69c89a277fd3bef36c3abe763f29e9/detection


## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\runtimebroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


