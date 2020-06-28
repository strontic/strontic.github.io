---
title: mspaint.exe | Paint
---

# mspaint.exe 

* File Path: `C:\Windows\system32\mspaint.exe`
* Description: Paint
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4C99142651ABA7300AD7FFBB5BE2E81A`
SHA1 | `E6353CCD671ED8EEFFBB012D744A7E3B0C56BD81`
SHA256 | `FDB5A84BF619CFDB6BBF6C88D657724574EC67393AFAD56443F0C173BF1AFEF5`
SHA384 | `255FD4B958A5CF7F6C48A074E9AB53F9674E30C9D196A279346788D20C21A93B9CBF5269B746A2C577190007817661AF`
SHA512 | `06B50F8BDB25E60DD7624DFAF7D89DB1404B30998C6AE3E77893BB1DE7948DF355FB2C8E42ED3F71D21A0AB781511C9C4B6EAE2362A4D92F7277B4720FCA9282`
SSDEEP | `24576:uxD4o8zPsAdQnDdEJ+OknWfYgoSlSoUM:/DGdERuq1lSoz`

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

* Original Filename: MSPAINT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `mspaint.exe` being misused. While `mspaint.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\mspaint.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe (a 2009 file)`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


