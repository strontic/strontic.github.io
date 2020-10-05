---
title: mmcndmgr.dll | MMC Node Manager DLL
excerpt: What is mmcndmgr.dll?
---

# mmcndmgr.dll 

* File Path: `C:\Windows\system32\mmcndmgr.dll`
* Description: MMC Node Manager DLL

## Hashes

Type | Hash
-- | --
MD5 | `1CC8066D5AED06434FB58480D3F67E1B`
SHA1 | `35FDEB0FD19DECEB09BD3661D93FBF54AB43342B`
SHA256 | `C7769411D0B881AA6EF6F94AE5E1DA8DB2B4AA675AA337FD706EE60ECE98E7C0`
SHA384 | `5494A5664231B66D146A563E459EFE115E6596B2BB8A71D272F7DBB41D16DA3055FF3A34E310645341A637C9F61F54EC`
SHA512 | `5E08D4DF9B9EDCC09787F722F9D813AA0C23EFF444093B67BAB34A5CB0CA3A0363F2949C51EF79DA6FF6026A3C14DD077053AFB1E1870A9BF989F4FF95F3307B`
SSDEEP | `24576:Vls4DoUVHn3AsuWTybMoUihIBzhYDiiQ8Q4r9OVqwn7PAM7:VShUVHn3Asx24on0h7FuOPb7`
IMP | `DF9D022F0AC7744B2B5C9D0739D655DE`
PESHA1 | `C72E9A2D894606026188DA0A28B176541F198C93`
PE256 | `3CB5B5A6D6485A271A692DA3B18A0256D6B6A740F350AD894D927C2A59E42F66`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 4 | Exported Function
`DllUnregisterServer` | 5 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`CreateExecutivePlatform` | 1 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mmcndmgr.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/c7769411d0b881aa6ef6f94ae5e1da8db2b4aa675aa337fd706ee60ece98e7c0/detection/


## Possible Misuse

*The following table contains possible examples of `mmcndmgr.dll` being misused. While `mmcndmgr.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_win_privesc.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_win_privesc.yar) | $s2 = "(([System.IconExtractor]::Extract(\"mmcndmgr.dll\", 126, $true)).ToBitMap()).Save($env:temp + \"\\Other.png\")    " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


