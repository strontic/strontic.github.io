---
title: rc.exe | Microsoft Resource Compiler
excerpt: What is rc.exe?
---

# rc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\rc.exe`
* Description: Microsoft Resource Compiler

## Hashes

Type | Hash
-- | --
MD5 | `BB813951B9CEE9021A8654583BD64B42`
SHA1 | `CC3FBC5FEA48C9AA2450E4F392B2B639CEEBAC87`
SHA256 | `A7861CDC34B610E8DBE141370A234DC76165D46CD706D140F89A4956D3AEC9AE`
SHA384 | `E76B7B863255A43F65B7F4B489F54F33D0625E13EFD494055EE42FF4BB27C12766B86394C89DE569937AC679F5FF88DE`
SHA512 | `2C6AE1D5BB4049097372FA01678D1CFB2EC581AB611D049E7F1D6105C29B33C8529638F42887EE3B6231A29FC66A758646BC1934063EC58FC23EDD578E1AC6CE`
SSDEEP | `768:M0oBDC90adoUVD0ZCrC5vMOMC+7VoPv6yss5eDZ5XFmHSU6rkxkipWVXphok2:t90ajYXlDv6ysj6SlM2ok2`
IMP | `887702E888C5EE55D78938EF62E42B0E`
PESHA1 | `7B225F95ADEF71002ADA1E671510DE97410545D6`
PE256 | `FF4D9955BBE3A166DD4DB78F60389A6405488B7E5637C7C922C5189FE1F91B51`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown


## Possible Misuse

*The following table contains possible examples of `rc.exe` being misused. While `rc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image\|endswith: '\rc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


