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
MD5 | `7671A105DCF05A6FB3E8CC1C0D21686D`
SHA1 | `9316829C364DA617E36D37D48BC1E5C16EEFEBB8`
SHA256 | `CFB7DD7E63343D5F863468737677158D9A5E207862BD3361C96E88094A0D69E3`
SHA384 | `6B231C98065CFA8841E0C6672EE022278FD4F94CB7E8022BDD6057E8977AA9A52D18CCC4F0F92F9950B1E5D177128022`
SHA512 | `E2C2CDBB6808F5730A6F3B29484FF4748ED3CBEA797630F0638549D7DC8EF57210EFA10EFC3BE510D03EAED95CA7BD2486BF33AEE22ED0562D010213545E326A`
SSDEEP | `24576:AjVINwENNu3//XUwJI/Zd4kie/ZgFA8TumqwE:AOeA/7AA8TumqN`
IMP | `2601842F772C1F9ABA3AAD89180D20E0`
PESHA1 | `D11C443C190A455954C9BBA12A3FB1509FF063FD`
PE256 | `A276112FED037E89D1B1E38F3BC6321352E4B0FED100BEA406D063486F820717`

## Runtime Data

### Usage (stdout):
```cmhg
Unknown switch.

```

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SecurityHealthService.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.1907.16384 (WinBuild.160101.0800)
* Product Version: 4.18.1907.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/cfb7dd7e63343d5f863468737677158d9a5e207862bd3361c96e88094a0d69e3/detection


## Possible Misuse

*The following table contains possible examples of `SecurityHealthService.exe` being misused. While `SecurityHealthService.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\SecurityHealthService'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


