﻿---
title: tttracer.exe | Time Travel Tracing Tracer Tool
excerpt: What is tttracer.exe?
---

# tttracer.exe 

* File Path: `C:\WINDOWS\SysWOW64\tttracer.exe`
* Description: Time Travel Tracing Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `A6C37CBB241AF38C2F6AF2BBF54A1DB2`
SHA1 | `9BB4A485B798B225040889914C3EBB842DB47425`
SHA256 | `CBAB0EDEF72829DD9897C33CD83B51846691DB4AE6617DEB48391F6BAA83D909`
SHA384 | `0BAC54F54CE28FB441EB32F8E468672BDD21717D5E5F5F0B428427D5C74E76CD940EC56980606BE639622E5112E5FBF4`
SHA512 | `80A0D9A99DBF8877C93EFE56E48128EE234EDCDE57C20952797820E836B8DCCCD56D2D41ACA8E1E313FD58965890621D6F019E7F3424BE2E766EE9E8D0799931`
SSDEEP | `6144:pcI29oqy82tSiiXXHZgS6/MtiwQSwGlPevt:l29ty82Ac/Og1G12t`

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


