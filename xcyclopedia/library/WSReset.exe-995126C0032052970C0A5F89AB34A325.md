---
title: WSReset.exe | This tool resets the Windows Store without changing account settings or deleting installed apps
excerpt: What is WSReset.exe?
---

# WSReset.exe 

* File Path: `C:\WINDOWS\system32\WSReset.exe`
* Description: This tool resets the Windows Store without changing account settings or deleting installed apps

## Hashes

Type | Hash
-- | --
MD5 | `995126C0032052970C0A5F89AB34A325`
SHA1 | `E1E6481CDC1487BD620FE3E2B1019C26D2F70CD4`
SHA256 | `0EDD534686643B1770D6897EAB387B9D2A82FC57593ADA049F1DC807FE792253`
SHA384 | `3A91401FA18780764CCFAB84792BB9C27CC547444D2E4C2C48330F79F7FE9056062F43AA6A97C32B3B11C5BDE5C5AE43`
SHA512 | `9682B08434A1EE77B1FBD368978861E2C5135F121569F4432481D8E9C793E96477F01AAE3629113EC05C6678CCDDD07795B1A4B70D950C9AB5FAFF6C125B6634`
SSDEEP | `768:I/YIv7YzH5FVHnwgdie0+yYqN1Nsn4FOBkStBWo:mYIkbHVHn58VNGg0Yo`
IMP | `AB03184F9306BF7E8482C6F987BA1832`
PESHA1 | `9B6275F3071E0BBE9495AD4F2A5D0B72B55190E0`
PE256 | `A3037D8776C84176FAABC039C1C2B289EA63784D037ADA00F57A34FB7FAAAB47`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\WSReset.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WSReset.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/0edd534686643b1770d6897eab387b9d2a82fc57593ada049f1dc807fe792253/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\WSCollect.exe](WSCollect.exe-11836752B88DD693C66A643BE973AA93.md) | 38
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-1C4F7AB2AD0B867487E42F77A637A3F2.md) | 44
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-4F67D9A480038D06463A43AE66880245.md) | 43
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-6212500CE0BBE755AFCC8DDF64698A87.md) | 40
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-74352E0225658E9AAE9A0D7AB4BF3885.md) | 47
[C:\WINDOWS\system32\WSCollect.exe](WSCollect.exe-C471046B92D04242ED85AB1522E90012.md) | 40
[C:\Windows\system32\WSReset.exe](WSReset.exe-0D2BE4AE7AE5B93B47E12F4EFF38A0D7.md) | 47
[C:\Windows\system32\WSReset.exe](WSReset.exe-374AB8022CA5EE56684BC28626F36F73.md) | 47
[C:\Windows\system32\WSReset.exe](WSReset.exe-5E3561D98BD5FB1D20098FAA0384FAA8.md) | 43
[C:\Windows\system32\WSReset.exe](WSReset.exe-C08D9492A11813196000AF9E4F5EE23F.md) | 40
[C:\WINDOWS\system32\WSReset.exe](WSReset.exe-FB3CE16149961934341850A6F1ED869E.md) | 47

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


