---
title: sqloledb.dll | OLE DB Provider for SQL Server
excerpt: What is sqloledb.dll?
---

# sqloledb.dll 

* File Path: `C:\Program Files\Common Files\System\Ole DB\sqloledb.dll`
* Description: OLE DB Provider for SQL Server

## Hashes

Type | Hash
-- | --
MD5 | `43E84E79F6ED4EAC723FD4ECD9B4380A`
SHA1 | `723C8D97E4C8D6B0DAB141C033024CEF32E4F564`
SHA256 | `1126C725D30471EA49233A08573EDEF63E37E0F63B7C257AF915CD3A887023D5`
SHA384 | `AEDC47BEFFABF2B93C15FD55DCF72C1DE90AB81872E4785A7F52FD0F0E861C69E19ACF961086F58B0B5928769CD679E6`
SHA512 | `D4125523E11941B8175CE25213254FC9FE680A61073D0C8A4F26F2553D463FEF4E7E90B7EAFF0FEC10AC60912C716E8F42576A48BA5E6AE768F97B7D43A982F8`
SSDEEP | `12288:crTjSn5bidJCZrBoyweBX7RyGqHe6D4z8fINFL0Kt1e8c53sOvRP:crXS5bidQVBPweBrns+8UFLrE8xC`
IMP | `3579AF5B6A34D41170C3F599AC5643D0`
PESHA1 | `4F722AB14609F5172D9F9FF308CFD5C42C0D637A`
PE256 | `F80850D7D299737CFF73E94B8286FE45B696AC8FB86D57227CBF07C15844AE2E`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 14 | Exported Function
`DllGetClassObject` | 15 | Exported Function
`DllMain` | 12 | Exported Function
`DllRegisterServer` | 16 | Exported Function
`DllUnregisterServer` | 17 | Exported Function
`SQLDebug` | 13 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sqloledb.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1126c725d30471ea49233a08573edef63e37e0f63b7c257af915cd3a887023d5/detection/

## Possible Misuse

*The following table contains possible examples of `sqloledb.dll` being misused. While `sqloledb.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s14 = "SELECT * FROM OPENROWSET('SQLOLEDB','Trusted_Connection=Yes;Data Source=myserver" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


