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
MD5 | `3FC10273D5BBB7B06A76FD5E78D91469`
SHA1 | `D500C5892411CC6DCDAB2EBBAA54FC40E3785B0B`
SHA256 | `1E35BB9770AE8202BD6D2E5FDA6784A80F67DCF4B547B206A14D82CC17154842`
SHA384 | `00AB59A1C15536A4583E89B92ABA0A922BA84484B923402AE997B8A9D80C7C5000C73B62CD306DC24374223518382B03`
SHA512 | `F1B15C780442101F3DFDD19AE6B1A22A70BA5903BCFCC9297A6577A21E17E1DDFCB3D8B5B3D498776AD6ED75968CF16886E270CFD7EBF68F92C7301A10085835`
SSDEEP | `49152:GcYVj023jhdZVTL3bBPZziAnrRfOqI/TYhUEgPk/Cx/mNDS8r37Un:qdHvNlr37`
IMP | `6DFBF12753AF176E3C203C407493A5B9`
PESHA1 | `6ABDEBC739E92D45F13C342703494724F516463B`
PE256 | `3B310D0ED16B4400FFCED1EA162162E9E0C5342A056C123B90E9D22A3A1B824E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\smartscreen.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/1e35bb9770ae8202bd6d2e5fda6784a80f67dcf4b547b206a14d82cc17154842/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\smartscreen.exe](smartscreen.exe-B75FA41284409A6134BF824BEAE59B4E.md) | 50

## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


