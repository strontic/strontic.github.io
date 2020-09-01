---
title: tttracer.exe | Time Travel Debugging Tracer Tool
---

# tttracer.exe 

* File Path: `C:\Windows\SysWOW64\tttracer.exe`
* Description: Time Travel Debugging Tracer Tool

## Hashes

Type | Hash
-- | --
MD5 | `AAF4C8B847ADDA45EDB38E2768772E8D`
SHA1 | `AD630FB86CA8F52524B491F8A14E74A114006D52`
SHA256 | `73FD8AA2603F3DF92DC6C912CC823099EF611340E6864A237D45C124AFC6EFB5`
SHA384 | `0C00BECB397266209CD62D7CC3301674723D811420B9D03B3F58C8FA504E27CF736E47F1098252EDF13A0CD70936CEAD`
SHA512 | `982BBA51C9093F7F6A75F8A6E219BBA8ADBF5195C728E7C54305EEBADE0B9DD21018E2198EC6F5FEDF8720ACDE2B218CBD6E2874801FEEB3D97F9CA1FB2A1A1F`
SSDEEP | `1536:8GqMbxBgvycQEdhC1/Hu+Kizxs7l9nvqGmESQQJczJe8s4TIew6QP1ICv:IMtavyFMG/OIzxAVSQQJkTu3v`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tttracer.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
[C:\Windows\system32\tttracer.exe](tttracer.exe-61C47B71A25302934A8CFB16E3B4DBD9.md) | 35

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


