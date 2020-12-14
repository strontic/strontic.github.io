---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\Windows\SysWOW64\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `55A288C36EBDFBA8F977307A8A2619D1`
SHA1 | `AB81F1C68543B79DA7B238DA39EB1A5149D751DF`
SHA256 | `0FFCC65F70860F3961694BA64DBE7D69B09B5F0D6EB095DFF8349D6B2F1F0E96`
SHA384 | `058FFB6E4F76DA5EE7F4A6BB46B810C10DEFEFBBDB7DB3F33846F30371B25D768FB521A98247D5FEE3B6638919D20320`
SHA512 | `0AF74257FACA6B86DB29756E9895D85066867B5B507B9983C4D24A568C9E38A7CD8772350D3104123932E5AEDCB31FE00DBFD79E2A850D14FA820411A2BFE2AE`
SSDEEP | `192:y8bV0AQb/4HTbkqM6tmZPuxu/0WhOWIwN:yrpbwHTQf2+mxu/0WhOW/`
IMP | `B05C7142E6016FF931CDC4142BE82084`
PESHA1 | `1A3B38BA2DDA5D4F0B18548A7235CB16785397F1`
PE256 | `B51996AE78FD0AA264B56BD979511DB883E886E96056E27EFC2CDFCF79416D0A`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\write.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/0ffcc65f70860f3961694ba64dbe7d69b09b5f0d6eb095dff8349d6b2f1f0e96/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\write.exe](write.exe-10F2BC4209233AB34BDA602967D0F798.md) | 41
[C:\WINDOWS\SysWOW64\write.exe](write.exe-7FBA1268E8C8AEC66A7BF9420F54A745.md) | 46
[C:\Windows\write.exe](write.exe-10F2BC4209233AB34BDA602967D0F798.md) | 41

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


