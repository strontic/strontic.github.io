---
title: VSSVC.exe | Microsoft Volume Shadow Copy Service
---

# VSSVC.exe 

* File Path: `C:\Windows\system32\VSSVC.exe`
* Description: Microsoft Volume Shadow Copy Service

## Hashes

Type | Hash
-- | --
MD5 | `532EDECFB487E57C5B8AAF5A7AC83B30`
SHA1 | `8CD4F1106EE61B15C915BF30FA160C3F3FACAFF8`
SHA256 | `6E967CBE87F41F1D5D102DFFAD46F13129E1B0FC7FD3920F3CE92E45E978E929`
SHA384 | `179479B293140DEC6BD78B771D11446EC3CEF0476E9AA98866C30CCFBDD5559A726A57B5BC73F6DEB5A568E6C2611F2D`
SHA512 | `099631C7EBE0EBA730AB46806F1C0E5AC1D26ABF9F63FB8488DF6802895C2832DF6B03661DCFF522398BAD10FF5CCCB7FC86C5B0F9B7F894C017FB46B4CA038B`
SSDEEP | `24576:IsVx+g9o1x+2kivU4REd//XpVPcFSNptbQEGNTObiUcA:px+g9m+EREd//XpVEFgtbQEGNTeiU`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


