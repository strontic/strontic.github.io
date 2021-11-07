---
title: WSReset.exe | This tool resets the Windows Store without changing account settings or deleting installed apps
excerpt: What is WSReset.exe?
---

# WSReset.exe 

* File Path: `C:\Windows\system32\WSReset.exe`
* Description: This tool resets the Windows Store without changing account settings or deleting installed apps

## Hashes

Type | Hash
-- | --
MD5 | `374AB8022CA5EE56684BC28626F36F73`
SHA1 | `DCEE9A0D93C86B79E93D13421C24CF1D71C3EA26`
SHA256 | `BF90ECD7CEA6870A9EF6E8CC818C993F0904CC89CB5CE8E8843972B26F05B29E`
SHA384 | `4604365CB7AA28B1C0E5368D4A4BF09E8529C7DF4BC6BA9F0E4E589D9A98EA80D8D87BEF98E513E4113ADF2E28252A53`
SHA512 | `9A0313C63635467A3EFB997FF3EA07576CC3FC245165099F5DC7A1CC9DD8A5890B3BA8E6C1F95DA1C69DBE3A13975BF820890BF5CB93343F5C467E2C7D5F7AEC`
SSDEEP | `768:8YcyPDMz6IlkiK7sOq5+TGRNsn4FOBkStBWg:pjOlisOq5z6g0Yg`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WSReset.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-1C4F7AB2AD0B867487E42F77A637A3F2.md) | 43
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-4F67D9A480038D06463A43AE66880245.md) | 44
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-6212500CE0BBE755AFCC8DDF64698A87.md) | 41
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-74352E0225658E9AAE9A0D7AB4BF3885.md) | 44
[C:\WINDOWS\system32\WSCollect.exe](WSCollect.exe-C471046B92D04242ED85AB1522E90012.md) | 41
[C:\Windows\system32\WSReset.exe](WSReset.exe-0D2BE4AE7AE5B93B47E12F4EFF38A0D7.md) | 44
[C:\Windows\system32\WSReset.exe](WSReset.exe-5E3561D98BD5FB1D20098FAA0384FAA8.md) | 44
[C:\Windows\system32\WSReset.exe](WSReset.exe-C08D9492A11813196000AF9E4F5EE23F.md) | 38
[C:\WINDOWS\system32\WSReset.exe](WSReset.exe-FB3CE16149961934341850A6F1ED869E.md) | 43

## Possible Misuse

*The following table contains possible examples of `WSReset.exe` being misused. While `WSReset.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_wsreset.yml) | `title: UAC Bypass WSReset`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_wsreset.yml) | `description: Detects the pattern of UAC Bypass via WSReset usable by default sysmon-config`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_wsreset.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Wsreset/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_wsreset.yml) | `Image\|endswith: '\wsreset.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `title: Bypass UAC via WSReset.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `description: Identifies use of WSReset.exe to bypass User Account Control. Adversaries use this technique to execute privileged processes.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `ParentImage\|endswith: '\wsreset.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `title: Wsreset UAC Bypass`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `description: Detects a method that uses Wsreset.exe tool that can be used to reset the Windows Store to bypass UAC`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Wsreset/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `- '\WSreset.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `- Unknown sub processes of Wsreset.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_bypass_via_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_bypass_via_wsreset.yml) | `title: UAC Bypass Via Wsreset`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_bypass_via_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_bypass_via_wsreset.yml) | `description: Unfixed method for UAC bypass from windows 10. WSReset.exe file associated with the Windows Store. It will run a binary file contained in a low-privilege registry.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_bypass_via_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_bypass_via_wsreset.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Wsreset`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `Name: Wsreset.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `- Command: wsreset.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `Description: During startup, wsreset.exe checks the registry value HKCU\Software\Classes\AppX82a6gwre4fdg3bt635tn5ctqjf8msdd2\Shell\open\command for the command to run. Binary will be executed as a high-integrity process without a UAC prompt being displayed to the user.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `- Path: C:\Windows\System32\wsreset.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `- IOC: wsreset.exe launching child process other than mmc.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\WSReset.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


