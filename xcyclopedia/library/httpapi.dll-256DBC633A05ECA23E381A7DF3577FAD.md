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

Function Name | Ordinal | Type
-- | -- | --
`HttpAddFragmentToCache` | 1 | Exported Function
`HttpQueryServerSessionProperty` | 26 | Exported Function
`HttpQueryServiceConfiguration` | 27 | Exported Function
`HttpQueryUrlGroupProperty` | 28 | Exported Function
`HttpReadFragmentFromCache` | 29 | Exported Function
`HttpReceiveClientCertificate` | 30 | Exported Function
`HttpReceiveHttpRequest` | 31 | Exported Function
`HttpReceiveRequestEntityBody` | 32 | Exported Function
`HttpRemoveUrl` | 33 | Exported Function
`HttpRemoveUrlFromUrlGroup` | 34 | Exported Function
`HttpSendHttpResponse` | 35 | Exported Function
`HttpSendResponseEntityBody` | 36 | Exported Function
`HttpSetRequestQueueProperty` | 37 | Exported Function
`HttpSetServerSessionProperty` | 38 | Exported Function
`HttpSetServiceConfiguration` | 39 | Exported Function
`HttpSetUrlGroupProperty` | 40 | Exported Function
`HttpShutdownRequestQueue` | 41 | Exported Function
`HttpTerminate` | 42 | Exported Function
`HttpUpdateServiceConfiguration` | 43 | Exported Function
`HttpWaitForDemandStart` | 44 | Exported Function
`HttpQueryRequestQueueProperty` | 25 | Exported Function
`HttpQueryRequestProperty` | 24 | Exported Function
`HttpPrepareUrl` | 23 | Exported Function
`HttpInitialize` | 22 | Exported Function
`HttpAddUrl` | 2 | Exported Function
`HttpAddUrlToUrlGroup` | 3 | Exported Function
`HttpCancelHttpRequest` | 4 | Exported Function
`HttpCloseRequestQueue` | 5 | Exported Function
`HttpCloseServerSession` | 6 | Exported Function
`HttpCloseUrlGroup` | 7 | Exported Function
`HttpControlService` | 8 | Exported Function
`HttpCreateHttpHandle` | 9 | Exported Function
`HttpCreateRequestQueue` | 10 | Exported Function
`HttpWaitForDisconnect` | 45 | Exported Function
`HttpCreateServerSession` | 11 | Exported Function
`HttpDeclarePush` | 13 | Exported Function
`HttpDelegateRequest` | 14 | Exported Function
`HttpDelegateRequestEx` | 15 | Exported Function
`HttpDeleteServiceConfiguration` | 16 | Exported Function
`HttpEvaluateRequest` | 17 | Exported Function
`HttpFindUrlGroupId` | 18 | Exported Function
`HttpFlushResponseCache` | 19 | Exported Function
`HttpGetCounters` | 20 | Exported Function
`HttpGetExtension` | 21 | Exported Function
`HttpCreateUrlGroup` | 12 | Exported Function
`HttpWaitForDisconnectEx` | 46 | Exported Function


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


