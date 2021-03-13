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
MD5 | `E983CDC58F22C7641CFAB9A21A3171DD`
SHA1 | `E4C496B24B48F7DBA280CB2FDE9A6AC123E56620`
SHA256 | `58920FDDCA62BC540072BA0EAA17429F9ADD01985B90768DA33C5CD73771E361`
SHA384 | `A70647B841AD1AED0C240F0DFF9D76F520DD7D6421B856FEFAB4065916985C3A4026CAA4901C61F5A33441DD3D97F694`
SHA512 | `CBC7209F8C73C070BA8C0D580DA0508C7604059BDB7BFCD70434C7B244338899BAB3A850802FAF685A83C5E0F4E41EBD11FD56F6ACEA9B7EF62B2E94E5B03327`
SSDEEP | `1536:GL9eXaGuBPGsL5x4+Jtpd8InFupB7PsXl:GZ7GuhhLXdtb8IFu7PU`
PESHA1 | `D2CB48A10686ED66BD978E315B2E674C346FB5D5`
PE256 | `BB48E3E15E48BDEADAEA4BC3A2BBE30DDF5E2F53A25B8B19AF22DD16797534A1`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NGenTask.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/58920fddca62bc540072ba0eaa17429f9add01985b90768da33c5cd73771e361/detection


## Possible Misuse

*The following table contains possible examples of `ngentask.exe` being misused. While `ngentask.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\ngentask.exe'  # c:\Windows\Microsoft.NET\Framework(64)\ngentask.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


