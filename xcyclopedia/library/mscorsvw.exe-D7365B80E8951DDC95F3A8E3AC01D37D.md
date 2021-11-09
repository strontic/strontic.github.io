---
title: mscorsvw.exe | .NET Runtime Optimization Service
excerpt: What is mscorsvw.exe?
---

# mscorsvw.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\mscorsvw.exe`
* Description: .NET Runtime Optimization Service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `D7365B80E8951DDC95F3A8E3AC01D37D`
SHA1 | `0636347981CB05B74859CE7C841753DA90CE679A`
SHA256 | `3E5099F573601926E59862FBA2495974688E72677C73F10E4C99E26A76CDCF37`
SHA384 | `A7E0E2966D778B78BC5649177DF338B0563D1D9845EEFE5BE59B0E329EFA9F0B73102786602A717422AD729B7519E89D`
SHA512 | `D66B3570E715C37D51A8F31A1D0AF5407536B88C0C6DDFBC9620E1CE974974C1E3700E6B2C7D32F0D00467AEE47E8A0894E2B57E2C58C3F347BECD648A7F3D74`
SSDEEP | `3072:eAipiUHyetEM+R9A0lBan8iEFGg7sc4T7n:m9AB97an8J7sFT7n`
IMP | `B7B46D14320453EEF45740445AF31BF1`
PESHA1 | `D57766EDC2F1C0CC60468D08F6EC4003D3AD87F3`
PE256 | `BFC9A193E915DB7C7485A2169807AA8A3C2ABE3EF300E280A985D1D43B481337`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\mscorsvw.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/3e5099f573601926e59862fba2495974688e72677c73f10e4c99e26a76cdcf37/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\mscorsvw.exe](mscorsvw.exe-C17EBBA87A1484B3A72BE5F241045B70.md) | 86

## Possible Misuse

*The following table contains possible examples of `mscorsvw.exe` being misused. While `mscorsvw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\mscorsvw.exe'  # c:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsw.exe for instance`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


