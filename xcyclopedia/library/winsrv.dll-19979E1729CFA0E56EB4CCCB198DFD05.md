---
title: winsrv.dll | Multi-User Windows Server DLL
excerpt: What is winsrv.dll?
---

# winsrv.dll 

* File Path: `C:\Windows\system32\winsrv.dll`
* Description: Multi-User Windows Server DLL

## Hashes

Type | Hash
-- | --
MD5 | `19979E1729CFA0E56EB4CCCB198DFD05`
SHA1 | `A8C4D015032C054CA6AC99ED23457AF2316FF37F`
SHA256 | `7F2A683F28877562409D810946DDCA2F069715CDFB249602251DFA50065FFF7A`
SHA384 | `EAA023AB2B862303F458B2A07932FCA75B1700D75E3ACA7F9C38FC83F8E9A003477252F35E9F768283288A632B70497A`
SHA512 | `FD47DB4247A08F520D6C613D1615B8DEB88A0A09FB1CB14B3ABDF78F4C78694F6BEDF814C8C31D45A2192AF579022C1277BC77729DB751BC0826BB3FBE83E595`
SSDEEP | `384:3ex/FWtdLrJx6d0C/2n4gGvrUHObvWq7LgKfk06WNcpu/pVowB7Oufano5wACtQW:u1Fwf6CC/u4zUVuYotCtGBp`
IMP | `0D19B1428D247B1ECFBCAB1DE7B681EA`
PESHA1 | `E6FD7C0088734F77D94D8D6DCFE3FCF119073F14`
PE256 | `5C46F5E6E820B575B64D647B9E31AA7EA473FA2758FE02CAA99DB3FCAE789BB1`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`SrvEndTask` | 1 (0x1) | Exported Function | 0x0000000180001690 | 0x00001690
`UserCreateCallbackThread` | 2 (0x2) | Exported Function | 0x0000000180001800 | 0x00001800
`UserHardError` | 3 (0x3) | Exported Function | 0x0000000180001a30 | 0x00001a30
`UserServerDllInitialization` | 4 (0x4) | Exported Function | 0x0000000180001010 | 0x00001010


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winsrv.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/7f2a683f28877562409d810946ddca2f069715cdfb249602251dfa50065fff7a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\conhost.exe](conhost.exe-D752C96401E2540A443C599154FC6FA9.md) | 40

## Possible Misuse

*The following table contains possible examples of `winsrv.dll` being misused. While `winsrv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s1 = "system32\\winsrv.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


