---
title: wab32res.dll | Microsoft (R) Contacts DLL
excerpt: What is wab32res.dll?
---

# wab32res.dll 

* File Path: `C:\Program Files\Common Files\System\wab32res.dll`
* Description: Microsoft (R) Contacts DLL

## Hashes

Type | Hash
-- | --
MD5 | `9AF0262134F16517DF32DA904FD1EFBC`
SHA1 | `6845E3F76DAE9080712F2533F3FB5D25AD30C440`
SHA256 | `230E8223FF56C838923F05949621702B58C87A788E64ADBEFC2E5EB9C0AE3DD7`
SHA384 | `DE0C766854D3035F63F417EF94DAB80E8696AA43A168D30A200BEC31652CECED3F28029FC112B48C433EE8DEDD057135`
SHA512 | `4228C0470B085479DA0EAA139733E74D0BEC87CC4DC81E2DE03EFAD0AEF1C6EC979A415780FC886AE1D81400D977E3B5A5D1F126CAD70E4F8AD26AE824476448`
SSDEEP | `12288:+Tx5KRZ18xtSy2567TW7NG96FEMed/ayvTd2erR2567TWTTx5KRZIEMm:7mxtSyqiW7NGcfpAR2oqiWQSm`
IMP | `n/a`
PESHA1 | `A68072DD695B4BB9E9341D790EF93240D3A2E42E`
PE256 | `33AE8A9AF9420942F838B0D7AF7440DD4315F2917F495D7A720AB6D1871AC45F`


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WAB32res.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/230e8223ff56c838923f05949621702b58c87a788e64adbefc2e5eb9c0ae3dd7/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Mail\wab.exe](wab.exe-58CDC40AE57D2F2C6FC787BF66BAA1A6.md) | 35
[C:\Program Files\Windows Mail\wab.exe](wab.exe-1763CB1756D4DF101F71DBC360C875E1.md) | 35

## Possible Misuse

*The following table contains possible examples of `wab32res.dll` being misused. While `wab32res.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | description = "Detects KeyBoy Loader wab32res.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s3 = "%s\\wab32res.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


