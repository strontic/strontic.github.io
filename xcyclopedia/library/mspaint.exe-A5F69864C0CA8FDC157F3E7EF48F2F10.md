﻿---
title: mspaint.exe | Paint
excerpt: What is mspaint.exe?
---

# mspaint.exe 

* File Path: `C:\Windows\system32\mspaint.exe`
* Description: Paint

## Screenshot

![mspaint.exe](screenshots/mspaint.exe-8A6A020DABFB0024BE80D988C59F8F2A-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `A5F69864C0CA8FDC157F3E7EF48F2F10`
SHA1 | `52802248F949C442D7EF40734B23AF109F2F23D2`
SHA256 | `5E832C11FBA0B0F2BCAB3B105FF7D63AC7A1A766D11282D50ECEE9BB038771F5`
SHA384 | `63349C7DED65E7E98FA904DAE0937A548328D1A61C6930F0416BB8CC24DC864A2C2FEDE4B6BD69697FB962E8E3FA9B7A`
SHA512 | `023C7D3AABEB6719BD5B0D5B038890A899B4FA1549563C27DDBBC263F6AACFDE641B81B246C7CE08EAFAAFFC7C2E039D0C7030D449F74A216A2B10E0FE5EE215`
SSDEEP | `98304:TJD2u7InCEE+wysPM4mlaw0LI60GBGrGrGWAuU7jPLQ:TJD6nTE+wBMHlaw0/U7jPL`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSPAINT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\mspaint.exe](mspaint.exe-226B4A88EB18B3A86B6D56B0FC05F35C.md) | 93
[C:\Windows\system32\mspaint.exe](mspaint.exe-67C68B11E98970966DF59D2FAD6152BF.md) | 71
[C:\windows\SysWOW64\mspaint.exe](mspaint.exe-1B84FBA247447BBF80A0883495823263.md) | 90
[C:\Windows\SysWOW64\mspaint.exe](mspaint.exe-7598568851B293CD82E958C3B9735F7C.md) | 69
[C:\Windows\SysWOW64\mspaint.exe](mspaint.exe-8A6A020DABFB0024BE80D988C59F8F2A.md) | 91

## Possible Misuse

*The following table contains possible examples of `mspaint.exe` being misused. While `mspaint.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\mspaint.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe (a 2009 file)``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s4 = "mspaint.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


