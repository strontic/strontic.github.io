---
title: inspect.exe | Inspect Object (32-bit UNICODE Release)
excerpt: What is inspect.exe?
---

# inspect.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\inspect.exe`
* Description: Inspect Object (32-bit UNICODE Release)

## Screenshot

![inspect.exe](screenshots/inspect.exe-6F5AEEA6E52F989AB14616FE0BC9D668-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `EB644BD85DC3E7120AE8459C75A70460`
SHA1 | `D41FB03778D84A8BFC7CAB53D603357B906ED478`
SHA256 | `FC527011F17B3DCBA93D914AB7322C1F3BC6FE3872C361082307A80984E660F5`
SHA384 | `6FC345B5F69DEC632EE9AC06B58272348600D1E9E2B8DD9E20C981ED1CEF4DC291766A7D76047CB470E32B09F51C6EB1`
SHA512 | `1992B65C5C935C1E7ECDE33C8BD30B52D293EE7277C633DC9BCF0539AD46D49DA7A9CE8248453FED80C96F396A4BFAB032F3A809EA47945D7A72308B79302B34`
SSDEEP | `6144:xqM63kMKYMKoqCHYVi94HrGS8zq1QJaRXwfuh:xqM63vm/4894LH1QKU`
IMP | `21F5E91FC9921974FA172D5259F5DC4D`
PESHA1 | `9771BF9BDFFE68F9EE704C8EF7D41C1DAA880241`
PE256 | `F1E79A17116A531BBE3F64DFEC32F34F0EB0D04B520D8598B2E55BCD763E6865`

## Runtime Data

### Window Title:
Inspect  (HWND: 0x00BA0858)

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\oleaccrc.dll.mui | File
(R-D)   C:\Windows\System32\en-US\UIAutomationCore.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme1383959086 | Section
\Windows\Theme2042523233 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\inspect.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: INSPECT.EXE
* Product Name: Microsoft Active Accessibility
* Company Name: Microsoft Corporation
* File Version: 7.2.0.0
* Product Version: 7.2.0.0
* Language: English (United States)
* Legal Copyright:  2012 Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/fc527011f17b3dcba93d914ab7322c1f3bc6fe3872c361082307a80984e660f5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\accevent.exe](accevent.exe-2B304EE7CC72B92167541E1359435DA9.md) | 30
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\inspect.exe](inspect.exe-B804026AF7C771E19D70EA0358340BF9.md) | 35
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\accevent.exe](accevent.exe-F84263097B3C4DE7D584C1E6E2B778D8.md) | 36

## Possible Misuse

*The following table contains possible examples of `inspect.exe` being misused. While `inspect.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Some security tools inspect files with static signatures to determine if they are known malicious. Adversaries may add data to files to increase the size beyond what security tools are capable of handling or to change the file hash to avoid hash-based blacklists.\n\nDetection: Depending on the method used to pad files, a file-based signature may be capable of detecting padding using a scanning or on-access based tool. \n\nWhen executed, the resulting process from padded files may also exhibit other behavior characteristics of being used to conduct an intrusion such as system and network information Discovery or Lateral Movement, which could be used as event indicators that point to the source file.\n\nPlatforms: Linux, macOS, Windows\n\nDefense Bypassed: Anti-virus, Signature-based detection",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `One can also manually inspect a server for outgoing DNS requests to DGA` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gaming_supply_chain.misp_event.json](https://github.com/eset/malware-ioc/blob/master/winnti_group/gaming_supply_chain.misp_event.json) | `"description": "Some security tools inspect files with static signatures to determine if they are known malicious. Adversaries may add data to files to increase the size beyond what security tools are capable of handling or to change the file hash to avoid hash-based blacklists.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


