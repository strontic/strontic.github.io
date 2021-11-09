---
title: WinSAT.exe | Windows System Assessment Tool
excerpt: What is WinSAT.exe?
---

# WinSAT.exe 

* File Path: `C:\WINDOWS\system32\WinSAT.exe`
* Description: Windows System Assessment Tool

## Hashes

Type | Hash
-- | --
MD5 | `ED2505CC79AB0C0008E1A23A731D9107`
SHA1 | `1281BBC227D3C66226FEA0B8BFFDB93C6614F2E2`
SHA256 | `E75D84511E577234FC62BF43894DB0F3995DC06DAC2148722B9C9A81F9C182FF`
SHA384 | `E2527EA64ADD3E5E6CABFFBE842C4396EFB7B1D6F82AE1DD15F5A7C53506F8CB00167175AFC10E1E17688A0769690634`
SHA512 | `462EF9CB9E3AE8C6D946C97DDFBA421EB0737874AB65C2643024411BC72C2E16F07EF777239536C4CE58700AD251FDC779BAD34D42E0755675451F46EF690725`
SSDEEP | `49152:mOpNQ6QTvumPeAGU1FVA7PsYmq1dKwdfU2bECbe:9NDF1DFE/`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WinSAT.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WinSAT.exe](WinSAT.exe-6654FC269DF21AA165842E479678A94B.md) | 47
[C:\Windows\system32\WinSAT.exe](WinSAT.exe-715DB53A8064C6DECCF68B7501DF3386.md) | 47
[C:\Windows\system32\WinSAT.exe](WinSAT.exe-D21AA5C451C43D15B2BA3611F57F2321.md) | 50
[C:\WINDOWS\system32\WinSAT.exe](WinSAT.exe-E278C34857373A1355D6453555E29CE0.md) | 46
[C:\Windows\system32\WinSAT.exe](WinSAT.exe-FC2414F108B613366BDE7AE897AB53A1.md) | 50

## Possible Misuse

*The following table contains possible examples of `WinSAT.exe` being misused. While `WinSAT.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_uac_bypass_winsat.yml) | `title: UAC Bypass Abusing Winsat Path Parsing - File`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [file_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_uac_bypass_winsat.yml) | `description: Detects the pattern of UAC Bypass using a path parsing issue in winsat.exe (UACMe 52)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [file_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_uac_bypass_winsat.yml) | `- '\AppData\Local\Temp\system32\winsat.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_winsat.yml) | `title: UAC Bypass Abusing Winsat Path Parsing - Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_winsat.yml) | `description: Detects the pattern of UAC Bypass using a path parsing issue in winsat.exe (UACMe 52)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_winsat.yml) | `ParentImage\|endswith: '\AppData\Local\Temp\system32\winsat.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_winsat.yml) | `ParentCommandLine\|contains: 'C:\Windows \system32\winsat.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_uac_bypass_winsat.yml) | `title: UAC Bypass Abusing Winsat Path Parsing - Registry`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_uac_bypass_winsat.yml) | `description: Detects the pattern of UAC Bypass using a path parsing issue in winsat.exe (UACMe 52)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_uac_bypass_winsat.yml) | `TargetObject\|contains: '\Root\InventoryApplicationFile\winsat.exe\|'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_uac_bypass_winsat.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_uac_bypass_winsat.yml) | `Details\|endswith: '\appdata\local\temp\system32\winsat.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


