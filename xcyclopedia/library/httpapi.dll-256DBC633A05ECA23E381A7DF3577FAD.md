---
title: httpapi.dll | HTTP Protocol Stack API
excerpt: What is httpapi.dll?
---

# httpapi.dll 

* File Path: `C:\Windows\SysWOW64\httpapi.dll`
* Description: HTTP Protocol Stack API

## Hashes

Type | Hash
-- | --
MD5 | `256DBC633A05ECA23E381A7DF3577FAD`
SHA1 | `EAE7F5C106CBBAB8240F909F45C12B69E357B6E0`
SHA256 | `DF807A4D67D77CA11E5356D19B6426EB1BD6D56E9F592AAD2C2F8DEA762DDE36`
SHA384 | `76B745499B324E9D9B56AA882C69AEB825C448D97F09BF2CF2AB3A0A3CE30408BBE1068F3165F363B9D48FF4E085ED0E`
SHA512 | `7F90E6442F10145196634B67C28B737C07B6408146D001A144E545FF9BF5868864E76D39F7594A477585E9A057203E009A9EA319716E3162C904B2062DCD9B18`
SSDEEP | `384:0q2gtQnCbNur6nCIRJfhbe28kXWta21FmUt4LgdYBLaccVk49lPOpWXJW6w707G:0q2AKFr6nmta294EdYBOccG+2mB+`
IMP | `044F27E22E1EDB346F50E8A0B8715005`
PESHA1 | `97DD5775625FD6F32C7BCBBA06922D54F3A3535B`
PE256 | `D365356477FB74FD5F334CBDC9153A16951C529A72AAAB6B36EF869915004D50`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`HttpAddFragmentToCache` | 1 (0x1) | Exported Function | 0x10004030 | 0x00004030
`HttpQueryServerSessionProperty` | 26 (0x1a) | Exported Function | 0x100027c0 | 0x000027c0
`HttpQueryServiceConfiguration` | 27 (0x1b) | Exported Function | 0x10004610 | 0x00004610
`HttpQueryUrlGroupProperty` | 28 (0x1c) | Exported Function | 0x100022b0 | 0x000022b0
`HttpReadFragmentFromCache` | 29 (0x1d) | Exported Function | 0x10004340 | 0x00004340
`HttpReceiveClientCertificate` | 30 (0x1e) | Exported Function | 0x10004410 | 0x00004410
`HttpReceiveHttpRequest` | 31 (0x1f) | Exported Function | 0x10003010 | 0x00003010
`HttpReceiveRequestEntityBody` | 32 (0x20) | Exported Function | 0x10003080 | 0x00003080
`HttpRemoveUrl` | 33 (0x21) | Exported Function | 0x10004d50 | 0x00004d50
`HttpRemoveUrlFromUrlGroup` | 34 (0x22) | Exported Function | 0x10002350 | 0x00002350
`HttpSendHttpResponse` | 35 (0x23) | Exported Function | 0x10003150 | 0x00003150
`HttpSendResponseEntityBody` | 36 (0x24) | Exported Function | 0x10003250 | 0x00003250
`HttpSetRequestQueueProperty` | 37 (0x25) | Exported Function | 0x10004480 | 0x00004480
`HttpSetServerSessionProperty` | 38 (0x26) | Exported Function | 0x10002850 | 0x00002850
`HttpSetServiceConfiguration` | 39 (0x27) | Exported Function | 0x100048e0 | 0x000048e0
`HttpSetUrlGroupProperty` | 40 (0x28) | Exported Function | 0x100023a0 | 0x000023a0
`HttpShutdownRequestQueue` | 41 (0x29) | Exported Function | 0x100044f0 | 0x000044f0
`HttpTerminate` | 42 (0x2a) | Exported Function | 0x10003700 | 0x00003700
`HttpUpdateServiceConfiguration` | 43 (0x2b) | Exported Function | 0x10004960 | 0x00004960
`HttpWaitForDemandStart` | 44 (0x2c) | Exported Function | 0x10004520 | 0x00004520
`HttpQueryRequestQueueProperty` | 25 (0x19) | Exported Function | 0x100042d0 | 0x000042d0
`HttpQueryRequestProperty` | 24 (0x18) | Exported Function | 0x10002ea0 | 0x00002ea0
`HttpPrepareUrl` | 23 (0x17) | Exported Function | 0x10002190 | 0x00002190
`HttpInitialize` | 22 (0x16) | Exported Function | 0x10003650 | 0x00003650
`HttpAddUrl` | 2 (0x2) | Exported Function | 0x10004cc0 | 0x00004cc0
`HttpAddUrlToUrlGroup` | 3 (0x3) | Exported Function | 0x10001f80 | 0x00001f80
`HttpCancelHttpRequest` | 4 (0x4) | Exported Function | 0x10002a20 | 0x00002a20
`HttpCloseRequestQueue` | 5 (0x5) | Exported Function | 0x100040e0 | 0x000040e0
`HttpCloseServerSession` | 6 (0x6) | Exported Function | 0x100026b0 | 0x000026b0
`HttpCloseUrlGroup` | 7 (0x7) | Exported Function | 0x10001fc0 | 0x00001fc0
`HttpControlService` | 8 (0x8) | Exported Function | 0x10004de0 | 0x00004de0
`HttpCreateHttpHandle` | 9 (0x9) | Exported Function | 0x10004110 | 0x00004110
`HttpCreateRequestQueue` | 10 (0xa) | Exported Function | 0x10004180 | 0x00004180
`HttpWaitForDisconnect` | 45 (0x2d) | Exported Function | 0x10003320 | 0x00003320
`HttpCreateServerSession` | 11 (0xb) | Exported Function | 0x10002720 | 0x00002720
`HttpDeclarePush` | 13 (0xd) | Exported Function | 0x10002b80 | 0x00002b80
`HttpDelegateRequest` | 14 (0xe) | Exported Function | 0x10002c10 | 0x00002c10
`HttpDelegateRequestEx` | 15 (0xf) | Exported Function | 0x10002cb0 | 0x00002cb0
`HttpDeleteServiceConfiguration` | 16 (0x10) | Exported Function | 0x10004590 | 0x00004590
`HttpEvaluateRequest` | 17 (0x11) | Exported Function | 0x10002d70 | 0x00002d70
`HttpFindUrlGroupId` | 18 (0x12) | Exported Function | 0x100020e0 | 0x000020e0
`HttpFlushResponseCache` | 19 (0x13) | Exported Function | 0x10004260 | 0x00004260
`HttpGetCounters` | 20 (0x14) | Exported Function | 0x100028f0 | 0x000028f0
`HttpGetExtension` | 21 (0x15) | Exported Function | 0x10004ec0 | 0x00004ec0
`HttpCreateUrlGroup` | 12 (0xc) | Exported Function | 0x10002040 | 0x00002040
`HttpWaitForDisconnectEx` | 46 (0x2e) | Exported Function | 0x10003390 | 0x00003390


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: httpapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/df807a4d67d77ca11e5356d19b6426eb1bd6d56e9f592aad2c2f8dea762dde36/detection/


## Possible Misuse

*The following table contains possible examples of `httpapi.dll` being misused. While `httpapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | ``Server: Microsoft-IIS/ 10.0 Microsoft-HTTPAPI/2.0`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


