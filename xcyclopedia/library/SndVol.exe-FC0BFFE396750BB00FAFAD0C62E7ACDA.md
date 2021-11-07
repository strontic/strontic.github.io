---
title: SndVol.exe | Volume Mixer
excerpt: What is SndVol.exe?
---

# SndVol.exe 

* File Path: `C:\Windows\SysWOW64\SndVol.exe`
* Description: Volume Mixer

## Screenshot

![SndVol.exe](screenshots/SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `FC0BFFE396750BB00FAFAD0C62E7ACDA`
SHA1 | `7B42015C44374C5AC44C82707E7D96DADEB73506`
SHA256 | `AEB8F9088436F40063D13C600CFDCCFF67D2682BA973CBBE83E8B2B76BFA6121`
SHA384 | `C4606421FC0711C7EF9838CDC4715A236BBA3B3036DF19C8CCE0D91727F3E17BF7C5AB7DC434294E4409CBD8037DC2E7`
SHA512 | `B4C85DEAA340C0743FFB86FE14F86AA545E056C2B15A8AD3BD020A3667F8DDD9A9EAC58988D5D2542733561851E7ED07A79B22A7B1F17D1FCEC00CC96CD8E025`
SSDEEP | `3072:wKMTzCPpReR4y9RBzqOEyAInlNrw2tWtBJwHjbEyB7HbI8O/Yxyy+yWo:wAyzZqmQ/Jxy10pwwto`

## Runtime Data

### Child Processes:
perfmon.exe

## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SndVol.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SndVol.exe](SndVol.exe-0D8208F039702F6D7FEA2FC002836408.md) | 33
[C:\WINDOWS\system32\SndVol.exe](SndVol.exe-BE6B28D62DB5B2AAF92B00DBD717D453.md) | 29
[C:\windows\system32\SndVol.exe](SndVol.exe-DA0973777069BEFF69D9D89476340104.md) | 32
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-2A724F091A5C7329F41CE3B99D420EBD.md) | 35
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-5AC83D3D18F9B6E1C5B78BD712661524.md) | 29
[C:\WINDOWS\SysWOW64\SndVol.exe](SndVol.exe-779D706DE5A512A06AF4933035970AE5.md) | 25
[C:\Windows\SysWOW64\SndVol.exe](SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3.md) | 24
[C:\windows\SysWOW64\SndVol.exe](SndVol.exe-8D40C30D3BA0030D55C1249C118D7F63.md) | 33

## Possible Misuse

*The following table contains possible examples of `SndVol.exe` being misused. While `SndVol.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file SndVol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "sndvol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


