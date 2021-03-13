---
title: RuntimeBroker.exe | Runtime Broker
excerpt: What is RuntimeBroker.exe?
---

# RuntimeBroker.exe 

* File Path: `C:\Windows\system32\RuntimeBroker.exe`
* Description: Runtime Broker

## Hashes

Type | Hash
-- | --
MD5 | `1E03C94933E088D9FAB00B49D46CC370`
SHA1 | `1DFE5C08B6C640833FD1B2D0761E074E3CE6AEC2`
SHA256 | `20A7EB74EFD23933A5C0887D3D8CE66FEA009A6CD257508CB4B0EB70F8D27C57`
SHA384 | `C88AE376AA379EB4ED3A457C881B44E85338B453DB40F82A04372FB6B98AF27FC813035C388A553EF296E25A912A555D`
SHA512 | `D25AED435FB9F5094881EF0C96FAA877A316E767FF3523C38D0C141EE79C05DA80130454BE486663BA6EEA65C890E888EB02045AE86B26B3FC0C5AD794F1DD63`
SSDEEP | `384:kXkyzjbt4ss3JwAnAGWaP6GON0Hxd5OXCpf+veF2WH6WpFlRDBRJLElfkPjCE/X:kXkOtiJwg6GOCxL+veFf31PFPf/X`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\runtimebroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


