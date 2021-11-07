---
title: rdpclip.exe | RDP Clipboard Monitor
excerpt: What is rdpclip.exe?
---

# rdpclip.exe 

* File Path: `C:\Windows\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `9E089ECF8B86983B7A77E3844CD02BB5`
SHA1 | `0265C1718EC95B025D9719F3B4872826F8F4661F`
SHA256 | `AF5CAE4B514215E530643A7FEA2D7A47A1B15F6E5610347B217D1ABFA4AE0F92`
SHA384 | `E6D9E48E90A602FE3A19EDF4B56036CA427D727901C9ED6B4E1D6A0691F8F515BAE1287C5FD1C061D97E3212BB876313`
SHA512 | `E7EE8D7D56D19BDD5103A58D5DE00BEAD5960BCD46703D5D5FC7F371DB1FD1C0F29F80B67DF2658EF508F80C41947C9CCB1258A7E252908E784AE519F4E71657`
SSDEEP | `12288:57MvYJAP0qgCcvijGlkEaaO1arUG94Ft+VN81h8bk969xh0yl:BMvYJw9ncvijGlkEaagarUGakN81hwDe`
IMP | `E3F33CEBF67721DAC951AFBD20321206`
PESHA1 | `3EAC0DA1DDE4EB05E3CF74EEDBD36D03D7CF5508`
PE256 | `3EE747892157E03603B0909E0BE34986CDFF8298B50F4CCAAE0DFB5709AE1997`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/af5cae4b514215e530643a7fea2d7a47a1b15f6e5610347b217d1abfa4ae0f92/detection/


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image\|endswith: '\rdpclip.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


