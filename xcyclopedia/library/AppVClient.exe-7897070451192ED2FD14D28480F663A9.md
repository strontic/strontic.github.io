---
title: AppVClient.exe | Microsoft Application Virtualization Client Service
excerpt: What is AppVClient.exe?
---

# AppVClient.exe 

* File Path: `C:\WINDOWS\system32\AppVClient.exe`
* Description: Microsoft Application Virtualization Client Service

## Hashes

Type | Hash
-- | --
MD5 | `7897070451192ED2FD14D28480F663A9`
SHA1 | `D2E268430E133606F609F82EBEC5065CBA49235F`
SHA256 | `FB8D9F041442A59D73B8A694A8FEA97CDB2FF773F629971DDE0137DF76CD1BF4`
SHA384 | `58A5BAAC3811EB7646AB7B4BAD6316E8C95164CCC32D8AFEA25AE7EE33C9A1EE22481DF68ADFF1ED784BF3CC33B3D540`
SHA512 | `4BA53FB8641DDD45528DC08271F9BBC46BD89CD4D970A562B42BF9F7F716E9E3DFDCB753EBC13EF097D453125A352A80462EE460FD1CFD8CC98E2A51DA087A20`
SSDEEP | `12288:c5i/5SAwJXfEQK5JIzPSCAJVWHe4Kqi5Seql4js13EZGNUbTXxdITwNFTDJKQi:DSAwJPE1IDAo+4Kt+l4413EUQi`
IMP | `8703FC06C7C2636012CE96CED91FF7F5`
PESHA1 | `698288BB30BF1222401B95C46696CDA9BD70A920`
PE256 | `30D7A81F4248B58ACB7134EA3908207EBEA0CA90131109B7EAB5174B41D3422E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\AppVClient.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVClient.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/fb8d9f041442a59d73b8a694a8fea97cdb2ff773f629971dde0137df76cd1bf4/detection


## Possible Misuse

*The following table contains possible examples of `AppVClient.exe` being misused. While `AppVClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `- AppvClient`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


