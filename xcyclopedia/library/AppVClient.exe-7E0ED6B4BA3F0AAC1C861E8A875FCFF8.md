---
title: AppVClient.exe | Microsoft Application Virtualization Client Service
excerpt: What is AppVClient.exe?
---

# AppVClient.exe 

* File Path: `C:\Windows\system32\AppVClient.exe`
* Description: Microsoft Application Virtualization Client Service

## Hashes

Type | Hash
-- | --
MD5 | `7E0ED6B4BA3F0AAC1C861E8A875FCFF8`
SHA1 | `921FABC287B8BC6DDAF9043DF0002626D4452AAC`
SHA256 | `6E17899E7D3C7BF80CDC31DBDDA8E9B880B54ECBF5842C907E764A267ADFFCC0`
SHA384 | `F4415DC42ED76E06C5BFE8E50D2939EB0872322DFB09245CC4085A1C7231475E8D36F8D1CD3A0EF4471331ED220E47FA`
SHA512 | `6D34D21C51A6EB435CC1B3D272CA487B814FC4B5F3DAEC0D6013A4E66CBBB5DA55C2B09EC04E7DFA49B3A55E1A0D33DFDC5653B49D893D051607BCED294748EC`
SSDEEP | `12288:VqFsEQETFCS0PmcrS5qjt6rLJ6457yM5/PQGNUbTRZZu6MAG:8Gfa0+cG5qjt6vJ6457ye/gi6Ml`
IMP | `1366F290C5A61FAA1E5E71959022B587`
PESHA1 | `C5322D3F218A7278A882B58F6EEFE04DACF3310E`
PE256 | `5050FCCB3151244E7C1B6569D42B699781177B17C2E1788BA83BA19D93FF70D6`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\AppVClient.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVClient.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1320 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1320
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6e17899e7d3c7bf80cdc31dbdda8e9b880b54ecbf5842c907e764a267adffcc0/detection


## Possible Misuse

*The following table contains possible examples of `AppVClient.exe` being misused. While `AppVClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `- AppvClient`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


