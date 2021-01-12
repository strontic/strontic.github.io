---
title: inspect.exe | Inspect Object (32-bit UNICODE Release)
excerpt: What is inspect.exe?
---

# inspect.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\inspect.exe`
* Description: Inspect Object (32-bit UNICODE Release)

## Screenshot

![inspect.exe](screenshots/inspect.exe-6F5AEEA6E52F989AB14616FE0BC9D668-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `B804026AF7C771E19D70EA0358340BF9`
SHA1 | `E553C5BA1DCB55001C3B0542D981ECB23C131317`
SHA256 | `A678C604BE37EB2BFF3B88C59B7BF2928C223932BB04AE45E477833DBB27BBC2`
SHA384 | `A88232F95D294D2033CE112A598B0D06B4DC92586A70768259DB08A36EA83DBA2EBC4E32EF9B714BBD86CEE328CA5247`
SHA512 | `B2379175B90461E9D0EC89BF3D5794B54BF9CC8003DD89C761E418930F99A09C82FC72332E3EBAAF60CA4AD236B00607D8A213ACD1AA6F97306B59166EA86361`
SSDEEP | `6144:5GrMU3kMKYMKYqOyVSfzptFge6b9TTUW8Tp:mMU3vmjy4zpx6bFup`
IMP | `09619BB57B671BC1DACCF1B9547AEB88`
PESHA1 | `E0E7BF852B2FAC8F00D230BEDBE24D1C43895020`
PE256 | `93C8300FD3DEF61CF2D43B80E5856FEB8FE91A8476A9EEDCB9B791998C5EEF2D`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: INSPECT.EXE
* Product Name: Microsoft Active Accessibility
* Company Name: Microsoft Corporation
* File Version: 7.2.0.0
* Product Version: 7.2.0.0
* Language: English (United States)
* Legal Copyright:  2012 Microsoft Corporation. All rights reserved.
* Machine Type: 452

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\accevent.exe](accevent.exe-2B304EE7CC72B92167541E1359435DA9.md) | 35
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\accevent.exe](accevent.exe-F84263097B3C4DE7D584C1E6E2B778D8.md) | 32
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\inspect.exe](inspect.exe-EB644BD85DC3E7120AE8459C75A70460.md) | 35

## Possible Misuse

*The following table contains possible examples of `inspect.exe` being misused. While `inspect.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Some security tools inspect files with static signatures to determine if they are known malicious. Adversaries may add data to files to increase the size beyond what security tools are capable of handling or to change the file hash to avoid hash-based blacklists.\n\nDetection: Depending on the method used to pad files, a file-based signature may be capable of detecting padding using a scanning or on-access based tool. \n\nWhen executed, the resulting process from padded files may also exhibit other behavior characteristics of being used to conduct an intrusion such as system and network information Discovery or Lateral Movement, which could be used as event indicators that point to the source file.\n\nPlatforms: Linux, macOS, Windows\n\nDefense Bypassed: Anti-virus, Signature-based detection",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `One can also manually inspect a server for outgoing DNS requests to DGA` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gaming_supply_chain.misp_event.json](https://github.com/eset/malware-ioc/blob/master/winnti_group/gaming_supply_chain.misp_event.json) | `"description": "Some security tools inspect files with static signatures to determine if they are known malicious. Adversaries may add data to files to increase the size beyond what security tools are capable of handling or to change the file hash to avoid hash-based blacklists.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


