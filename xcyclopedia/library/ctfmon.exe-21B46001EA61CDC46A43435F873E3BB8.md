---
title: ctfmon.exe | CTF Loader
excerpt: What is ctfmon.exe?
---

# ctfmon.exe 

* File Path: `C:\WINDOWS\system32\ctfmon.exe`
* Description: CTF Loader

## Hashes

Type | Hash
-- | --
MD5 | `21B46001EA61CDC46A43435F873E3BB8`
SHA1 | `C422D48F5A3CE1176C6750E9A4D277E3AEBF7F36`
SHA256 | `0485B01BF15802441FE1671CAE60CDF82697B121B8EB21C2D5205CE6AAE7FFBE`
SHA384 | `7E4A5D2C898CD14E0695A221C47F182349089FD6CEBF59CE302E10A9AC2F04DBAE2755117757F61793EB38A387063D2B`
SHA512 | `D5B1CB497C8466773F8186B630052F9D6B2AA2302CEFEE40A15A7076E78432158E1A3A5EDA007C70F91418582C61D81B0AB3E4754EB1E8035FE812225C8F2D5A`
SSDEEP | `96:QfIhhl6QDswgXJW2QD6tkYEWMSGIdXZVWruTcEbL+QyRODJVpRKLNaLEWKgWwje:ioH6QD6bDtkYEWMd6ZncEbKQuCMWKgW`
IMP | `6FD43544FB51C12382CAD7C88F550240`
PESHA1 | `A0DA1CB344823AF2EAFF00F5F8314B11190E9833`
PE256 | `62DDE6FA0FDAB53370453C48B232C97E26CABF03B1644D64D9CCF04BBB5931D4`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/0485b01bf15802441fe1671cae60cdf82697b121b8eb21c2d5205ce6aae7ffbe/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\ctfmon.exe](ctfmon.exe-9929D83891B1C86F4E12C0C90BD8632E.md) | 38
[C:\Windows\system32\ctfmon.exe](ctfmon.exe-B625C18E177D5BEB5A6F6432CCF46FB3.md) | 40
[C:\WINDOWS\SysWOW64\ctfmon.exe](ctfmon.exe-82FEE2FD4957DD49F911D12C082AA49C.md) | 38

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


