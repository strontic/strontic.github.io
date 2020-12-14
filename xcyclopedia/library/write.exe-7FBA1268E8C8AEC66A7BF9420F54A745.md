---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\WINDOWS\SysWOW64\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `7FBA1268E8C8AEC66A7BF9420F54A745`
SHA1 | `F2DDC0E41426AEDA2A35D117B89FB8400F845166`
SHA256 | `CFBB731014E491B6FC70305D23195003CC0DF802B8C9BCF4E586FD7C92900B18`
SHA384 | `0A972103D5F07B002221FCF71185470F6E71F93984362143A6838A1711B7C728337D909506101D92E439D54629E78C9B`
SHA512 | `9C710F12828841149314369CCA0BB2A4F03C2AFA5644DED852DF0E374583CEA910A83BBC34CC7C664CAEF7A2493308C0F61581A3066C08EB1411D734CF7E6DAD`
SSDEEP | `96:kPp1kwoMNExbFn9Jkp2kRTDDDGjgq2Hng3M6tmZDJdMi2bKveLrxuJRd9EWrOWw+:eTzoHxRywgng3M6tmZPuxu/EWrOW+W`

## Runtime Data

### Child Processes:
wordpad.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\write.exe](write.exe-1D27F61CC5D659247D2E0C111C5386DE.md) | 32
[C:\windows\SysWOW64\write.exe](write.exe-1EFA647F97009893CC54BD677751A958.md) | 40
[C:\Windows\SysWOW64\write.exe](write.exe-3D6FDBA2878656FA9ECB81F6ECE45703.md) | 65
[C:\Windows\SysWOW64\write.exe](write.exe-55A288C36EBDFBA8F977307A8A2619D1.md) | 46
[C:\Windows\SysWOW64\write.exe](write.exe-ED73F0253A4C10F6B7C221FF6E8BD8B4.md) | 47

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


