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
MD5 | `CD38B65FBFF35E1D3E307DD70F1D2E99`
SHA1 | `76BACAE59C84BAE5323E6B3404DD9C53F7AB2D36`
SHA256 | `842EEE57AEC0D8FF489079EB086B091AF253B10F74E9CF344CF0DAEB6A838946`
SHA384 | `4EA84B23958E2713833F669C184CEB8E76382D3B0305D03C3DCA2550A535F6503C1A05C5332EBDBD90F135601DF7C720`
SHA512 | `5E25A86BEBA0C1DF92AD72672DADDCE4084397E72A93D3503DE81F31828E62569504B9FF80623189D695742F9BF3B35BEE84A3F058E58E913169CA3032E655F8`
SSDEEP | `768:KTqHPEiucKtfeXiBWts4v5s5OI5r5kP7Jtj7Zq26JCOcdsnIbcC:KT+PEJcKtfeyq0TknjLSnIbZ`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CMDL32.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.18362.1 (WinBuild.160101.0800)
* Product Version: 7.2.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\SysWOW64\cmdl32.exe](cmdl32.exe-421B1E635E43A97F98FE7E1A8B612CAA.md) | 33
[C:\Windows\SysWOW64\cmdl32.exe](cmdl32.exe-5C354F6BA0DF7D01B2CB5CF08140B67E.md) | 44
[C:\Windows\SysWOW64\cmdl32.exe](cmdl32.exe-87390E37E36622B054D4BDCBB7997B6C.md) | 43
[C:\Windows\SysWOW64\cmdl32.exe](cmdl32.exe-BD60DF43E6419AFE39B3FCBFB14077E7.md) | 50

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


