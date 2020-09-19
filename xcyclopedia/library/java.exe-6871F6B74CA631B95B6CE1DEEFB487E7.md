---
title: java.exe | Java(TM) Platform SE binary
---

# java.exe 

* File Path: `C:\ProgramData\Oracle\Java\javapath\java.exe`
* Description: Java(TM) Platform SE binary

## Hashes

Type | Hash
-- | --
MD5 | `6871F6B74CA631B95B6CE1DEEFB487E7`
SHA1 | `1453B98681D5E4A93226E6C12D903238636CADA6`
SHA256 | `8F957B71C0E38F4F19D02FCA3584B3AB42B434F097B849D289B8B00473961063`
SHA384 | `C55F593990E3CF660B7E2FF3CA454E01B447A35883A96EB53BADB076E373DD87F1E253308C40A90646D138DEBD9BBECA`
SHA512 | `4DB080996591EA45F94CBEEC7D844C5DC27CA01BDFF31D1FBC4E04E281637A59EEEA5966E22D207FD6FD7F744D7AECEFEF1861D9649054128BFCBB458B6D99C0`
SSDEEP | `3072:CQ4Hdi0lKx96kzos9wMD0yRgUdRPu3fKMoTBf3vSjZqMN8YiYkwc:349S6DsStyaUddu3yMoTBevRXhc`

## Runtime Data

### Usage (stderr):
```cmhg
Error: opening registry key 'Software\JavaSoft\Java Runtime Environment'
Error: could not find java.dll
Error: Could not find Java SE Runtime Environment.

```

## Signature

* Status: Signature verified.
* Serial: `12F0277E0F233B39F9419B06E8CDE352`
* Thumbprint: `3B75816D15A6D8F4598E9CF5603F1839EE84D73D`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN="Oracle America, Inc.", OU=Code Signing Bureau, O="Oracle America, Inc.", L=Redwood Shores, S=California, C=US

## File Metadata

* Original Filename: java.exe
* Product Name: Java(TM) Platform SE 8
* Company Name: Oracle Corporation
* File Version: 8.0.1710.11
* Product Version: 8.0.1710.11
* Language: Language Neutral
* Legal Copyright: Copyright  2018


## Possible Misuse

*The following table contains possible examples of `java.exe` being misused. While `java.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- '\programdata\oracle\java.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_10189.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_10189.yml) | `ParentImage\|endswith: 'DesktopCentral_Server\jre\bin\java.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`java.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         description = "Detects uncommon file size of java.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         and filename == "java.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


