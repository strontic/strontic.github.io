﻿---
title: tttracer.exe | Time Travel Tracing Tracer Tool
excerpt: What is tttracer.exe?
---

# tttracer.exe 

* File Path: `C:\Windows\system32\tttracer.exe`
* Description: Time Travel Tracing Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `9EAFF78CE415BC5475FC24C1B86FB0D5`
SHA1 | `275D7657F35575291C7A18C01FD964C97C377C65`
SHA256 | `4D94208E7D497B5BEDD481263FEA903C9CD66962A5DBA9F5353CCA15FAF0D9FD`
SHA384 | `0A305E8279170F3D67CFCC4E9A5941C928A0628F8C6BE3A03C12767001DB7A287C8438B061F02465D6A09A91D4479752`
SHA512 | `4C1D73D136DE4B57CD3E0F6CAB14B13E26375279D1BB51C0641BE23E9A9B063B50F8FDB29B0F1066255A50113CBA86EF3E4D5EBDAB61AC63B986D12198CA3216`
SSDEEP | `6144:zRe4oPhepmdFB47+E1q9pyMFOIDixHmev9:g4oP0mcWHRiJm29`
IMP | `2DD7AC615E10A236D551AAFD2B7BB0B7`
PESHA1 | `859DC01FD5EA1329D7FC4E112B9B271556B009E2`
PE256 | `77E3A77906B506DD41C963F003A97DD8CB0EEB88AA779A23D4158626F28856AF`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) TTTracer 1.01.03
Release: 10.0.17763.1
Copyright (C) Microsoft Corporation. All rights reserved.


```

### Usage (stderr):
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

### Child Processes:
conhost.exe help.exe ttdinject.exe

### Open Handles:

Path | Type
-- | --
(---)   C:\Users\user\help01.out | File
(RW-)   C:\Users\user | File
(RWD)   C:\Users\user\help01.run | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\ttdSeq_s_2_01_03 | Section
\Sessions\2\BaseNamedObjects\ttd_s_2_01_03_1164 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tttracer.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TTTracer.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/4d94208e7d497b5bedd481263fea903c9cd66962a5dba9f5353cca15faf0d9fd/detection/


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


