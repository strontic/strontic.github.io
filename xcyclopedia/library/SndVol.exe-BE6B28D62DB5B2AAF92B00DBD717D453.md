---
title: SndVol.exe | Volume Mixer
excerpt: What is SndVol.exe?
---

# SndVol.exe 

* File Path: `C:\WINDOWS\system32\SndVol.exe`
* Description: Volume Mixer

## Screenshot

![SndVol.exe](screenshots/SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `BE6B28D62DB5B2AAF92B00DBD717D453`
SHA1 | `C3868D5F073434C27E1FEC3DC681C2EC1A3B266C`
SHA256 | `3689A43858DB4845B5DA04EC5140E0616118D56A99F0C498ED5A90C4E9998CAB`
SHA384 | `578918C5A3F207449A7237A1BA902EBAE0C57DCDC2495D8D81FFFA4EAE0381F1CABA2E3B8EF4E20D4BDF2AE997F94FF3`
SHA512 | `777900BC98D6542B6142D9B8F28B129AFF36DC9A6E417BC508696042E2615A8594D5139D33987B5F537CBAC0FBD22E143E7FED05CF99B4B35B7EE9E53F144016`
SSDEEP | `3072:tEKC5GybtCSb6K4c8TklfXzHgasD8sazJeYEoqGcQDWkyzjbEyB7HbIrnvkSW:tEKCjCS2KR8ULgasD8se3cEbvy10rTW`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SndVol.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SndVol.exe](SndVol.exe-0D8208F039702F6D7FEA2FC002836408.md) | 30
[C:\windows\system32\SndVol.exe](SndVol.exe-DA0973777069BEFF69D9D89476340104.md) | 32
[C:\WINDOWS\SysWOW64\SndVol.exe](SndVol.exe-04930647DF45D1DBF56331644A17D1BC.md) | 27
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-2A724F091A5C7329F41CE3B99D420EBD.md) | 30
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-5AC83D3D18F9B6E1C5B78BD712661524.md) | 33
[C:\WINDOWS\SysWOW64\SndVol.exe](SndVol.exe-779D706DE5A512A06AF4933035970AE5.md) | 35
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3.md) | 30
[C:\windows\SysWOW64\SndVol.exe](SndVol.exe-8D40C30D3BA0030D55C1249C118D7F63.md) | 32
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-FC0BFFE396750BB00FAFAD0C62E7ACDA.md) | 29

## Possible Misuse

*The following table contains possible examples of `SndVol.exe` being misused. While `SndVol.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file SndVol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "sndvol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


