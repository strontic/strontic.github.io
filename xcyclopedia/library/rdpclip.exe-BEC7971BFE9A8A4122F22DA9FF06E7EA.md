---
title: rdpclip.exe | RDP Clipboard Monitor
excerpt: What is rdpclip.exe?
---

# rdpclip.exe 

* File Path: `C:\WINDOWS\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `BEC7971BFE9A8A4122F22DA9FF06E7EA`
SHA1 | `6F77B42E17E19148B5064C537F8169E342E60132`
SHA256 | `01DC9FD40E8206DA63A9B921383348ECC3EBB7B72E38E0A1E5BEFA292A793085`
SHA384 | `2520FAAF8202AAB292ACD388A16DFB9F1A50FA369A71BE9E7843AEE3A2832AB1D0F14F64240D8716BA0854BEAFF474F4`
SHA512 | `8A58631CAE2FAF049CC472DA680963771B4684A5ACA8DF5EEB497D528C7816CE487ED7989F1B2231112F3A611FF81744C0B547E784283E7E3891C0698B143A1E`
SSDEEP | `12288:L3nDy/JHSjbkV8jeP2mLnBLxJw1AJQUTntdKXb5zMsoSe9AW:TDyxHSjbkV8je+mLBLxJw1SfdKXbcSe9`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image: '*\rdpclip.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


