---
title: tttracer.exe | Time Travel Debugging Tracer Tool
excerpt: What is tttracer.exe?
---

# tttracer.exe 

* File Path: `C:\Windows\SysWOW64\tttracer.exe`
* Description: Time Travel Debugging Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `97579953AD08B01659EFE70976BE33E3`
SHA1 | `37B8D100CE1CDAF17D53ECDA65F9E53EF8A56FEA`
SHA256 | `A766076806B2610CBEC325A886EDA7352DA83703F6F4C623C2F58E0706C499A9`
SHA384 | `B0A70B65CC20251254E64094A334732FA79C31C58C30D8E2EA9BECB44E9EEC713E88DCEF5C52DDE2CC12F49F3870D595`
SHA512 | `2E9AEEDE53937E3AEC02E637A6E836DF89122734E4A4F54B7FC72B1418C57FD68E36C58B52E4F856E9361237CFA2A74D96CE208F3C71DE07D63D88DC0BB8D7F0`
SSDEEP | `1536:K7mDABjM2yEUJFMagRHKizRsk9nbGmESQujczJe8s4TIe8FPhg:5sFM2yBgaqxzRMVSQujkTA2`
IMP | `F60B40636A512BD0BFE6ECF41CF49CBB`
PESHA1 | `979A9D4B7E32760E143CD39933620EAC7BBEAD8F`
PE256 | `345FEDF92E3052350C8C5C074344A5B38CD5B5200A49C9C1F5435AB60812A730`

## Runtime Data

### Usage (stdout):
```cmhg
MICROSOFT TIME TRAVEL DEBUGGING (TTD)

Time Travel Debugging (TTD) command line utility is not meant for use in custom software or
automation. TTD is included with this version of Windows to improve diagnostics gathering and is not
intended for direct use as a stand-alone solution.

DISCLAIMER OF WARRANTY. THE SOFTWARE IS LICENSED "AS IS." YOU BEAR THE RISK OF USING IT. MICROSOFT
GIVES NO EXPRESS WARRANTIES, GUARANTEES, OR CONDITIONS. TO THE EXTENT PERMITTED UNDER APPLICABLE LAWS,
MICROSOFT EXCLUDES ALL IMPLIED WARRANTIES, INCLUDING MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE,
AND NON-INFRINGEMENT.

1. DATA COLLECTION. The software may collect information about you and your use of the software and send
   that to Microsoft. Microsoft may use this information to provide services and improve Microsoft's
   products and services. Your opt-out rights, if any, are described in the product documentation. Some
   features in the software may enable collection of data from users of your applications that access or
   use the software. If you use these features to enable data collection in your applications, you must
   comply with applicable law, including getting any required user consent, and maintain a prominent
   privacy policy that accurately informs users about how you use, collect, and share their data. You can
   learn more about Microsoft's data collection and use in the product documentation and the Microsoft
   Privacy Statement at https://go.microsoft.com/fwlink/?LinkId=521839. You agree to comply with all
   applicable provisions of the Microsoft Privacy Statement.

2. SCOPE OF LICENSE. The software is licensed, not sold. Microsoft reserves all other rights. Unless
   applicable law gives you more rights despite this limitation, you will not (and have no right to):
    a) work around any technical limitations in the software that only allow you to use it in certain ways;
    b) reverse engineer, decompile or disassemble the software;
    c) remove, minimize, block, or modify any notices of Microsoft or its suppliers in the software;
    d) use the software for commercial, non-profit, or revenue-generating activities;
    e) use the software in any way that is against the law or to create or propagate malware; or
    f) share, publish, distribute, or lend the software, provide the software as a stand-alone hosted
       solution for others to use, or transfer the software or this agreement to any third party.

3. SUPPORT SERVICES. Microsoft is not obligated under this agreement to provide any support services
   for the software. Any support provided is "as is", "with all faults", and without warranty of any kind.


```

### Usage (stderr):
```cmhg
Error:  Unrecognized command line option '--help' (Error Code 0x80070057:  The parameter is incorrect.)

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tttracer.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TTTracer.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a766076806b2610cbec325a886eda7352da83703f6f4c623c2f58e0706c499a9/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\tttracer.exe](tttracer.exe-61C47B71A25302934A8CFB16E3B4DBD9.md) | 36
[C:\Windows\system32\tttracer.exe](tttracer.exe-F716498E51219F64BFB4AFABAB44A796.md) | 41
[C:\Windows\SysWOW64\tttracer.exe](tttracer.exe-AAF4C8B847ADDA45EDB38E2768772E8D.md) | 50

## Possible Misuse

*The following table contains possible examples of `tttracer.exe` being misused. While `tttracer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_tttracer_mod_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/process_creation_tttracer_mod_load.yml) | `description: Detects usage of Time Travel Debugging Utility. Adversaries can execute malicious processes and dump processes, such as lsass.exe, via tttracer.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_tttracer_mod_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/process_creation_tttracer_mod_load.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Tttracer/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_tttracer_mod_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/process_creation_tttracer_mod_load.yml) | `ParentImage\|endswith: '\tttracer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_tttracer_mod_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_tttracer_mod_load.yml) | `description: Detects usage of Time Travel Debugging Utility. Adversaries can execute malicious processes and dump processes, such as lsass.exe, via tttracer.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_tttracer_mod_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_tttracer_mod_load.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Tttracer/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Description: Used by Windows 1809 and newer to Debug Time Travel (Underlying call of tttracer.exe)`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `Name: Tttracer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `- Command: tttracer.exe C:\windows\system32\calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `Description: Execute calc using tttracer.exe. Requires administrator privileges`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `- Command: TTTracer.exe -dumpFull -attach pid`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `Description: Dumps process using tttracer.exe. Requires administrator privileges`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `- Path: C:\Windows\System32\tttracer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `- Path: C:\Windows\SysWOW64\tttracer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `- IOC: Parent child relationship. Tttracer parent for executed command`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


