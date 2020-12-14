---
title: SIHClient.exe | SIH Client
excerpt: What is SIHClient.exe?
---

# SIHClient.exe 

* File Path: `C:\Windows\system32\SIHClient.exe`
* Description: SIH Client

## Hashes

Type | Hash
-- | --
MD5 | `1A2203911DB977B17D378E2B2CC21E25`
SHA1 | `DE5A5FB881366351E5B55C329551C8E362258228`
SHA256 | `2765B204B66737C10C5E8E04AFF91AA80F851CEC28D4FA941FFB81E6F05626E3`
SHA384 | `7198BEFBE101BAB48EBD392AF821CFABE6DA9C6ADD2445E7C10B02DCEF462FCC078D6EC5DEA124B23123E5E09765CA00`
SHA512 | `4AE3D0834C5248000E967D844A5B12FC5F81D381E3D99BE6947D55EA4A66EBC9DF5B0F7506F5311A30F815823E4EE67E192DF18C06A0C698918A442DFE641100`
SSDEEP | `6144:IOCUtmYAGr1TgnkQ+4Vx2f8hOAvj3aWzlE9IT90edT+f+b6fnA6RFFMTi5f9:bCUvKECNvbaOIaZ+XA6fyTAf9`

## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SIHClient.exe](SIHClient.exe-F2CC4F2F8B22C6540E557892A2E3A562.md) | 91

## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


