---
title: coregen.exe | Microsoft Common Language Runtime native compiler
excerpt: What is coregen.exe?
---

# coregen.exe 

* File Path: `C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\coregen.exe`
* Description: Microsoft Common Language Runtime native compiler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `3BF709AEDF5042C39515756FB72E9EC0`
SHA1 | `5F536E6701D928DD262D475CD6987777B9FA5E33`
SHA256 | `412A6B755B2029126D46E7469854ADD3FAA850F5A4700DD1E078FCC536CA418A`
SHA384 | `9F4EA6CE74672F10C3D2C024C834EAFD226E352255018E3B82B7BE5E6961F3245C5AF232F8C026A402F0E3EFC782CDA7`
SHA512 | `82B28BC4F52B2CC8C6FCFB92C7D236F46C397DF4A860F6795C5D69AC92E82A0406EA66F61D63B2FA9FA2F8CE01A7975E6F28D69E1E2FAFF8462AB70EAD674C3C`
SSDEEP | `768:6EDUAnMskbT0UxBCuWG/oDS0THDhshjSfhFB67z6GYMMtwylKCVWFTBlRL7++i+:TCbhk+IVLm2fhFBoz4/cFTB++R`
IMP | `9959601E87162D788749D80BA2EA8FF2`
PESHA1 | `CAA5E552B562D6E2EB1454B9F6E41FC6406631E4`
PE256 | `F99063DEECF3FF2DDF5F07ABB33369F380D4969DE3AEAD18DB2DFA3ABBBE5C6A`

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
C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\coregen.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/412a6b755b2029126d46e7469854add3faa850f5a4700dd1e078fcc536ca418a/detection/


## Possible Misuse

*The following table contains possible examples of `coregen.exe` being misused. While `coregen.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `Name: coregen.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `Description: Binary coregen.exe (Microsoft CoreCLR Native Image Generator) loads exported function GetCLRRuntimeHost from coreclr.dll or from .DLL in arbitrary path. Coregen is located within "C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\" or another version of Silverlight. Coregen is signed by Microsoft and bundled with Microsoft Silverlight.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Command: coregen.exe dummy_assembly_name` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Command: coregen.exe /L C:\folder\evil.dll dummy_assembly_name` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Path: C:\Program Files\Microsoft Silverlight\5.1.50918.0\coregen.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- Path: C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\coregen.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe loading .dll file not in "C:\Program Files (x86)\Microsoft Silverlight\5.1.50918.0\"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe loading .dll file not named coreclr.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe command line containing -L or -l` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe command line containing unexpected/invald assembly name` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Coregen.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Coregen.yml) | `- IOC: coregen.exe application crash by invalid assembly name` | 



MIT License. Copyright (c) 2020 Strontic.


