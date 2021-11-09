---
title: ngentask.exe | Microsoft .NET Framework optimization service
excerpt: What is ngentask.exe?
---

# ngentask.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe`
* Description: Microsoft .NET Framework optimization service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `3142937610966B092CA8886C76A3B113`
SHA1 | `EA8FF42F1D5346532A42BC345DD25652BA63A850`
SHA256 | `FF70C1B71440E34931EB8EF97236F3CB2BB2668C72E7A3338660CED5C0753AF8`
SHA384 | `DEE5303874DD1AF4CB302F07F3186D92BFF5F896A5A3E127613F327D0DCAA2C2A13FC4A5C7DD21D256BD801268AB3ED9`
SHA512 | `EFBFDDCCB42F610EA2E768E9264019A96D7F2885ED089F70C2F71EBA6B6ED839C1D54409BF7FD53BC63AA17F6847FE6439260F7AF05DD1F8187360E68E425083`
SSDEEP | `1536:x9eXaGuBPGsm5x4v2zUFl7ppN8InFun3hWKp:X7GuhhmXngXFf8IFehh`
PESHA1 | `86BB275EDD3947BC97CAD39438D5E66B668A5FCA`
PE256 | `96979A29CC3D3DA6112F4612DDCED5EECFFA704836E8DEFD103619B0F72C0F90`

## Runtime Data

### Usage (stdout):
```cmhg
NGen Task starting, command line: "C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe" --help
Unrecognized command line option --help

```

### Usage (stderr):
```cmhg
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe [options...]
 This tool reads from the usage log data produced by the runtime, and triggers NGen to occur.
   /RuntimeWide - Parse the fusion stream of the usage logs instead of the App stream. Task runs in machine-wide mode.
   /Critical - Runs as a critical idle task.

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NGenTask.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4320.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4320.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/ff70c1b71440e34931eb8ef97236f3cb2bb2668c72e7a3338660ced5c0753af8/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe](ngentask.exe-5CC0818E8E6FC3920A7BAFF21F6DEDA4.md) | 80
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe](ngentask.exe-E983CDC58F22C7641CFAB9A21A3171DD.md) | 60

## Possible Misuse

*The following table contains possible examples of `ngentask.exe` being misused. While `ngentask.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\ngentask.exe'  # c:\Windows\Microsoft.NET\Framework(64)\ngentask.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


