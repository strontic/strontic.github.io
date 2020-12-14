---
title: SndVol.exe | Volume Mixer
excerpt: What is SndVol.exe?
---

# SndVol.exe 

* File Path: `C:\WINDOWS\SysWOW64\SndVol.exe`
* Description: Volume Mixer

## Screenshot

![SndVol.exe](screenshots/SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `779D706DE5A512A06AF4933035970AE5`
SHA1 | `19EEE3177E73CD9500CD91653B05F41A8432EC75`
SHA256 | `1B436AB7D1C60434605AE3AB18F8F9C4D89496CFD07F3295FDFB93F8E1058929`
SHA384 | `49236ACC14A580B9072C16C06A4A0533985B0072C0D7A6B47CF18CEF470102A32F15F0B8B43A991F42193AA5942F155D`
SHA512 | `5D33688704D5AE6BA33B351224AAC2896EECDE811968CA4D668BE48BBD48F33E39E12256A4A04B0EEC172F9A9D2C1BB816F08950A0B150F3BC1D524A6F6AAD6E`
SSDEEP | `3072:e3vE5+T1v9ImTX+8AcbJovI6GuQgQxj1Vp4/7Do9zjbEyB7HbIdMXssz:e38GvTX+fcbiv7//vy10dMb`

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
[C:\WINDOWS\system32\SndVol.exe](SndVol.exe-BE6B28D62DB5B2AAF92B00DBD717D453.md) | 35
[C:\windows\system32\SndVol.exe](SndVol.exe-DA0973777069BEFF69D9D89476340104.md) | 32
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-2A724F091A5C7329F41CE3B99D420EBD.md) | 29
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3.md) | 30
[C:\windows\SysWOW64\SndVol.exe](SndVol.exe-8D40C30D3BA0030D55C1249C118D7F63.md) | 32
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-FC0BFFE396750BB00FAFAD0C62E7ACDA.md) | 25

## Possible Misuse

*The following table contains possible examples of `SndVol.exe` being misused. While `SndVol.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file SndVol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "sndvol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


