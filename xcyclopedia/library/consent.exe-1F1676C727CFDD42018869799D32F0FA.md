---
title: consent.exe | Consent UI for administrative applications
excerpt: What is consent.exe?
---

# consent.exe 

* File Path: `C:\WINDOWS\system32\consent.exe`
* Description: Consent UI for administrative applications

## Hashes

Type | Hash
-- | --
MD5 | `1F1676C727CFDD42018869799D32F0FA`
SHA1 | `93D8D66D80A83431BDDCCFF86E3B9FBE42B37156`
SHA256 | `AECFB06F61D2A6C697B469C9D3EE61972BBCEDD30DED294828B88D6F95B86BB8`
SHA384 | `BD6B09EA6AE99B3A9D58A8EA2CE34AF082896699F283814936B2E53593FB6774DFB93A463C75616F95B86FE7AF3305AB`
SHA512 | `2AFFFFEEC872ADBB6B58C8941276D105A90EB50A17A427A4DB4638F823738C19A7AE62F4F86A7819BB70C185886ECDE85C9AD06B8DB075C887251B92142CE3C1`
SSDEEP | `3072:KZ4VpHIJvo2h7zJ8XNsyMZd0pbAX5LClWQDybBGzFrHv:VSJw2h7zJ8XNFMZd0Sleyb4zJP`
IMP | `8CA7AFB40D5BE5A4055E722819EEF43D`
PESHA1 | `96D1DEC3DE27B4CF60F882730F9CF95CC8EB9A18`
PE256 | `D29FA13536BABB465C9CC8C68DD5436E5BBAF6B7527AC7EFD263152440E06884`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\consent.exe |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: consent.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/aecfb06f61d2a6c697b469c9d3ee61972bbcedd30ded294828b88d6f95b86bb8/detection


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


