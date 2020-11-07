---
title: spoolsv.exe | Spooler SubSystem App
excerpt: What is spoolsv.exe?
---

# spoolsv.exe 

* File Path: `C:\Windows\system32\spoolsv.exe`
* Description: Spooler SubSystem App

## Hashes

Type | Hash
-- | --
MD5 | `C98A3A0395AE60D108CBED7ACEBC0531`
SHA1 | `76931B75A68EEBFF58FC38A1C8D40159E98DB54A`
SHA256 | `00AC7E58DFC2F6757C0C2268EB441E4E8FB317427840971A1049011CD2888A35`
SHA384 | `25A7CBC8ECC5D5145BC2B2893C6C590EAC71306FC060A44A6D8E542ADCF9B311685C089A6CEEC054189C4CA3DB9C3582`
SHA512 | `A06123C622EFCDCE4934E83B56280273AB029E0D094DA273A1404301A7CC685C031600B145AE5CAD6659250879F0D5FD60740A1CBFA414554101F205996C26A6`
SSDEEP | `24576:7uhB4Q43JLDzWBYnuesJLK27QDndkYQQZsU9ocTwSb105K:7u74n3JLDzWBYnuesJLK27QDndkYQQZV`
IMP | `6D527F52CF7772DC1BF45147E1BD0544`
PESHA1 | `8050CB6D401955725C6B4775EB4471F6CB3A6E4F`
PE256 | `63D9053CC4354C4EFA3F3349530B72748DD61125E99BF213484C9675C679D954`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\DNSAPI.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\spoolsv.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: spoolsv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/00ac7e58dfc2f6757c0c2268eb441e4e8fb317427840971a1049011cd2888a35/detection


## Possible Misuse

*The following table contains possible examples of `spoolsv.exe` being misused. While `spoolsv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\spoolsv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\spoolsv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\spoolsv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | This technique was used by WannaCry. Upon execution, if the spoolsv service was running "SUCCESS: The process "spoolsv.exe" with PID 2316 has been terminated." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | will be displayed. If the service was not running "ERROR: The process "spoolsv.exe" not found." will be displayed and it can be | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | \| process_name \| Name of a process to kill \| String \| spoolsv.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


