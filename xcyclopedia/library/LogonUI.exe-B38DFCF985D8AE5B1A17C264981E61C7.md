---
title: LogonUI.exe | Windows Logon User Interface Host
---

# LogonUI.exe 

* File Path: `C:\Windows\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `B38DFCF985D8AE5B1A17C264981E61C7`
SHA1 | `D14F98FA954E585672D8505DFBB1F8240C49EDA1`
SHA256 | `AA62D29803D52EC06CD27ED3124E034048F09606EB7342181913C9817C7B44C5`
SHA384 | `0DEF752E3AD60FE1CF9E27FC1640CF7B73FDEE05D39370B9909603ED20310AED045DD38C116A54CDB2BB6B3897839BA8`
SHA512 | `7B16787E8C4A5197D0E904C73CD256BF02E646B4C65013668161D00A193314E14270F4A5756D85E1562E990B197441A2A53D17297FF4D03F08A13C3FCB8326EE`
SSDEEP | `192:wPQ3DcPYDUfHqlZubjq4jrzCEqXVdQ9GvGHsl2WnUW:bDUfwgbLjreEOXGHsoWnUW`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logonui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | 		$s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


