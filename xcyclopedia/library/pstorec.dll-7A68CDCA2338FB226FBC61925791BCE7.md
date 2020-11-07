---
title: pstorec.dll | Deprecated Protected Storage COM interfaces
excerpt: What is pstorec.dll?
---

# pstorec.dll 

* File Path: `C:\Windows\system32\pstorec.dll`
* Description: Deprecated Protected Storage COM interfaces

## Hashes

Type | Hash
-- | --
MD5 | `7A68CDCA2338FB226FBC61925791BCE7`
SHA1 | `B9EB5C2D6C1E67093C9C709064B50D5EEBEA640A`
SHA256 | `FDF77E40FCEBE6E1DB2E6679EAD423962C0359D24B9C91EFBFE1BC8675D36392`
SHA384 | `D06ABE2A9EF4B10BE4B13F88751372E1D01D008D9FA6BDB3CAEC0AA35902B4F1875E23364FDA989DBD14C38F9FC0CF01`
SHA512 | `1749FFED95F726C53ACEE5F2E3D4A4FF2913F77E267C72F535A3426E988B5C92ABF156457213A49E41378B6EF9044E73DD6776BA2A14889F0F206664DFEBAAD9`
SSDEEP | `192:2BTOzZjSA7if+EcbZLWSvwaWDLq6sEQL6gqyz5sqAp3M:2BTsZj8KZLWSvwaWa6eLPj6qAtM`
IMP | `92E98CCD6AA108E386042837A53C42F8`
PESHA1 | `E041335212E972D6FCD1348869D69A4BBC58F782`
PE256 | `C70D48BE23152A8DA2D71D0713FFF69AE9EA7D53058167D6C311464D171EF7EF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`PStoreCreateInstance` | 5 | Exported Function
`PStoreEnumProviders` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pstorec.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/fdf77e40fcebe6e1db2e6679ead423962c0359d24b9c91efbfe1bc8675d36392/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\pstorec.dll](pstorec.dll-07C04745324D02193A39D9DED5DD00AC.md) | 58

## Possible Misuse

*The following table contains possible examples of `pstorec.dll` being misused. While `pstorec.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $x6 = "Unable to obtain handle to PStoreCreateInstance in pstorec.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


