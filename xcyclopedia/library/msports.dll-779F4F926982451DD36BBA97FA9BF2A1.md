---
title: msports.dll | Ports Class Installer
excerpt: What is msports.dll?
---

# msports.dll 

* File Path: `C:\Windows\SysWOW64\msports.dll`
* Description: Ports Class Installer

## Hashes

Type | Hash
-- | --
MD5 | `779F4F926982451DD36BBA97FA9BF2A1`
SHA1 | `D3489742968228CF53B83F8C90AF6F79AA4DE953`
SHA256 | `DBBC37E32D66A27F1F4A174B3F237859EF1D770260C836D9856035D988350B11`
SHA384 | `A23FFEBC291DAB81D7A360DA8F02F131CCA3F0118EAE6923AA54F766222C79E061F5C2315B0F44577EC36AECFC2DE4D8`
SHA512 | `2763A5BC6B5C95D1A42B14CA316E9987B1CBC41D0F165A02FE9448709E1D44201881B231C198583BDBA71981E3292B2225051C350F81C6CAA2D1F270382FD079`
SSDEEP | `768:KccqW2t9kh0S3PB1Mx62HPHWBwmSsI5qpM5PImkO0mzmjNd+GGzIiK00P:zc+yfB1M4Y2PM5qQImkO0oed+GGzIiK0`
IMP | `B17185807711D93055FF750B4EA1D65E`
PESHA1 | `CD31A9656DDF72855A86D4215D98CB51EBE31285`
PE256 | `FFBFA5A4D687F36643A0E4A7522BEC07EF6BFCBF1AE4E2F75003FBEB5AD3710D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ComDBClaimNextFreePort` | 1 (0x1) | Exported Function | 0x70104490 | 0x00004490
`ComDBClaimPort` | 2 (0x2) | Exported Function | 0x70104580 | 0x00004580
`ComDBClose` | 3 (0x3) | Exported Function | 0x70104270 | 0x00004270
`ComDBGetCurrentPortUsage` | 4 (0x4) | Exported Function | 0x70104390 | 0x00004390
`ComDBOpen` | 5 (0x5) | Exported Function | 0x70103f80 | 0x00003f80
`ComDBReleasePort` | 6 (0x6) | Exported Function | 0x70104660 | 0x00004660
`ComDBResizeDatabase` | 7 (0x7) | Exported Function | 0x701046e0 | 0x000046e0
`ParallelPortPropPageProvider` | 8 (0x8) | Exported Function | 0x70107080 | 0x00007080
`PortsClassInstaller` | 9 (0x9) | Exported Function | 0x70104880 | 0x00004880
`SerialDisplayAdvancedSettings` | 10 (0xa) | Exported Function | 0x70101b50 | 0x00001b50
`SerialPortPropPageProvider` | 11 (0xb) | Exported Function | 0x70106250 | 0x00006250


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsPorts.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/dbbc37e32d66a27f1f4a174b3f237859ef1d770260c836d9856035d988350b11/detection/


## Possible Misuse

*The following table contains possible examples of `msports.dll` being misused. While `msports.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_upatre_oct15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_upatre_oct15.yar) | $s0 = "msports.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


