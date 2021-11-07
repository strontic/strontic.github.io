---
title: smartscreen.exe | Windows Defender SmartScreen
excerpt: What is smartscreen.exe?
---

# smartscreen.exe 

* File Path: `C:\Windows\system32\smartscreen.exe`
* Description: Windows Defender SmartScreen

## Hashes

Type | Hash
-- | --
MD5 | `521ED922765BCA8F79BD76188F879311`
SHA1 | `183E877F488F2DF9F304F60A42514A334720399F`
SHA256 | `9605680FC164ACB985C031ECA2C8BC4909CF8B749C571DB6DE2B0B2C204C2163`
SHA384 | `2DC97E509BDA626F819B531D03F8B50F927AC86969AD485E6EBEBEE649402F99153B976B266467EA610799C573F9A900`
SHA512 | `32DD68806A6FC16444E681D2F6BEA7799A6C5F0FB9E3CF3DF581176B0C015DBC1937B3720E9EFC9BA53EB09C0DF135B4033BF54E41618EC7521616452638F2D3`
SSDEEP | `49152:8FYYVj023JlFKu5s4OkJP+XAd0Sr5TsIjKHGP8j1/d8r37UnxNDu:8lFUbmr37eN6`
IMP | `6DFBF12753AF176E3C203C407493A5B9`
PESHA1 | `D081828A1CD7FCD3E009B82137ABBB3A412C645A`
PE256 | `3FD0088D4239BE353E1FE1115BDCF0F941876ABA5CF85B0E0ACA3959C8B5BFAC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\smartscreen.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smartscreen.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9605680fc164acb985c031eca2c8bc4909cf8b749c571db6de2b0b2c204c2163/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\smartscreen.exe](smartscreen.exe-6033F55F30364319ED5B7E1C6E6C9ED4.md) | 35
[C:\Windows\system32\smartscreen.exe](smartscreen.exe-B75FA41284409A6134BF824BEAE59B4E.md) | 44

## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1553.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1553.005/T1553.005.md) | <blockquote>Adversaries may abuse specific file formats to subvert Mark-of-the-Web (MOTW) controls. In Windows, when files are downloaded from the Internet, they are tagged with a hidden NTFS Alternate Data Stream (ADS) named <code>Zone.Identifier</code> with a specific value known as the MOTW.(Citation: Microsoft Zone.Identifier 2020) Files that are tagged with MOTW are protected and cannot perform certain actions. For example, starting in MS Office 10, if a MS Office file has the MOTW, it will open in Protected View. Executables tagged with the MOTW will be processed by Windows Defender SmartScreen that compares files with an allowlist of well-known executables. If the file in not known/trusted, SmartScreen will prevent the execution and warn the user not to run it.(Citation: Beek Use of VHD Dec 2020)(Citation: Outflank MotW 2020)(Citation: Intezer Russian APT Dec 2020) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


