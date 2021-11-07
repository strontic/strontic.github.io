---
title: SecurityHealthService.exe | Windows Security Health Service
excerpt: What is SecurityHealthService.exe?
---

# SecurityHealthService.exe 

* File Path: `C:\Windows\system32\SecurityHealthService.exe`
* Description: Windows Security Health Service

## Hashes

Type | Hash
-- | --
MD5 | `0C29D470959F1AE4AC208AA2D2BA3E87`
SHA1 | `AE4A8E321A4CA28FBED8AE5719E00478CE797F51`
SHA256 | `61B1BCA1EF2073482C5A14FD9F5DB31FE54AAD61FFA8DA2A708BA974912C037C`
SHA384 | `ED7322391330F25A3FEB471E23613A8DEDA607E7C5A918907A04523011928657377B1A7D069B65191767C672AF3C874E`
SHA512 | `B480FD0A84B997BFA8C9A0BED858562B94AEFB1020255DE6BEFDD40C2674716C7463C386C62DF8FA18FFDCAEB69024653FF35220D950DA2F7CB95BCBA9F333BC`
SSDEEP | `12288:37b7ap/kykn6zszmeXJr7jZn4JholqKYLzERYVSOreV1uEL8/ah:37fap8yaiiZ5lIhowKYLzIYVQV1uEL8o`
IMP | `F5BD79DC95E0303BDD85756328F16293`
PESHA1 | `1BB8ED7A045CDB13ED7295DD202224D22E083103`
PE256 | `B31738A3887B84E2A1D6DE1CDC45EB81E4C738858BEE2E64814FD0C61345A31B`

## Runtime Data

### Usage (stdout):
```cmhg
Unknown switch.

```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SecurityHealthService.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.1807.16384 (WinBuild.160101.0800)
* Product Version: 4.18.1807.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/61b1bca1ef2073482c5a14fd9f5db31fe54aad61ffa8da2a708ba974912c037c/detection/


## Possible Misuse

*The following table contains possible examples of `SecurityHealthService.exe` being misused. While `SecurityHealthService.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\SecurityHealthService'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


