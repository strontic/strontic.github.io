---
title: iphlpsvc.dll | Service that offers IPv6 connectivity over an IPv4 network.
excerpt: What is iphlpsvc.dll?
---

# iphlpsvc.dll 

* File Path: `C:\Windows\system32\iphlpsvc.dll`
* Description: Service that offers IPv6 connectivity over an IPv4 network.

## Hashes

Type | Hash
-- | --
MD5 | `C669B5F35FC37F7B083A278577D08874`
SHA1 | `A8284D0923D4552491171A468C48DF7D00A85159`
SHA256 | `253E2535D737868F5B797781591966A3BADEF78341C534E337B196C1F22505C1`
SHA384 | `7157A192EA575968EF869B3B3974D0EA76DADE88B42B0959F9E26D065081728A5A6ED78252B5862F5CAA05924C4A097F`
SHA512 | `896783820839CC927ECC597DE8C76CE2831541E6AE9668330CDAF7CA2C7602018234812A0505AE8D6643D1B3132DB341673A92422D752D823DBF134338ECE85E`
SSDEEP | `24576:eedzAPAdEXGy/RRTGAbwNJv1Qh24sG49N:DdzAPAkGsRpG08JNQhwN`
IMP | `162FB79B0EA1AC3471E06F8D87640679`
PESHA1 | `F711D18E5B29367A9CB02A0DD0C50F2D2112CC75`
PE256 | `AA605CE3C3CEA981C893489629776CF49F6D4180589D8488C3FA58146C008A82`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`IphlpsvcSysprepGeneralize` | 1 | Exported Function
`ServiceMain` | 2 | Exported Function
`SvchostPushServiceGlobals` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iphlpsvc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/253e2535d737868f5b797781591966a3badef78341c534e337b196c1f22505c1/detection/


## Possible Misuse

*The following table contains possible examples of `iphlpsvc.dll` being misused. While `iphlpsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_enfal.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_enfal.yar) | $s2 = "iphlpsvc.tmp" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


