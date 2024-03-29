﻿---
title: javaw.exe | Java(TM) Platform SE binary
excerpt: What is javaw.exe?
---

# javaw.exe 

* File Path: `C:\ProgramData\Oracle\Java\javapath\javaw.exe`
* Description: Java(TM) Platform SE binary

## Screenshot

![javaw.exe](screenshots/javaw.exe-6CE5BDFF0E2F280B0A270ECD1AC31E68-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `D554CF4A04E7973DF28372BCDAE820B3`
SHA1 | `21967D83E5401CEE94BF170370330ABAD8BC4FEC`
SHA256 | `69F70DE18DBE78CE1B1D3B2F4A8C12A8FAAE86B9A1D94716916968D6CDBDDA57`
SHA384 | `B7EB3205F6607123869B5E49110A2BA01A181CB129F0F333A47089514B6CB79A54911F46149E05E4C7D569BC482E3347`
SHA512 | `81254377EB50BDFA4A5A96E994DC031207906E980A37C79804526C148FC49AD7E4A2B21D1F51C7F75593CAF9EDCB467F7D754BD73A88647A8F256904A9B9C61A`
SSDEEP | `3072:JKdm6VH3+Q6zaesz1SCCTOphtYAHIG0xR4TBfHnIjZqMNxWDAhT:J6mgh6BszOTO3tYAHIGGR4TBQvoDsT`

## Signature

* Status: Signature verified.
* Serial: `12F0277E0F233B39F9419B06E8CDE352`
* Thumbprint: `3B75816D15A6D8F4598E9CF5603F1839EE84D73D`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN="Oracle America, Inc.", OU=Code Signing Bureau, O="Oracle America, Inc.", L=Redwood Shores, S=California, C=US

## File Metadata

* Original Filename: javaw.exe
* Product Name: Java(TM) Platform SE 8
* Company Name: Oracle Corporation
* File Version: 8.0.1710.11
* Product Version: 8.0.1710.11
* Language: Language Neutral
* Legal Copyright: Copyright  2018



## Possible Misuse

*The following table contains possible examples of `javaw.exe` being misused. While `javaw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_adwind.yml) | `description: Detects javaw.exe in AppData folder as used by Adwind / JRAT`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_adwind.yml) | `description: Detects javaw.exe in AppData folder as used by Adwind / JRAT`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_mal_adwind.yml) | `description: Detects javaw.exe in AppData folder as used by Adwind / JRAT`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


