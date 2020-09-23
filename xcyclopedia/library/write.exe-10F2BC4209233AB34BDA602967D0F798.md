---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\Windows\system32\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `10F2BC4209233AB34BDA602967D0F798`
SHA1 | `923BE1A95641EC2BE6F8F7E2CFF51E40C2655D65`
SHA256 | `664256FDE0E3A7C39801D91DD20204250638048E0E3F12C5891A84FFE283680A`
SHA384 | `149D613DFD9FB7A153DD2603D1A93F71B271A9DD4C2FC3C0C4DE09F727F65279FE6DAC7E88162B6FCC13658377BB430C`
SHA512 | `3B57E4832D29071782D9A18B1F1D7D70789368E6DFA10707BE27903DCECBC53A233015F397CAEC1EE896E24CE8273FF791D5946CAD03912E56D107FC3F79BFA6`
SSDEEP | `192:kfN8IBpmrj0DyjZ3NRvWkHbTTHrdguUxhWxu/0WhOW:kCIB20uddBWMb9Ioxu/0WhOW`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\write.exe](write.exe-55A288C36EBDFBA8F977307A8A2619D1.md) | 41
[C:\Windows\write.exe](write.exe-10F2BC4209233AB34BDA602967D0F798.md) | 100

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


