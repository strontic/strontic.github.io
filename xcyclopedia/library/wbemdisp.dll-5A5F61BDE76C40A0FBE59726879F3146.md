---
title: wbemdisp.dll | WMI Scripting
excerpt: What is wbemdisp.dll?
---

# wbemdisp.dll 

* File Path: `C:\Windows\SysWOW64\wbem\wbemdisp.dll`
* Description: WMI Scripting

## Hashes

Type | Hash
-- | --
MD5 | `5A5F61BDE76C40A0FBE59726879F3146`
SHA1 | `7FA83B3BDA113F4236F472612A71DCBBA2434C58`
SHA256 | `B206237CA3E97CA1DDE7D9CB811C566CC0CB39966C3D7B635C574F89297307F5`
SHA384 | `0C095C782FCE1EEE5DBC307A2E857FBECEBFAFFCE3DC785534E6C99D9E2CCE7E7D545BF6DBF43921A413E72F59B1A48C`
SHA512 | `63AC36FD40B035906220FCA56A7B9F903FE2D3DA8A36EB21C402A2B684EA760B7B05B060A78337F0F927EA9BD96A0BA58AE5B0D0A5773C13F06DDA341D1F4C60`
SSDEEP | `3072:1Em9m+QmmVyA3GLt5GKpj05i5FrgVxRVq4zkZggAHAzqI106Tc0EitRA0UROcZHZ:1Evk5GejJriRzkZ/B1JtRAWcx`
IMP | `AA90109FBA6B8A8BF8515A9599A598C1`
PESHA1 | `60E2776E0104C7A4BC2D79D9AA4E04672D220CD2`
PE256 | `8359BB53D202B4FE44942F6D2CA6DC9C403FDC0015AB08198B91D159E1071761`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WBEMDISP.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b206237ca3e97ca1dde7d9cb811c566cc0cb39966c3d7b635c574f89297307f5/detection/


## Possible Misuse

*The following table contains possible examples of `wbemdisp.dll` being misused. While `wbemdisp.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemdisp.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


