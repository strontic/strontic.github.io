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

Function Name | Ordinal | Type
-- | -- | --
`HttpReceiveHttpRequest` | 31 | Exported Function
`HttpReceiveClientCertificate` | 30 | Exported Function
`HttpReceiveRequestEntityBody` | 32 | Exported Function
`HttpRemoveUrlFromUrlGroup` | 34 | Exported Function
`HttpRemoveUrl` | 33 | Exported Function
`HttpReadFragmentFromCache` | 29 | Exported Function
`HttpQueryRequestQueueProperty` | 25 | Exported Function
`HttpQueryRequestProperty` | 24 | Exported Function
`HttpQueryServerSessionProperty` | 26 | Exported Function
`HttpQueryUrlGroupProperty` | 28 | Exported Function
`HttpQueryServiceConfiguration` | 27 | Exported Function
`HttpSendHttpResponse` | 35 | Exported Function
`HttpUpdateServiceConfiguration` | 43 | Exported Function
`HttpTerminate` | 42 | Exported Function
`HttpWaitForDemandStart` | 44 | Exported Function
`HttpWaitForDisconnectEx` | 46 | Exported Function
`HttpWaitForDisconnect` | 45 | Exported Function
`HttpShutdownRequestQueue` | 41 | Exported Function
`HttpSetRequestQueueProperty` | 37 | Exported Function
`HttpSendResponseEntityBody` | 36 | Exported Function
`HttpSetServerSessionProperty` | 38 | Exported Function
`HttpSetUrlGroupProperty` | 40 | Exported Function
`HttpSetServiceConfiguration` | 39 | Exported Function
`HttpControlService` | 8 | Exported Function
`HttpCloseUrlGroup` | 7 | Exported Function
`HttpCreateHttpHandle` | 9 | Exported Function
`HttpCreateServerSession` | 11 | Exported Function
`HttpCreateRequestQueue` | 10 | Exported Function
`HttpCloseServerSession` | 6 | Exported Function
`HttpAddUrl` | 2 | Exported Function
`HttpAddFragmentToCache` | 1 | Exported Function
`HttpAddUrlToUrlGroup` | 3 | Exported Function
`HttpCloseRequestQueue` | 5 | Exported Function
`HttpCancelHttpRequest` | 4 | Exported Function
`HttpCreateUrlGroup` | 12 | Exported Function
`HttpGetCounters` | 20 | Exported Function
`HttpFlushResponseCache` | 19 | Exported Function
`HttpGetExtension` | 21 | Exported Function
`HttpPrepareUrl` | 23 | Exported Function
`HttpInitialize` | 22 | Exported Function
`HttpFindUrlGroupId` | 18 | Exported Function
`HttpDelegateRequest` | 14 | Exported Function
`HttpDeclarePush` | 13 | Exported Function
`HttpDelegateRequestEx` | 15 | Exported Function
`HttpEvaluateRequest` | 17 | Exported Function
`HttpDeleteServiceConfiguration` | 16 | Exported Function


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


