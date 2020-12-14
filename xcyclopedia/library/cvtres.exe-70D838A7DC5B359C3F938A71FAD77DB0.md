---
title: cvtres.exe | Microsoft Resource File To COFF Object Conversion Utility
excerpt: What is cvtres.exe?
---

# cvtres.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\cvtres.exe`
* Description: Microsoft Resource File To COFF Object Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `70D838A7DC5B359C3F938A71FAD77DB0`
SHA1 | `66B83EB16481C334719EED406BC58A3C2B910923`
SHA256 | `E4DBDBF7888EA96F3F8AA5C4C7F2BCF6E57D724DD8194FE5F35B673C6EF724EA`
SHA384 | `DA6911C92262C8742B964F82C582D51B4A071C72FD3B5F871DB5F5C3EF928D4F73183EB964CA984AB709E872E11FA249`
SHA512 | `9C9A945DB5B5E7FF8105BFE74578E6F00B5F707F7C3D8F1F1FB41553A6D0EAB29CEF026E77877A1AD6435FA7BC369141921442E1485F2B0894C6BBCBD7791034`
SSDEEP | `768:bINyGPbIriyUAfETlzjpyXcZ0R55GhrdRMJmcBkmcrH+ihBy3kM:3GjyUAfWNkFR5GTMJhkmM+wBxM`
IMP | `0FCE7AAB563778C495FB59AA62464473`
PESHA1 | `5C888E327875860863798A0113E29BBDFF93DBE3`
PE256 | `C8FC5A7BD50569E6DE0E25278EC797C3AF36B7BD4F950940CEDE503201EDD1D3`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Windows Resource To Object Converter Version 14.10.25028.0
Copyright (C) Microsoft Corporation.  All rights reserved.

usage: CVTRES [options] [files]

   options:

      /DEFINE:symbol
      /FOLDDUPS
      /MACHINE:{ARM|EBC|IA64|X64|X86}
      /NOLOGO
      /OUT:filename
      /READONLY
      /VERBOSE

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\cvtres.exe |
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

* Original Filename: CVTRES.EXE
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.10.25028.0 built by: VCTOOLSD15RTM
* Product Version: 14.10.25028.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/e4dbdbf7888ea96f3f8aa5c4c7f2bcf6e57d724dd8194fe5f35b673c6ef724ea/detection


## Possible Misuse

*The following table contains possible examples of `cvtres.exe` being misused. While `cvtres.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\cvtres.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


