---
title: tttracer.exe | Time Travel Tracing Tracer Tool
excerpt: What is tttracer.exe?
---

# tttracer.exe 

* File Path: `C:\WINDOWS\system32\tttracer.exe`
* Description: Time Travel Tracing Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `5D419F7F98ABC0B3CF9E52D3598F587F`
SHA1 | `80018FD22CD3D4120F362121C8A59E87B7492EF0`
SHA256 | `9B3F44C3AA76AEA793EF3CF23401BF1C1E5DBE23932DC36F26C4BA2BB0187426`
SHA384 | `B11B450DA7C94633BF0E619C261D2E2E49A8F01A319BA0BDC05181838DA7E8B6A3969864F35AD60991ABA31586E5B595`
SHA512 | `EB00FF3DA21C4A9B19DEE75A1177CDF0E5164AF1882D5DE622A5081C3454C0088C250272E78A56FF2676D70C582CA40CB153FF053A1D797E1E3E6A43C39A61B9`
SSDEEP | `6144:LMjBOQRWbzF90BaZXMbACl4DH3IH5rNbbVdUK3KRSO+Qqm/QDGr5rITBevg:TTBZaACO4NB9KRLDWGqd2g`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) TTTracer 1.01.05
Release: 10.0.18362.1
Copyright (C) Microsoft Corporation. All rights reserved.


```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TTTracer.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


