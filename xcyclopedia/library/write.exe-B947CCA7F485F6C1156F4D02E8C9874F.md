---
title: write.exe | Windows Write
---

# write.exe 

* File Path: `C:\Windows\system32\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `B947CCA7F485F6C1156F4D02E8C9874F`
SHA1 | `9F184E48F17F104C6A476687E8E760A65A0326B5`
SHA256 | `A70D52EDA892EDC073932B462CC367CDBFBACE3F4196857D8D4FA869A13DE792`
SHA384 | `54333EC10CFCAB874257FA46DCF5E9F30D3F982B194D32C4022D7533AB04356D7093EF6B2552D164126EF9B5D2AB830D`
SHA512 | `28C6FF32BC94AAD8B201E469F854DDE32CAD9EB2E7A80ED858AC2FF99648312CECCA06918BCE96E8D905D52D5EBEE076BD08D957F7933602C0C79D93EAD20EE3`
SSDEEP | `192:ZV89t7hglDCS8O3GbXdYFWihWxu/sWGOW:ZVM7hceSP3IXioxu/sWGOW`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\write.exe](write.exe-E87C6A38E61A712C48025A6AD54C1113.md) | 35
[C:\Windows\SysWOW64\write.exe](write.exe-3D6FDBA2878656FA9ECB81F6ECE45703.md) | 43
[C:\Windows\write.exe](write.exe-B947CCA7F485F6C1156F4D02E8C9874F.md) | 100

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `  - Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


