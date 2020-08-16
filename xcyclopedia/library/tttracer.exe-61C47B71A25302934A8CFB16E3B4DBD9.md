---
title: tttracer.exe | Time Travel Debugging Tracer Tool
---

# tttracer.exe 

* File Path: `C:\Windows\system32\tttracer.exe`
* Description: Time Travel Debugging Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `61C47B71A25302934A8CFB16E3B4DBD9`
SHA1 | `FCC75A413069B1579868FB0026099FAA5BE358C3`
SHA256 | `B2A6E526499F552C2C9AE920DD7B6722B0D49B862950B5740033A8764F66E9D2`
SHA384 | `523DC88B240766DFA2114189737C690FBD6FFF848B628CB1F7455DF886FE2D21764C903A480CA479F317E7B534B00078`
SHA512 | `13A5B22762D47D08CC76E556AC30C6FC2EFB7744EB94487EC27D7195F3CFAB33A1D0C48DF005236BD7A3B84255B7B379A91B6B3343276ACF4DFB980F9814EB7A`
SSDEEP | `1536:GF3vbRpaTi07EMKW4OFgu24sDRccRXP0VOESXthksJczJe8s4TIePPMuJ:EjkR4MKuFgu2Pfh0VtSX7ksJkTNxJ`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
Error:  Unrecognized command line option '--help' (Error Code 0x80070057:  The parameter is incorrect.)

```

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\tttracer.exe](tttracer.exe-AAF4C8B847ADDA45EDB38E2768772E8D.md) | 35

## Possible Misuse

*The following table contains possible examples of `tttracer.exe` being misused. While `tttracer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `Name: Tttracer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Command: tttracer.exe C:\windows\system32\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `    Description: Execute calc using tttracer.exe. Requires administrator privileges` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Command: TTTracer.exe -dumpFull -attach pid` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `    Description: Dumps process using tttracer.exe. Requires administrator privileges` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Path: C:\Windows\System32\tttracer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `  - Path: C:\Windows\SysWOW64\tttracer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | ` - IOC: Parent child relationship. Tttracer parent for executed command` | 



MIT License. Copyright (c) 2020 Strontic.


