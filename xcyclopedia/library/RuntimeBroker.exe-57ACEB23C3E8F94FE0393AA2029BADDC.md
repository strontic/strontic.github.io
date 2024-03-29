﻿---
title: RuntimeBroker.exe | Runtime Broker
excerpt: What is RuntimeBroker.exe?
---

# RuntimeBroker.exe 

* File Path: `C:\Windows\system32\RuntimeBroker.exe`
* Description: Runtime Broker

## Hashes

Type | Hash
-- | --
MD5 | `57ACEB23C3E8F94FE0393AA2029BADDC`
SHA1 | `E17AB3C6C038F086D0654626B62979795AD06EFE`
SHA256 | `E00345A3DF0EE01EDBD9C14E39EA8C8D5FA0A7D09DE8141155333391F8AAA453`
SHA384 | `4CB19CB602B964BA4DB15729C5D479E4C3A22632882BCC4456191013419BA5C911E9E475935A0672DE64D51DC94067CD`
SHA512 | `EE52F0FCAB28A05AE7FF2A9EBD248C94886192C46BB585770C02D235AA0D48C0CA4BD15617772BC0A859593F2A97E70DD8D94946F01E62698C1F2F044F9AE3BD`
SSDEEP | `1536:/vCUohAf8DfSSSeoucmUgLGJssg1NKxV1jLEAOV/ySSyQEA5X+VU2e5fPmkK:/gQufSSSSFaJjJO/yfyQBIfqf+kK`
IMP | `0EED46A2FDA377B907A358F23DB4199F`
PESHA1 | `5E7C87CCA1625B1F048CECAEF829EFE1AB9A8202`
PE256 | `B21CB49168436529063E11E79130D1068DAC350982056D6D8DE23F88DC76C0F5`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/e00345a3df0ee01edbd9c14e39ea8c8d5fa0a7d09de8141155333391f8aaa453/detection/


## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\runtimebroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


