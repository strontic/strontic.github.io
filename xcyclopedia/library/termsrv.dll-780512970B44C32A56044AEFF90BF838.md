---
title: termsrv.dll | Remote Desktop Session Host Server Remote Connections Manager
excerpt: What is termsrv.dll?
---

# termsrv.dll 

* File Path: `C:\Windows\system32\termsrv.dll`
* Description: Remote Desktop Session Host Server Remote Connections Manager

## Hashes

Type | Hash
-- | --
MD5 | `780512970B44C32A56044AEFF90BF838`
SHA1 | `B931F3988E137DB78F0814CB9557977F7DF3BFA8`
SHA256 | `0AD0D87284D8C29F6DEEA82951F4EECE7EC94C58BBABBE1CF8DF75EE5AA47D1B`
SHA384 | `7D42314BA885DE04D68FA8FFBC3E1CF05CD81CB2C1D26ED64A62EC922D02FC893A5F9A2E03107AB4E11BC4A3A256A87E`
SHA512 | `64B15527AEEC6D098E7F336B2A41AEEF342E079BA60EF4BB3261203F2D26CC589074A5BE62A06527B06861193D1D267DE75682337B403FD64F8651BF9A589465`
SSDEEP | `24576:rBjohhYftdTMLf+qHbJdt3aw/zptiB5S:NjohCfPw7+q7ntqw/zpUB5S`
IMP | `7DF88E0684C200A3B664545C1D9E29ED`
PESHA1 | `6550BEE079269851E26A401CD1494BC2C11F340A`
PE256 | `E24778F04DD6093C46E608C4F4276E1A9A291107722588D9774795E0EBA12DC1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ServiceMain` | 1 | Exported Function
`SvchostPushServiceGlobals` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: termsrv.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/0ad0d87284d8c29f6deea82951f4eece7ec94c58bbabbe1cf8df75ee5aa47d1b/detection/


## Possible Misuse

*The following table contains possible examples of `termsrv.dll` being misused. While `termsrv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntlm_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_ntlm_rdp.yml) | `TargetName: TERMSRV*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | cmdkey /generic:TERMSRV/$Server /user:$User /pass:$Password | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


