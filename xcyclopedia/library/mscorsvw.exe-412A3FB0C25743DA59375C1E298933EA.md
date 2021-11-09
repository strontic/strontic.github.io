---
title: mscorsvw.exe | .NET Runtime Optimization Service
excerpt: What is mscorsvw.exe?
---

# mscorsvw.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe`
* Description: .NET Runtime Optimization Service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `412A3FB0C25743DA59375C1E298933EA`
SHA1 | `9B3F155D23569A683A1C1059D539A15A0C08093F`
SHA256 | `DA1087BA2641EFD77D85E5838AEB6C333E80CAA9F24C889FD2DE2E0B58F8D1A5`
SHA384 | `36767E5523AEB7CEFA4F6D889CA0E1876F3FC65E4505554D28C49BADF60E3FE71462AE838D179A03D9203AACC4C69F09`
SHA512 | `021DC3788CF03013AD749B6B6301F906AD0124D4E738E989E27542B6CCFE1384AA23B965490A7AA4C9443B094908A44855F6F2F6B48363D58A0116231BCD0D62`
SSDEEP | `1536:yBb9ZCyhpIutUcSeITNga0nCjdYYuKcWDh/I1FZgOr+MUyd7b+Mbsm8eKzgQ07v9:1ihUhia0CqY/cQhQ1FZgO/deA8eKsN7V`
IMP | `72FA9F3C31A63C45F46299F4E6E1B9CE`
PESHA1 | `B7B054CCC86DA9B6E95342CFC90DBEEA2B6F5D03`
PE256 | `FBBB0D7BAB08F3A279770F24523D5D13EB9A29F323D4F372A8AC627A3498F98A`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\mscoree.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\ucrtbase_clr0400.dll |
C:\Windows\SYSTEM32\VCRUNTIME140_CLR0400.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000031F6B42E0EF61B11B1F00000000031F`
* Thumbprint: `6B92389862934AE6E93B248335EFB4E563AECA94`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Dynamic Code Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mscorsvw.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4320.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4320.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/da1087ba2641efd77d85e5838aeb6c333e80caa9f24c889fd2de2e0b58f8d1a5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe](mscorsvw.exe-3FF8ED8F93BED9F1840A05BAECACA6E5.md) | 85

## Possible Misuse

*The following table contains possible examples of `mscorsvw.exe` being misused. While `mscorsvw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\mscorsvw.exe'  # c:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsw.exe for instance`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


