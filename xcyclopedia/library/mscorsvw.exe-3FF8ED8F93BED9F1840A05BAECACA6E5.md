---
title: mscorsvw.exe | .NET Runtime Optimization Service
excerpt: What is mscorsvw.exe?
---

# mscorsvw.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe`
* Description: .NET Runtime Optimization Service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `3FF8ED8F93BED9F1840A05BAECACA6E5`
SHA1 | `2D2D387355142FCB43885D406CD63ED483700DD6`
SHA256 | `C5BE32520FF3A1A6ACDF66B30A9A068F20F946F2E1091C6F85D6E9F09FBA1624`
SHA384 | `157A8FE67004D7E5A7C5E7D3DF36889874AD04BC9A981DB2972191E00BB0D784F417ED074696378AC4A5531A43D7526B`
SHA512 | `DB9D68338599D888DB8536D5824785B2F5400CFEE51083C98496988E8074F8BCCDBF2AE90EF83426679E516EAC3D49EF5CF478D1B5413C476CB54BDE2397E579`
SSDEEP | `3072:uihUhia0CqY/cQhQ1FZgOHdeA8eKszyT:uyUs7CZC1JM`
IMP | `72FA9F3C31A63C45F46299F4E6E1B9CE`
PESHA1 | `886944AC433B7C7D26A49A93F7B1CDFDA2ED6E7F`
PE256 | `5EC8F7F1E636FC9A3BC00AF942FF14AA820DE2117FD6B27B4DFC6861E691F88D`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\fusion.dll |
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\mscorsvc.dll |
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\IMM32.DLL |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\mscoree.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ole32.dll |
C:\WINDOWS\System32\OLEAUT32.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\SYSTEM32\ucrtbase_clr0400.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\SYSTEM32\VCRUNTIME140_CLR0400.dll |
C:\WINDOWS\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mscorsvw.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4341.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4341.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c5be32520ff3a1a6acdf66b30a9a068f20f946f2e1091c6f85d6e9f09fba1624/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe](mscorsvw.exe-412A3FB0C25743DA59375C1E298933EA.md) | 85

## Possible Misuse

*The following table contains possible examples of `mscorsvw.exe` being misused. While `mscorsvw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\mscorsvw.exe'  # c:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsw.exe for instance`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


