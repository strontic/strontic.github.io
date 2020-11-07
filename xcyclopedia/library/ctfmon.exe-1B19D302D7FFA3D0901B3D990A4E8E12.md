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
MD5 | `1B19D302D7FFA3D0901B3D990A4E8E12`
SHA1 | `1C06DBE26185E2956373118EDC7543EE5FE9B6EB`
SHA256 | `33AD4738B6342C9CC2DA01402B26A4424C0ADFDDDE9936D8926A86BF8D80D44F`
SHA384 | `51041DBF8CF4DD7BA2CB445D58DA97125335C848520978BAC6B9A9A7EC3911C945F532207841A3051822A9A2DAD9AB58`
SHA512 | `348405010F1AF06ADE0F4B9A27144E783C48777E93D0EFD2D2F42C3DBAC34DD9CA54EC7618120384F36B1A34BC0BCC0A38808080B8D6866C010743E327890293`
SSDEEP | `96:K6Qq4eRAWEKAp2hJH3DGjoK6HU9osQshDJ7pRKRcLEWhgWwUeq:K6Qq4q2JUU9osQsniWhgW`
IMP | `A0DF2CAE30CD48F978A8D80039C738E5`
PESHA1 | `025E1EB147C4D753E8728EBD862B3B67CE4F10F1`
PE256 | `D70A05F4239E96CF7AD31104988A0DE8925AF34F7E5269171CF0276EFE1F205C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ctfmon.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/33ad4738b6342c9cc2da01402b26a4424c0adfddde9936d8926a86bf8d80d44f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-29656B9E6B04C85E7BF4018B6844BE28.md) | 43
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-97D7FF9EED95ADF3785F2D0219EEED46.md) | 52
[C:\windows\SysWOW64\ctfmon.exe](ctfmon.exe-BE80808B5FE1D9C9351653EEC814A75A.md) | 36
[C:\WINDOWS\SysWOW64\ctfmon.exe](ctfmon.exe-C0D57D7289C20B3B4D8680369394F188.md) | 55

## Possible Misuse

*The following table contains possible examples of `ctfmon.exe` being misused. While `ctfmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `6C04499F7406E270B590374EF813C4012530273E` \| ctfmon.exe       \| Abused legitimate application \| Clean file                             \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_four_element_sword.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_four_element_sword.yar) | $s1 = "\\System32\\ctfmon.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s0 = "%USERPROFILE%\\AppData\\Local\\Temp\\Low\\ctfmon.log" fullword ascii /* PEStudio Blacklist: strings */ /* score: '43.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s1 = "%USERPROFILE%\\AppData\\Local\\Temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '37.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s2 = "\\temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '28.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


