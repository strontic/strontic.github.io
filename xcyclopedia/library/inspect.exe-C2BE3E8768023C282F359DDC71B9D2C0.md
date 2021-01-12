---
title: inspect.exe | Inspect Object (64-bit UNICODE Release)
excerpt: What is inspect.exe?
---

# inspect.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\inspect.exe`
* Description: Inspect Object (64-bit UNICODE Release)

## Screenshot

![inspect.exe](screenshots/inspect.exe-6F5AEEA6E52F989AB14616FE0BC9D668-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `C2BE3E8768023C282F359DDC71B9D2C0`
SHA1 | `8B9C1D4335B04E9E7D8C54CDEADFC0500C1465EB`
SHA256 | `7C4D3080E314819D13D0A4F704068357D22DB5C447A2462980766065F5C40D84`
SHA384 | `17F37A44EA994A22FCE9E73648925C46E2D0A506E09F52F6AAE113ABAB6593808B120DFBD71CF06C6323D69F4989FB6A`
SHA512 | `E1031DF66D58391DD19C6811474A7E397B055C3E6AF4E1D0A1A1EB9A932FCABBEF6350C25E0F311E305F6F5B74255A409791826A939BF7E0FE57D54F9285DAA0`
SSDEEP | `3072:BRc2D3oPXT/9K9IjWOOOozLWFOCx4qjt9sF3UMKYMKI6Cf+sk8BTbNryc78DL+:nT3cXT/9KejWtPWl9sF3UMKYMKI6u0t+`
IMP | `FD9BA3997C843970551017713D9FCB16`
PESHA1 | `6F4A24B915A3A7F5C473C8566C1CCDBB19A18EBA`
PE256 | `59FA897464BCC59AA3229AE7274E9183D7A3E4A2E3F1109F517C94921CF835CC`

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
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\accevent.exe](accevent.exe-EE4E6F4157D2F4A00810ECF85D685644.md) | 35
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\accevent.exe](accevent.exe-499CAE98F79635D60CC333400963554E.md) | 32
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\inspect.exe](inspect.exe-6F5AEEA6E52F989AB14616FE0BC9D668.md) | 43

## Possible Misuse

*The following table contains possible examples of `inspect.exe` being misused. While `inspect.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Some security tools inspect files with static signatures to determine if they are known malicious. Adversaries may add data to files to increase the size beyond what security tools are capable of handling or to change the file hash to avoid hash-based blacklists.\n\nDetection: Depending on the method used to pad files, a file-based signature may be capable of detecting padding using a scanning or on-access based tool. \n\nWhen executed, the resulting process from padded files may also exhibit other behavior characteristics of being used to conduct an intrusion such as system and network information Discovery or Lateral Movement, which could be used as event indicators that point to the source file.\n\nPlatforms: Linux, macOS, Windows\n\nDefense Bypassed: Anti-virus, Signature-based detection",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `One can also manually inspect a server for outgoing DNS requests to DGA` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gaming_supply_chain.misp_event.json](https://github.com/eset/malware-ioc/blob/master/winnti_group/gaming_supply_chain.misp_event.json) | `"description": "Some security tools inspect files with static signatures to determine if they are known malicious. Adversaries may add data to files to increase the size beyond what security tools are capable of handling or to change the file hash to avoid hash-based blacklists.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


