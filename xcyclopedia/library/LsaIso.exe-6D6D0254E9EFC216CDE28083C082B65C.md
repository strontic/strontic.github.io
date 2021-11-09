---
title: LsaIso.exe | Credential Guard & Key Guard
excerpt: What is LsaIso.exe?
---

# LsaIso.exe 

* File Path: `C:\WINDOWS\system32\LsaIso.exe`
* Description: Credential Guard & Key Guard

## Hashes

Type | Hash
-- | --
MD5 | `6D6D0254E9EFC216CDE28083C082B65C`
SHA1 | `BC11CC5480DC38DCD90CC15EA6A9AEC4F8D4CB44`
SHA256 | `17809F82C436DFE7BD312CD2BF320E5E9F8011DC64C50406EA48C3E64C898968`
SHA384 | `ABB807561337122F8493397FF6AC2AFB43D206F5E980DC79659C0D53405BC8BF93E1AC9357C4F8222E49A8BA77488DA8`
SHA512 | `7791728530BF58BD567F88152324978D7F6E5375014F636CEEAA7031118BA064F5E904E7A0EAD9C0F4E7994E3A9CF2A38B966DC00272AE9AC776474A76E96658`
SSDEEP | `6144:ZlirsfylqJxqvSRxo4a9CpFgS3ZbyB/tGN1:ZJacuzV01`
IMP | `6B0168F57231F870419649B42B7DB3AD`
PESHA1 | `D23A7F18FA7C17B3EAECD5F88C9FD274D7C5D24F`
PE256 | `C8ADDF7CB76339AE76073D716F556720DDFD2A1F520D05C8A49272C50CFEC406`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LsaIso.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.258 (WinBuild.160101.0800)
* Product Version: 10.0.22000.258
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/17809f82c436dfe7bd312cd2bf320e5e9f8011dc64c50406ea48c3e64c898968/detection


## Possible Misuse

*The following table contains possible examples of `LsaIso.exe` being misused. While `LsaIso.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '\lsaiso.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


