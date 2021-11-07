---
title: consent.exe | Consent UI for administrative applications
excerpt: What is consent.exe?
---

# consent.exe 

* File Path: `C:\Windows\system32\consent.exe`
* Description: Consent UI for administrative applications

## Hashes

Type | Hash
-- | --
MD5 | `6646631CE4AD7128762352DA81F3B030`
SHA1 | `1095BD4B63360FC2968D75622AA745E5523428AB`
SHA256 | `56B2D516376328129132B815E22379AE8E7176825F059C9374A33CC844482E64`
SHA384 | `EAFC167CB07BC87A80ED4A1B5FB74F96F34EE4C6487CF4FF9600331D1E3E80E098056B637D0156809E258A1AF8C4C681`
SHA512 | `1C00ED5D8568F6EBD119524B61573CFE71CA828BD8FBDD150158EC8B5DB65FA066908D120D201FCE6222707BCB78E0C1151B82FDC1DCCF3ADA867CB810FEB6DA`
SSDEEP | `1536:XS8vuaYDLPADsydN+zs/EIT9+N08HlCUtWDxbKFc8984AB6QBnW8q5i8NVm+dBO6:i8maBis7i0ACD1bKBzUkBORyxIzYP1r`
IMP | `ACAFC223D6C3FCAE537D9630A0021EFD`
PESHA1 | `1335607FDBD7DD4D3F8A6EFC227E0553473F6717`
PE256 | `4E28A66F9E6E93AF9B32518EBA6E936FBAEF80BACD881CFA1637D6649F572070`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\system32\consent.exe |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\SYSTEM32\samcli.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\SYSTEM32\SspiCli.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: consent.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/56b2d516376328129132b815e22379ae8e7176825f059c9374a33cc844482e64/detection


## Possible Misuse

*The following table contains possible examples of `consent.exe` being misused. While `consent.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_consent_comctl32.yml) | `title: UAC Bypass Using Consent and Comctl32 - File`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_consent_comctl32.yml) | `description: Detects the pattern of UAC Bypass using consent.exe and comctl32.dll (UACMe 22)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_consent_comctl32.yml) | `TargetFilename\|startswith: 'C:\Windows\System32\consent.exe.@'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_ieinstal.yml) | `TargetFilename\|endswith: 'consent.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `description: Detects an exploitation attempt in which the UAC consent dialogue is used to invoke an Internet Explorer process running as LOCAL_SYSTEM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `ParentImage\|endswith: '\consent.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_consent_comctl32.yml) | `title: UAC Bypass Using Consent and Comctl32 - Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_consent_comctl32.yml) | `description: Detects the pattern of UAC Bypass using consent.exe and comctl32.dll (UACMe 22)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_consent_comctl32.yml) | `ParentImage\|endswith: '\consent.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ieinstal.yml) | `Image\|endswith: 'consent.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | <blockquote>Adversaries may spoof the parent process identifier (PPID) of a new process to evade process-monitoring defenses or to elevate privileges. New processes are typically spawned directly from their parent, or calling, process unless explicitly specified. One way of explicitly assigning the PPID of a new process is via the <code>CreateProcess</code> API call, which supports a parameter that defines the PPID to use.(Citation: DidierStevens SelectMyParent Nov 2009) This functionality is used by Windows features such as User Account Control (UAC) to correctly set the PPID after a requested elevated process is spawned by SYSTEM (typically via <code>svchost.exe</code> or <code>consent.exe</code>) rather than the current user context.(Citation: Microsoft UAC Nov 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2015_5119.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2015_5119.yar) | yaraexchange = "No distribution without author's consent" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


