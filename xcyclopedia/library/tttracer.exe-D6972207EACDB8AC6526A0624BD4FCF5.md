---
title: tttracer.exe | Time Travel Tracing Tracer Tool
---

# tttracer.exe 

* File Path: `C:\Windows\SysWOW64\tttracer.exe`
* Description: Time Travel Tracing Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `D6972207EACDB8AC6526A0624BD4FCF5`
SHA1 | `EE8324C6932F1A52A74CA6B62DB0D19BD5E78211`
SHA256 | `F501B18D8270CE7802E724C84D1EBA5C5D77ADB9113739605FB45E302EDF9C4C`
SHA384 | `5C2AA92C40DAB06E2D0F5F25D08250BFEF78CF4ECA71774DA85EA202D97F74278E1CDC6B14615245C2E015B63ABB120C`
SHA512 | `B9289CED19CEB996E8B6CD987FC12F725F2A9E74EF68207368FCD6030AAE793B2FAB17BD0B72E04875C866DD2A3C7CDC646815E12B70FD808524370D7A40A872`
SSDEEP | `3072:NqmrA6A5XVO/DNT/J7rnOoXAlXZ3ptkeuOwinfX9EJTJx4VniXOFZ9nkTvcx8MxB:AmrR0XVOhTBNwv3XkOYJHlOFZpevcx88`

## Runtime Data

### Usage (stdout):
```Batchfile
We have created EULA.TXT in the current folder. 
Please review this file before agreeing.
Have you read and do you accept the EULA? Y/N

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\Administrator\Documents | File
(RW-)   C:\Windows | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


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


## Possible Misuse

*The following table contains possible examples of `tttracer.exe` being misused. While `tttracer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Description: Used by Windows 1809 and newer to Debug Time Travel (Underlying call of tttracer.exe)` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `Name: Tttracer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Command: tttracer.exe C:\windows\system32\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `    Description: Execute calc using tttracer.exe. Requires administrator privileges` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Command: TTTracer.exe -dumpFull -attach pid` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `    Description: Dumps process using tttracer.exe. Requires administrator privileges` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Path: C:\Windows\System32\tttracer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Path: C:\Windows\SysWOW64\tttracer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | ` - IOC: Parent child relationship. Tttracer parent for executed command` | 



MIT License. Copyright (c) 2020 Strontic.


