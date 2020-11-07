---
title: cryptbase.dll | Base cryptographic API DLL
excerpt: What is cryptbase.dll?
---

# cryptbase.dll 

* File Path: `C:\Windows\SysWOW64\cryptbase.dll`
* Description: Base cryptographic API DLL

## Hashes

Type | Hash
-- | --
MD5 | `66BCA0AE7660609A50BA365E95EA982A`
SHA1 | `953412242BF16164307D358A38C791AEAAD795CA`
SHA256 | `9705F8BBA23044AA2F9AFF5579EFADA04AD6AE49ACF418CE72F2F296CBA61374`
SHA384 | `7C8574EC9F73E94D0DE9836307B087CA05F9B08794039106969F0512CD792910370726C7D65D686991C98E99EFAE5661`
SHA512 | `884E2BF9794013A39B781CF8A5B7F95DAFEDE8569C5823D82E40811A12F3DBC4647282ED978D715901FCB83BEAD39ACD78323EF3E06F3996BB47EF6745773149`
SSDEEP | `384:xTc/HnPF3GaXj65WKm2MWHIWF8VyDBRJOpJllNGt:hc/vtfunm2Nj8I1PqGt`
IMP | `0BE75B543C0F25B405F5788FEEC9F429`
PESHA1 | `C92DFE404827FF03FC58142E2E20B12E21150234`
PE256 | `8C6942B6FD678C5D6FA878D26368A41EDBF8DBA02B6FE1AB3E338368E4A7CD52`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SystemFunction001` | 1 | Exported Function
`SystemFunction002` | 2 | Exported Function
`SystemFunction003` | 3 | Exported Function
`SystemFunction004` | 4 | Exported Function
`SystemFunction005` | 5 | Exported Function
`SystemFunction028` | 6 | Exported Function
`SystemFunction029` | 7 | Exported Function
`SystemFunction034` | 8 | Exported Function
`SystemFunction036` | 9 | Exported Function
`SystemFunction040` | 10 | Exported Function
`SystemFunction041` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cryptbase.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/9705f8bba23044aa2f9aff5579efada04ad6ae49acf418ce72f2f296cba61374/detection/


## Possible Misuse

*The following table contains possible examples of `cryptbase.dll` being misused. While `cryptbase.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $c4 = "\\sysprep\\CRYPTBASE.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_netwire_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_netwire_rat.yar) | $s3 = "CRYPTBASE" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "C:\\WINDOWS\\system32\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "C:\\Windows\\SysNative\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "C:\\Windows\\system32\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s3 = "\\CryptBase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "CryptBase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_win_plugx.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_win_plugx.yar) | $s3 = "l%s\\sysprep\\CRYPTBASE.DLL" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_win_plugx.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_win_plugx.yar) | $s5 = "CRYPTBASE.DLL" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s5 = "CRYPTBASE.dll" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s6 = "loadFrom=\"%systemroot%\\system32\\sysprep\\cryptbase.DLL\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s4 = "System32\\migwiz\\CRYPTBASE.dll" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


