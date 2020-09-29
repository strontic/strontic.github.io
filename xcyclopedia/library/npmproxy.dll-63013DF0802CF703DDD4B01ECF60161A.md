---
title: npmproxy.dll | Network List Manager Proxy
excerpt: What is npmproxy.dll?
---

# npmproxy.dll 

* File Path: `C:\Windows\system32\npmproxy.dll`
* Description: Network List Manager Proxy

## Hashes

Type | Hash
-- | --
MD5 | `63013DF0802CF703DDD4B01ECF60161A`
SHA1 | `4400C3F8886818ED712E43A212A491A03FC4A425`
SHA256 | `F67A5D1145EE905236ED8DF8BD1C2545D24EB4B925AAD8643F53A7FBAB8C7591`
SHA384 | `E57616408E392CF6B04C797B8E29DEA3652F61070451918EB8F0CCD700CE130BE4DFA3821C3AEC372506EE94175FD106`
SHA512 | `5DB7543372364F09F96D971B79834EB6E270434FB4F4B2714D5242052C7A86E220F7E44F5A989F3EC7BACBDF9EF72D28136115F5FEEECD0D28B47D6045E3E878`
SSDEEP | `384:AU2nvYeg48PlXnkoR1Nmn8QHFUX6Zu7D73hmexWQv3mCLJhkXIwriVsWPNWWPNLU:caVPl8n8QWN73hm+/v3m+kTOV1BNL`
IMP | `35CC1E259B0BB239ED81C751C8D0CEE1`
PESHA1 | `4B9110AF503AAAF7DB2E213C7C2327894A4FDA16`
PE256 | `D1A6AE56A1CE9575AD9E4085B2F924314C0F954FD9C14DA4B21B2BF2C2D89C18`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x00000001800011e0 | 0x000011e0
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x0000000180001190 | 0x00001190
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x00000001800024a0 | 0x000024a0
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x00000001800024e0 | 0x000024e0
`GetProxyDllInfo` | 5 (0x5) | Exported Function | 0x0000000180002520 | 0x00002520


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: npfproxy.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/f67a5d1145ee905236ed8df8bd1c2545d24eb4b925aad8643f53a7fbab8c7591/detection/


## Possible Misuse

*The following table contains possible examples of `npmproxy.dll` being misused. While `npmproxy.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy.yar) | $s1 = "w%SystemRoot%\\System32\\npmproxy.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


