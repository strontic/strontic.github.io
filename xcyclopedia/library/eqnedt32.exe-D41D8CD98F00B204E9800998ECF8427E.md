﻿---
title: eqnedt32.exe | 
excerpt: What is eqnedt32.exe?
---

# eqnedt32.exe 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX86\Microsoft Shared\EQUATION\eqnedt32.exe`

## Hashes

Type | Hash
-- | --
MD5 | `D41D8CD98F00B204E9800998ECF8427E`
SHA1 | `DA39A3EE5E6B4B0D3255BFEF95601890AFD80709`
SHA256 | `E3B0C44298FC1C149AFBF4C8996FB92427AE41E4649B934CA495991B7852B855`
SHA384 | `38B060A751AC96384CD9327EB1B1E36A21FDB71114BE07434C0CC7BF63F6E1DA274EDEBFE76F65FBD51AD2F14898B95B`
SHA512 | `CF83E1357EEFB8BDF1542850D66D8007D620E4050B5715DC83F4A921D36CE9CE47D0D13C5D85F2B0FF8318D2877EEC2F63B931BD47417A81A538327AF927DA3E`
SSDEEP | `3::`

## Signature

* Status: The form specified for the subject is not one supported or known by the specified trust provider
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/60
* VirusTotal Link: https://www.virustotal.com/gui/file/e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855/detection/


## Possible Misuse

*The following table contains possible examples of `eqnedt32.exe` being misused. While `eqnedt32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_11882.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_11882.yml) | `description: Detects exploits that use CVE-2017-11882 to start EQNEDT32.EXE and other sub processes like mshta.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_11882.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_11882.yml) | `ParentImage\|endswith: '\EQNEDT32.EXE'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\EQNEDT32.EXE'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


