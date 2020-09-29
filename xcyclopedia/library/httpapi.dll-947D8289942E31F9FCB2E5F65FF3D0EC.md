---
title: httpapi.dll | HTTP Protocol Stack API
excerpt: What is httpapi.dll?
---

# httpapi.dll 

* File Path: `C:\Windows\system32\httpapi.dll`
* Description: HTTP Protocol Stack API

## Hashes

Type | Hash
-- | --
MD5 | `947D8289942E31F9FCB2E5F65FF3D0EC`
SHA1 | `38A32F83D0E247C8B827AE9D0FF632F88A2FAFA8`
SHA256 | `F4CED65C41B4FF594FE786AC9B934E4681DF0D686E0D76510EB02DBB3E36E949`
SHA384 | `3B4D5681567A0E5EC894DC15BD50D68FE1D6E2D26BE566254499B8A401519CC541F4C4E662230C2C8B45544535FA88B9`
SHA512 | `F049E2076A4C7AE01DC5CFA3AB57A26596E4FECE49416BDECCFBBB5A4BEE6F98869E7A0185A53A36850463F9DE5AA1FAEE74855D4D035EC5BC4E66EA0D3156DA`
SSDEEP | `768:YKIevKIsLAl2JbOx8atZDj/8iWFc2pqa42pH:FpbvbKA2N`
IMP | `CC2E69927A5241B7E666C7698B40F6AE`
PESHA1 | `6373A3FD5B27305B052656749E90C5A81B47530E`
PE256 | `C494A95DD0F6644592CA264B0A8D7A551AB12447D2202AC4559FD791282F0DE4`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`HttpAddFragmentToCache` | 1 (0x1) | Exported Function | 0x0000000180004a00 | 0x00004a00
`HttpQueryServerSessionProperty` | 26 (0x1a) | Exported Function | 0x0000000180003c30 | 0x00003c30
`HttpQueryServiceConfiguration` | 27 (0x1b) | Exported Function | 0x0000000180004fc0 | 0x00004fc0
`HttpQueryUrlGroupProperty` | 28 (0x1c) | Exported Function | 0x00000001800038a0 | 0x000038a0
`HttpReadFragmentFromCache` | 29 (0x1d) | Exported Function | 0x0000000180004bf0 | 0x00004bf0
`HttpReceiveClientCertificate` | 30 (0x1e) | Exported Function | 0x0000000180004d00 | 0x00004d00
`HttpReceiveHttpRequest` | 31 (0x1f) | Exported Function | 0x0000000180001d30 | 0x00001d30
`HttpReceiveRequestEntityBody` | 32 (0x20) | Exported Function | 0x0000000180002260 | 0x00002260
`HttpRemoveUrl` | 33 (0x21) | Exported Function | 0x0000000180001010 | 0x00001010
`HttpRemoveUrlFromUrlGroup` | 34 (0x22) | Exported Function | 0x00000001800010a0 | 0x000010a0
`HttpSendHttpResponse` | 35 (0x23) | Exported Function | 0x0000000180002060 | 0x00002060
`HttpSendResponseEntityBody` | 36 (0x24) | Exported Function | 0x0000000180004590 | 0x00004590
`HttpSetRequestQueueProperty` | 37 (0x25) | Exported Function | 0x0000000180004dc0 | 0x00004dc0
`HttpSetServerSessionProperty` | 38 (0x26) | Exported Function | 0x0000000180003cc0 | 0x00003cc0
`HttpSetServiceConfiguration` | 39 (0x27) | Exported Function | 0x0000000180005450 | 0x00005450
`HttpSetUrlGroupProperty` | 40 (0x28) | Exported Function | 0x0000000180003930 | 0x00003930
`HttpShutdownRequestQueue` | 41 (0x29) | Exported Function | 0x0000000180004e60 | 0x00004e60
`HttpTerminate` | 42 (0x2a) | Exported Function | 0x0000000180001190 | 0x00001190
`HttpUpdateServiceConfiguration` | 43 (0x2b) | Exported Function | 0x0000000180005500 | 0x00005500
`HttpWaitForDemandStart` | 44 (0x2c) | Exported Function | 0x0000000180004e90 | 0x00004e90
`HttpQueryRequestQueueProperty` | 25 (0x19) | Exported Function | 0x0000000180004b40 | 0x00004b40
`HttpQueryRequestProperty` | 24 (0x18) | Exported Function | 0x0000000180004320 | 0x00004320
`HttpPrepareUrl` | 23 (0x17) | Exported Function | 0x00000001800036d0 | 0x000036d0
`HttpInitialize` | 22 (0x16) | Exported Function | 0x0000000180001ea0 | 0x00001ea0
`HttpAddUrl` | 2 (0x2) | Exported Function | 0x00000001800018d0 | 0x000018d0
`HttpAddUrlToUrlGroup` | 3 (0x3) | Exported Function | 0x00000001800034a0 | 0x000034a0
`HttpCancelHttpRequest` | 4 (0x4) | Exported Function | 0x0000000180003dd0 | 0x00003dd0
`HttpCloseRequestQueue` | 5 (0x5) | Exported Function | 0x0000000180004b10 | 0x00004b10
`HttpCloseServerSession` | 6 (0x6) | Exported Function | 0x0000000180003b10 | 0x00003b10
`HttpCloseUrlGroup` | 7 (0x7) | Exported Function | 0x00000001800034f0 | 0x000034f0
`HttpControlService` | 8 (0x8) | Exported Function | 0x00000001800059b0 | 0x000059b0
`HttpCreateHttpHandle` | 9 (0x9) | Exported Function | 0x0000000180001310 | 0x00001310
`HttpCreateRequestQueue` | 10 (0xa) | Exported Function | 0x00000001800013a0 | 0x000013a0
`HttpWaitForDisconnect` | 45 (0x2d) | Exported Function | 0x00000001800021e0 | 0x000021e0
`HttpCreateServerSession` | 11 (0xb) | Exported Function | 0x0000000180003b80 | 0x00003b80
`HttpDeclarePush` | 13 (0xd) | Exported Function | 0x0000000180003fb0 | 0x00003fb0
`HttpDelegateRequest` | 14 (0xe) | Exported Function | 0x0000000180004080 | 0x00004080
`HttpDelegateRequestEx` | 15 (0xf) | Exported Function | 0x00000001800040f0 | 0x000040f0
`HttpDeleteServiceConfiguration` | 16 (0x10) | Exported Function | 0x0000000180004ef0 | 0x00004ef0
`HttpEvaluateRequest` | 17 (0x11) | Exported Function | 0x00000001800041c0 | 0x000041c0
`HttpFindUrlGroupId` | 18 (0x12) | Exported Function | 0x0000000180003610 | 0x00003610
`HttpFlushResponseCache` | 19 (0x13) | Exported Function | 0x0000000180002150 | 0x00002150
`HttpGetCounters` | 20 (0x14) | Exported Function | 0x0000000180002300 | 0x00002300
`HttpGetExtension` | 21 (0x15) | Exported Function | 0x0000000180005af0 | 0x00005af0
`HttpCreateUrlGroup` | 12 (0xc) | Exported Function | 0x0000000180003560 | 0x00003560
`HttpWaitForDisconnectEx` | 46 (0x2e) | Exported Function | 0x00000001800046a0 | 0x000046a0


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: httpapi.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/f4ced65c41b4ff594fe786ac9b934e4681df0d686e0d76510eb02dbb3e36e949/detection/


## Possible Misuse

*The following table contains possible examples of `httpapi.dll` being misused. While `httpapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | ``Server: Microsoft-IIS/ 10.0 Microsoft-HTTPAPI/2.0`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


