---
title: ctfmon.exe | CTF Loader
excerpt: What is ctfmon.exe?
---

# ctfmon.exe 

* File Path: `C:\Windows\system32\ctfmon.exe`
* Description: CTF Loader

## Hashes

Type | Hash
-- | --
MD5 | `AFE653CCC2592633C22DD5DA4124AB59`
SHA1 | `65597164F3BFC193EAC140A8BCA7EAA3FCE8A92C`
SHA256 | `2D88AB60714D7CAA53B06653CDD31E14093121CEBF3BB7EB7CA0F1B9F04A3A8A`
SHA384 | `0F35AC7A9427183F31F18C352E013A911F8F774BA6FE6AC23C087A9EE8F80D108A5CF1049A22952DFD99A1F44BD97D77`
SHA512 | `D2CD6B392C22E6A02CC67BB2D1927298670F47A2CD8C62891EB8D46CD87BAD6FEE2061CECF4E09E450BE2D9AC9673562CFF77AAF5625A578163D0F4AFAF9F432`
SSDEEP | `192:jQJ1u2Llzc5pjlPJ3hF+JF+q617XCMW2gW:20KlQXlh3hF+z+qg/W2gW`
IMP | `6FD43544FB51C12382CAD7C88F550240`
PESHA1 | `461B9C0A6701A6EC91034012C22BA4F53F19AD30`
PE256 | `74F843A49267EAA3472F9F585F83E741C175DCA106B00E444559E9DA1AF8117F`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/2d88ab60714d7caa53b06653cdd31e14093121cebf3bb7eb7ca0f1b9f04a3a8a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\ctfmon.exe](ctfmon.exe-A1F2CF496F181AA75352E102978E60D0.md) | 60

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


