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
MD5 | `8EA79E659DA869468746ABE850D67996`
SHA1 | `C4D483AC89670539592D1B73733C25FB4FE3F574`
SHA256 | `7D8D8696ACD1815316174FBA563F2E2AD0BE3B5E9C6A28E237F9131A41067169`
SHA384 | `5C59CA2F6894DEC2EBA74B28D97BD842AC5816DD976B852588B0BCF8CE0432A9BBA045B03652BA692355BD9EAE9C1B8B`
SHA512 | `F7D62FFA3F0CD1E3E8A163EE2D724854F749ECE3169180F573CA683F2641519E8C7FC4308E0E4CC362A78F40640649D2F251FF0E35CD1E1710F810D79B7512B5`
SSDEEP | `3072:5AiZiUHXe/Is2d9AKxIL3AHI+8YI/o1pGa7YTq:f9bV9sL3AiYI/8pGa7YW`
IMP | `924E0F5D11C8B561E5182D325FAB1C75`
PESHA1 | `7CC9582DB528384E68F5F4ECB8958E38A33ADCBA`
PE256 | `9EFACF82747833017C8E65177A1605EB7EB5C7844823465324891337F59B35EF`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mscorsvw.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/7d8d8696acd1815316174fba563f2e2ad0be3b5e9c6a28e237f9131a41067169/detection


## Possible Misuse

*The following table contains possible examples of `mscorsvw.exe` being misused. While `mscorsvw.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\mscorsvw.exe'  # c:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsw.exe for instance` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


