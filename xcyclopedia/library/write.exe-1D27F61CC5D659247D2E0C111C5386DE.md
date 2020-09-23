---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\WINDOWS\system32\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `1D27F61CC5D659247D2E0C111C5386DE`
SHA1 | `D35657CAD7FE1986EF049EA5094D601B2B7F87E6`
SHA256 | `EE25F7A64B299968BE5109C6AB8D692CEBE12FF7BBAFEBF53918787C602F104C`
SHA384 | `E2C198ACC074A05186646DEBCA293523128A4A537CA8E7CD78722CBFE4EC50E7156213F94798EFCA00964D0D4ADDA20E`
SHA512 | `DE350CBC1C72E779C71B2F7E2FCDB2FC18F98DFF4CE5EB42B85830DF378AA7C0C348A4064B98D6F1EC0FE370BBE82936B6FE12E683AEADB30ACBE9AD71F61001`
SSDEEP | `192:pM4fN8IBUmrj0DyC8RRvWAT1qWUdguUthWxu/EWrOW:K4CIBz0uCEBWAu9coxu/EWrOW`

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
[C:\WINDOWS\SysWOW64\write.exe](write.exe-7FBA1268E8C8AEC66A7BF9420F54A745.md) | 32

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


