---
title: cmdl32.exe | Microsoft Connection Manager Auto-Download
excerpt: What is cmdl32.exe?
---

# cmdl32.exe 

* File Path: `C:\WINDOWS\SysWOW64\cmdl32.exe`
* Description: Microsoft Connection Manager Auto-Download

## Hashes

Type | Hash
-- | --
MD5 | `1AB5C8141C1891465EFDE8F31B851BA2`
SHA1 | `B33337C5D3410AA1C72BE3D7F24EEF895A8ED475`
SHA256 | `498280E4610458825C48DAA24811D0D326C6C227C50B6B3005A17946E8ACC811`
SHA384 | `703CD4517D0FFB45ABAF753AE6E5FBA97A91B0131ADC5169C7FF208ABCBAD35F114BD20653D6B329CB43CA45FE97FC22`
SHA512 | `AAB4F76C84774CF09CDE000748E8E4234362EB28320A97A66E43FDE39DB5BA8DF49DB1499954E2A704749D70E0C0259813ECE0315D8AC655CA6142285FE58935`
SSDEEP | `768:cbzqH1EiGeKtl9dHNw/9cT3ztdihtu7tScyzIR3dIGdpAT:uz+1EheKtfh3zvv3dIGc`
IMP | `F9E3C82E9C985DDB248100C9AD9C8921`
PESHA1 | `8D61500BB265D6407997A529C3DDF5DCB79C0BC0`
PE256 | `1D998F1AD876CEC45DD7E48068FBED4FE9D71BD1319E6335E5153787C49A57A5`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\cmdl32.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CMDL32.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.22000.1 (WinBuild.160101.0800)
* Product Version: 7.2.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/498280e4610458825c48daa24811d0d326c6c227c50b6b3005a17946e8acc811/detection


## Possible Misuse

*The following table contains possible examples of `cmdl32.exe` being misused. While `cmdl32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `title: Suspicious Cmdl32 Execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `description: lolbas Cmdl32 is use to download a payload to evade antivirus`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Cmdl32/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `cmdl32:`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `- Image\|endswith: '\cmdl32.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `- OriginalFileName: CMDL32.EXE`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `condition: cmdl32 and options`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `Name: cmdl32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `- Command: cmdl32 /vpn /lan %cd%\config`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `- Path: C:\Windows\System32\cmdl32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `- Path: C:\Windows\SysWOW64\cmdl32.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


