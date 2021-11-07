---
title: LsaIso.exe | Credential Guard & Key Guard
excerpt: What is LsaIso.exe?
---

# LsaIso.exe 

* File Path: `C:\Windows\system32\LsaIso.exe`
* Description: Credential Guard & Key Guard

## Hashes

Type | Hash
-- | --
MD5 | `C9A4EAD6CED14D5B2AF396613D6C2085`
SHA1 | `6621AC74112247677A0EE0FAE63D4270DD1910E0`
SHA256 | `E87672B39D716870DF7C4426547D66D8155F284CDF8230C12B3BB31343A5C0E1`
SHA384 | `51CB319D94F8A9BF5B2D5DC5D2D26A5A7045321437DB8567367E6E508ECA72FF501795EDA577A10E6B0DDACAEFFD2355`
SHA512 | `69BB21F641B29ABFA8BDFBA104D1C3C306DABC815D32B952149DA401FC649645A2ADBCC5EEAE185A2B924A2C8D0E210E0A2AED82FCBD45976D7341FD4C197BAD`
SSDEEP | `3072:rkJjpWaibl0pUX2M1JYQZWTTthjWj4RZ+ZLxXPk4QS7+DzE5g4bQRV0Q3jv6K:rkJjpWai+mYxhyj4RZ+ZLFPkC76I/2/f`
IMP | `E20271694660EB17470CEE91AE53E0B4`
PESHA1 | `9254E1FB2099412484DB80DA13F77975F0C41A64`
PE256 | `E2095EEDD983DED845EC2F3A45D4EC571433C2559208D56220C79610CA118379`

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LsaIso.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1288 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1288
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e87672b39d716870df7c4426547d66d8155f284cdf8230c12b3bb31343a5c0e1/detection


## Possible Misuse

*The following table contains possible examples of `LsaIso.exe` being misused. While `LsaIso.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '\lsaiso.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


