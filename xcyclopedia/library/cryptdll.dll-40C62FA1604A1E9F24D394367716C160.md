---
title: cryptdll.dll | Cryptography Manager
excerpt: What is cryptdll.dll?
---

# cryptdll.dll 

* File Path: `C:\Windows\SysWOW64\cryptdll.dll`
* Description: Cryptography Manager

## Hashes

Type | Hash
-- | --
MD5 | `40C62FA1604A1E9F24D394367716C160`
SHA1 | `191AEEC70CB020DD462A3E0D6ABEE4BE74D0CF88`
SHA256 | `F46F29506AC8E8FCE62CBAD5EFFDE1B3BDBF1A32877F37EC2C29259036EEA100`
SHA384 | `4A504303ED8EF29938D68141CF23EE216972F20E16FE0DABD853A71FA61547302BAE9D164E8F27C34F321B506E0F8324`
SHA512 | `B7C5FC1755D079AE8280D37C58C0DEDAF0368E61EC2DC7CE3680636B6FE6D9E2B1F4B2D3FE9141381FDC3C6F0E932302A22799DFC1C7B07488C77172687131AB`
SSDEEP | `1536:4V0juawfNK6/pKO7oK9KNKou4rmbIXKCKxKtKUbvocb2mJTXsc8ZP3:O0jujdboASfu46wtAi1l4dZP`
IMP | `2713D6DE24282CB3AF6E2436F33FC7DA`
PESHA1 | `7169AC2BDD11D5867840BAB27466FFA1CFC41E94`
PE256 | `F4E52AAB42C19A46D4BEC563C51E0FC88592B66BC13CD465656E1B4120130B1C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`aesCTSDecryptMsg` | 19 | Exported Function
`MD5Init` | 16 | Exported Function
`MD5Final` | 15 | Exported Function
`KRBFXCF2` | 14 | Exported Function
`HMACwithSHA` | 13 | Exported Function
`CDRegisterRng` | 12 | Exported Function
`CDRegisterCSystem` | 10 | Exported Function
`CDRegisterCheckSum` | 11 | Exported Function
`CDLocateRng` | 9 | Exported Function
`CDLocateCSystem` | 7 | Exported Function
`CDLocateCheckSum` | 8 | Exported Function
`CDGetIntegrityVect` | 6 | Exported Function
`CDGenerateRandomBits` | 5 | Exported Function
`CDFindCommonCSystemWithKey` | 4 | Exported Function
`CDFindCommonCSystem` | 3 | Exported Function
`CDBuildVect` | 2 | Exported Function
`CDBuildIntegrityVect` | 1 | Exported Function
`aesCTSEncryptMsg` | 20 | Exported Function
`MD5Update` | 17 | Exported Function
`PBKDF2` | 18 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cryptdll.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/f46f29506ac8e8fce62cbad5effde1b3bdbf1a32877f37ec2c29259036eea100/detection/


## Possible Misuse

*The following table contains possible examples of `cryptdll.dll` being misused. While `cryptdll.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `- 'cryptdll.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_skeletonkey.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_skeletonkey.yar) | $dll1 = "cryptdll.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


