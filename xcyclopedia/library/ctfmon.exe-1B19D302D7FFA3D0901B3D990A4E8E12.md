---
title: ctfmon.exe | CTF Loader
---

# ctfmon.exe 

* File Path: `C:\Windows\SysWOW64\ctfmon.exe`
* Description: CTF Loader
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1B19D302D7FFA3D0901B3D990A4E8E12`
SHA1 | `1C06DBE26185E2956373118EDC7543EE5FE9B6EB`
SHA256 | `33AD4738B6342C9CC2DA01402B26A4424C0ADFDDDE9936D8926A86BF8D80D44F`
SHA384 | `51041DBF8CF4DD7BA2CB445D58DA97125335C848520978BAC6B9A9A7EC3911C945F532207841A3051822A9A2DAD9AB58`
SHA512 | `348405010F1AF06ADE0F4B9A27144E783C48777E93D0EFD2D2F42C3DBAC34DD9CA54EC7618120384F36B1A34BC0BCC0A38808080B8D6866C010743E327890293`
SSDEEP | `96:K6Qq4eRAWEKAp2hJH3DGjoK6HU9osQshDJ7pRKRcLEWhgWwUeq:K6Qq4q2JUU9osQsniWhgW`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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



MIT License. Copyright (c) 2020 Strontic.


