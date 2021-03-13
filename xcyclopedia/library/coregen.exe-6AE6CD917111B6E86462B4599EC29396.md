---
title: coregen.exe | Microsoft Common Language Runtime native compiler
excerpt: What is coregen.exe?
---

# coregen.exe 

* File Path: `C:\Program Files\Microsoft Silverlight\5.1.50918.0\coregen.exe`
* Description: Microsoft Common Language Runtime native compiler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `6AE6CD917111B6E86462B4599EC29396`
SHA1 | `F446B5EDB7AC15A8FBDEF89D9BE1DF77FD91B5FA`
SHA256 | `E0344BC6C6A47D1AD11EC3CE98C48DF07DC80B5F6337BBCA155491EE0F814A1F`
SHA384 | `B8B98C050463183BA7E4D1236825601D9350A8E76052E386965D8E9AA8F4DDF991B2795F4EC2EAA0E4925CAEB61EC148`
SHA512 | `56DEB21DF98A806CB6C7CD9757E1C4E5571B955B0037582DF384B73E88141197E0450A4CD84214DA922DB9B0CBCE3D7E6BEA23F52EC985D4977E5EBA82079B43`
SSDEEP | `1536:2dKTjw9GNL5ybOjU+Q0x7+66lVk0b89LhrNo3Kv2:aKTjw9A9aOA+t9aG489Lhxo3m2`
IMP | `10CE2F704DACA82828A02A0D76021EB8`
PESHA1 | `FE88F80DB3957E509D08DDDE3EAC5319EBE52D91`
PE256 | `8AB15669CBC7D795A184270C3D444C20CBF5B20C9A69C3613505B86E421F0F6B`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) CoreCLR Native Image Generator - Version 5.1.50918.0
Copyright (c) Microsoft Corporation.  All rights reserved.

Usage: coregen [args] <assembly name>

    /? or /help     - Display this screen
    /nologo         - Prevents displaying the logo
    /L <coreclr>    - Specify path to coreclr.dll

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Microsoft Silverlight\5.1.50918.0\coregen.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: coregen.exe
* Product Name: Microsoft Silverlight
* Company Name: Microsoft Corporation
* File Version: 5.1.50918.0 built by: SL_V5_SVC
* Product Version: 5.1.50918.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/e0344bc6c6a47d1ad11ec3ce98c48df07dc80b5f6337bbca155491ee0f814a1f/detection/


## Possible Misuse

*The following table contains possible examples of `coregen.exe` being misused. While `coregen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `Name: coregen.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `Description: Binary coregen.exe (Microsoft CoreCLR Native Image Generator) loads exported function GetCLRRuntimeHost from coreclr.dll or from .DLL in arbitrary path. Coregen is located within "C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\" or another version of Silverlight. Coregen is signed by Microsoft and bundled with Microsoft Silverlight.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Command: coregen.exe dummy_assembly_name`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Command: coregen.exe /L C:\folder\evil.dll dummy_assembly_name`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Path: C:\Program Files\Microsoft Silverlight\5.1.50918.0\coregen.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Path: C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\coregen.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe loading .dll file not in "C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe loading .dll file not named coreclr.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe command line containing -L or -l`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe command line containing unexpected/invald assembly name`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe application crash by invalid assembly name`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


