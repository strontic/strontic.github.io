---
title: SndVol.exe | Volume Mixer
---

# SndVol.exe 

* File Path: `C:\Windows\system32\SndVol.exe`
* Description: Volume Mixer

## Screenshot

![SndVol.exe](screenshots/SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `9877E28BD78EFAAF4813C84D48CC56C4`
SHA1 | `56F9639C87C4D9E08C92D115F4EF7955697FE77D`
SHA256 | `5BE12686C75A1F034EAC11031A7440EA40731298DF5F7296B2C5462028793BF3`
SHA384 | `3498A8467E84A6FA53064C97A79B09E2E5933416AF3DBDDDEF02D37DB1CEF84411BDC979C9289B4EF38423EE8CC2EE00`
SHA512 | `B6E504BC4E8336D4FD8733594DEB8CE6165DB48E978DB1C1538AE23C5F17AA24DAAABE6F3DF2819BCE950618B59AE0115F6C37F7A9841D1FF38D471B56397AF8`
SSDEEP | `6144:M/k6mogoeAAVpq4jpExOd3n3u8Ggu0kr/2rzIBqncyXy10X:r6pTjA7q4jpEcX3upgvXyM`

## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SndVol.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SndVol.exe` being misused. While `SndVol.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | 		description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file SndVol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | 		filename == "sndvol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


