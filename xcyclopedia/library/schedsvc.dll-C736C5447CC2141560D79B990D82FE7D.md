---
title: schedsvc.dll | Task Scheduler Service
excerpt: What is schedsvc.dll?
---

# schedsvc.dll 

* File Path: `C:\Windows\system32\schedsvc.dll`
* Description: Task Scheduler Service

## Hashes

Type | Hash
-- | --
MD5 | `C736C5447CC2141560D79B990D82FE7D`
SHA1 | `4773E4749BC6C581D753F1E9630FEFD551C485D0`
SHA256 | `4D6B4D425ED7066A2EA3E3209F48C84E6074F9093F9B7E3A9BD16BB9D74056BC`
SHA384 | `E36F1629F4995C9EA070762C68D6DC8688F4B0E340A535175D7C0CD22AFACA5053BAE8345EBA7B25AD16A8E5CE638A7D`
SHA512 | `D42382F5E9EB3C247D6AAC7593A2A0DA3956E80687F5E2CEBA5640E2AFA03C3E5223B285A47B3276CE487CA5043A80391F49CB7EC2B0C9928F93651A8EFF1858`
SSDEEP | `24576:3G9E0AVX+LOVxlUEg+iA3P7LbMaq7A9gRtW:3GV6TRiA3PXbMv7A9gRtW`
IMP | `3BBD38D813FA8A9856623ED654A45A74`
PESHA1 | `DB09C158AD9D5BEE7300EC1C611C0EE9DABF5896`
PE256 | `CB1A70AF7290A166A033EAA78FFF14959B0B0DA475BF0A96EE197290DD631C7A`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ServiceMain` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: schedsvc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/4d6b4d425ed7066a2ea3e3209f48c84e6074f9093f9b7e3a9bd16bb9d74056bc/detection/


## Possible Misuse

*The following table contains possible examples of `schedsvc.dll` being misused. While `schedsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_hdroot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_hdroot.yar) | $s2 = "Schedsvc.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


