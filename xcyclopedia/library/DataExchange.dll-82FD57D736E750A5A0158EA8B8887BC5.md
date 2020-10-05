---
title: DataExchange.dll | Data exchange
excerpt: What is DataExchange.dll?
---

# DataExchange.dll 

* File Path: `C:\Windows\system32\DataExchange.dll`
* Description: Data exchange

## Hashes

Type | Hash
-- | --
MD5 | `82FD57D736E750A5A0158EA8B8887BC5`
SHA1 | `20E561B55ACBDE0E2B196183013E21FB81008647`
SHA256 | `F95F9D9DC951FF11F294492CC62164623556D0512D31D81031BC766857A2A9C1`
SHA384 | `A9115F6A392C56A1E2FF7ED7458A5E2D9CCD7DE218044598106B992DB71ED3657E145BD2BE71E9F803A9E96697CB3F0B`
SHA512 | `2E6E537539BDB207042405306C558AEF57146026ABB88708AFCB31AB9F5CCB3260361D573AC2EF8686DF3BAE0D3839984562FDA32A20C3BE1215289ACB0CF4A3`
SSDEEP | `3072:xHOpRdI9pSZ/kwJseXcRE+ddCZSxQs8/fbEMDC+owa72PG2IaeAEEl2N69:UBcpSZ/DJmdCZELGfvCbFQIpFN6`
IMP | `5BA064C9B02712CEDCC9C8A0DD6C6C5B`
PESHA1 | `7FF7BB25ED007B3DDC1DFB62FC8FABB1BADD597E`
PE256 | `35C67E9DD9C3C7DDB771C5A6DB6042A85E0C143BE6457D746E2762C368F439EF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 3 | Exported Function
`DllGetActivationFactory` | 2 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DataExchange.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/f95f9d9dc951ff11f294492cc62164623556d0512d31d81031bc766857a2a9c1/detection/


## Possible Misuse

*The following table contains possible examples of `DataExchange.dll` being misused. While `DataExchange.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_apt_muddywater_dnstunnel.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_apt_muddywater_dnstunnel.yml) | `- 'DataExchange.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


