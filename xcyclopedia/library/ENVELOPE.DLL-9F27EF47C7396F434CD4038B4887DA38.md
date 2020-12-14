---
title: ENVELOPE.DLL | Microsoft Outlook Envelope Control
excerpt: What is ENVELOPE.DLL?
---

# ENVELOPE.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\ENVELOPE.DLL`
* Description: Microsoft Outlook Envelope Control

## Hashes

Type | Hash
-- | --
MD5 | `9F27EF47C7396F434CD4038B4887DA38`
SHA1 | `4EC81A2452AAF843E6A4A1707C58B0B509EA7A14`
SHA256 | `6FA48BD1A060AADDB935C37300F9229ED958C5767A3106A4D26A85ABB4B15B6D`
SHA384 | `7C8E565C1EB69A0379FFBEA57F2D78904FF2300DEC3143A366B46B98C6479339EC25C2D4406987F301930B17201D4B4A`
SHA512 | `E44A53B3BD684DAA8C41C68644039C72865FA6732B16802C6C083B1643FCDB9C0783888499384AEB39AE912E338281ACA45410B36653FCFC2A93C3A7BF31139D`
SSDEEP | `3072:bAN3Jl6QAQn7TxyL138Qmu/SCFqE10ITx6sNYNUYqxvVDfF7P:b66QAQv8VKNzs6s3Yqxj7`
IMP | `830DE150A062A6B022198312516D2218`
PESHA1 | `DC9EFC054F7F1688E5E0E92439EF6206551D8A56`
PE256 | `7041469868FE23679B70FECA871A0AF1F3BD517B1100D53C39EE7F731681AB35`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Envelope.dll
* Product Name: Microsoft Outlook
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20174
* Product Version: 16.0.12527.20174
* Language: Language Neutral
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/6fa48bd1a060aaddb935c37300f9229ed958c5767a3106a4d26a85abb4b15b6d/detection/

## Possible Misuse

*The following table contains possible examples of `ENVELOPE.DLL` being misused. While `ENVELOPE.DLL` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_mirai.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_mirai.yar) | $s2 = "loadURL>$(echo HUAWEIUPNP)</NewDownloadURL></u:Upgrade></s:Body></s:Envelope>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


