---
title: ctfmon.exe | CTF Loader
excerpt: What is ctfmon.exe?
---

# ctfmon.exe 

* File Path: `C:\Windows\SysWOW64\ctfmon.exe`
* Description: CTF Loader

## Hashes

Type | Hash
-- | --
MD5 | `29656B9E6B04C85E7BF4018B6844BE28`
SHA1 | `91E297712F7B8B72DF83C83D59E897D492D5A5D1`
SHA256 | `171ABACAD96CD027317621FC8FB74AA3B8C13BF25EBA79955B0E51BB90C6A843`
SHA384 | `F10C67689E56862317964887A4878C1ADC9AE7F013AB762A5015FE505E454AB668798DC29E6B476E736626CDAF279B11`
SHA512 | `57D7BFD06DA4D25091114D697F3DE5D8B34CE38DC8D70968E0476771B176BD6E2BC60093B68AE53BCB306495254584E00663FCBEE3B6A82B6EC633634FC97007`
SSDEEP | `96:TekkA3GX9c27oo90tPDWPT4u14HbJV/s/iDm9os0Tz0DJ7pRKRNEW6gWw0ee0qZ:SkkAWXOI/TKbeiS9os0TzitW6gWV0`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-1B19D302D7FFA3D0901B3D990A4E8E12.md) | 43
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-97D7FF9EED95ADF3785F2D0219EEED46.md) | 36
[C:\windows\SysWOW64\ctfmon.exe](ctfmon.exe-BE80808B5FE1D9C9351653EEC814A75A.md) | 46
[C:\WINDOWS\SysWOW64\ctfmon.exe](ctfmon.exe-C0D57D7289C20B3B4D8680369394F188.md) | 33

## Possible Misuse

*The following table contains possible examples of `ctfmon.exe` being misused. While `ctfmon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `6C04499F7406E270B590374EF813C4012530273E` \| ctfmon.exe       \| Abused legitimate application \| Clean file                             \|`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_four_element_sword.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_four_element_sword.yar) | $s1 = "\\System32\\ctfmon.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s0 = "%USERPROFILE%\\AppData\\Local\\Temp\\Low\\ctfmon.log" fullword ascii /* PEStudio Blacklist: strings */ /* score: '43.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s1 = "%USERPROFILE%\\AppData\\Local\\Temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '37.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s2 = "\\temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '28.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


