---
title: verclsid.exe | Extension CLSID Verification Host
excerpt: What is verclsid.exe?
---

# verclsid.exe 

* File Path: `C:\Windows\system32\verclsid.exe`
* Description: Extension CLSID Verification Host

## Hashes

Type | Hash
-- | --
MD5 | `00E31F606C082A42247D3BDE2CA8A171`
SHA1 | `31EB54997B6EE5E126F3DB038EE73F34D4D84EDB`
SHA256 | `18C4E76431643AAF2113A5C4556CBE1D79CBC8113E4B0904A6205D73A8926045`
SHA384 | `A7A1AC01393598C37A59228CFF0F1695ACF0AB23617903FE0D979D56B1F016DB39B7B34C48A3F1B7E82F956ACE6737D1`
SHA512 | `BB0C09334197AF868B469634E842A81C5205A00639FB95CE93581F231719E17DBE0C49FE6C3C6B0FF831FE9B1A51BB2B387E7F2DF3EC9A42CABF7282C6D9B074`
SSDEEP | `192:sCtBf9auhKg6rZ6wQrp9g4FxfJZGmuJAxcNukPWNNW:saBljwrgwC9T1JZHuYoWNNW`
IMP | `FA65D753209C7382631265744DE49154`
PESHA1 | `37DE54C96F9BB00832F43E3B958CE563BE1FB087`
PE256 | `F3BD5375A7C0D44BBF04E29D7131A14845992262D1A92AECF1F28DE6E6575899`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verclsid.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/18c4e76431643aaf2113a5c4556cbe1d79cbc8113e4b0904a6205d73a8926045/detection/


## Possible Misuse

*The following table contains possible examples of `verclsid.exe` being misused. While `verclsid.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `title: Malware Shellcode in Verclsid Target Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `description: Detects a process access to verclsid.exe that injects shellcode from a Microsoft Office application / VBA macro` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `TargetImage: '*\verclsid.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `Name: Verclsid.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Command: verclsid.exe /S /C {CLSID}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Path: C:\Windows\System32\verclsid.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Path: C:\Windows\SysWOW64\verclsid.exe` | 



MIT License. Copyright (c) 2020 Strontic.


