---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
---

# pcwrun.exe 

* File Path: `C:\WINDOWS\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker

## Hashes

Type | Hash
-- | --
MD5 | `8EF6CF4E50D1D30D34F9F451EBB4A781`
SHA1 | `FFDC649329FF4CC842312FCCC2D0D8F867846181`
SHA256 | `C14F8C3F2D7005D3AF2D880118C74523F40BAEFD44E34932E96F3A2A7FA690E5`
SHA384 | `A879FC6AF27D9DB1CB60B9190B4FB1BDC8B45C64FAAA19177EE9EF148B47F5036C0053C36F8AA2C087EABBE0D722226D`
SHA512 | `B8C78C066D1E559C6BE2904FA0988DE56839BDE8AD6AE2390E32959942F813E72EAD157844E0A6C227A7734D5376463EA84432E8D697BD64CDD4CA0F605600BA`
SSDEEP | `192:4N2ogLOLwB1EsMOchQXfRwO5gjeSxsAQGlWlO2dL7imMWtgW:GgLOLZROc6RbOjVxnlEO2pMWtgW`

## Runtime Data

### Child Processes:
msdt.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\pcwrun.exe](pcwrun.exe-FEE8B8FE78C3B7C9FC1C7ABB6FBCBCF6.md) | 69

## Possible Misuse

*The following table contains possible examples of `pcwrun.exe` being misused. While `pcwrun.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `Name: Pcwrun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Command: Pcwrun.exe c:\temp\beacon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Path: C:\Windows\System32\pcwrun.exe` | 



MIT License. Copyright (c) 2020 Strontic.


