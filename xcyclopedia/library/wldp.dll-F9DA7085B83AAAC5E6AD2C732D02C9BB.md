---
title: wldp.dll | Windows Lockdown Policy
excerpt: What is wldp.dll?
---

# wldp.dll 

* File Path: `C:\Windows\SysWOW64\wldp.dll`
* Description: Windows Lockdown Policy

## Hashes

Type | Hash
-- | --
MD5 | `F9DA7085B83AAAC5E6AD2C732D02C9BB`
SHA1 | `FABCBDA52D727B4E39D8070FE548267AFDB9CC58`
SHA256 | `667E1E1D7C290FF579039EA8A5E653115B50983F2CA7CEF4B76A3ED1272CF523`
SHA384 | `7DC6961840AFF00BA11B3BAB2FACECC192A87F50551E5393521735B46708DF0CE6C1419876648EC5D22373F4D4CAB709`
SHA512 | `A0441424D82002E6E96FF66688F69DB31D89C230FBCC4B42ABBCBBE6829C2D5E5FAAFAB5189BA2AC1066992663D8E6C2E2B513E4474A65C0DE3B7885349462C0`
SSDEEP | `3072:Unw+VlCauk7a4zPMAw78SgUm8wyptuEEpcEZ0ah4IyzU5pWHArQ50dH0e0g:MwfGPkAw404vZ/4J`
IMP | `FA2A9E6F2FAB2E469C3725D77D770E63`
PESHA1 | `AAB2246F648BDB49343AF61E7820CA5FDE3DF4B4`
PE256 | `7739BF2128B14A2AF1B7187FB0498AE38C7822F5929A4EA7AA9C7FC658B7F6DC`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WldpAddDeveloperCertificateForDynamicCodeTrust` | 5 (0x5) | Exported Function | 0x10013990 | 0x00013990
`WldpSetDynamicCodeTrust` | 21 (0x15) | Exported Function | 0x10014b10 | 0x00014b10
`WldpResetSecurityWatermarkState` | 19 (0x13) | Exported Function | 0x100170e0 | 0x000170e0
`WldpQueryWindowsLockdownRestriction` | 3 (0x3) | Exported Function | 0x100131d0 | 0x000131d0
`WldpQueryWindowsLockdownMode` | 2 (0x2) | Exported Function | 0x10007a00 | 0x00007a00
`WldpQuerySecurityPolicy` | 18 (0x12) | Exported Function | 0x10014a80 | 0x00014a80
`WldpQueryDynamicCodeTrust` | 17 (0x11) | Exported Function | 0x10014a20 | 0x00014a20
`WldpIsDynamicCodePolicyEnabled` | 16 (0x10) | Exported Function | 0x100149b0 | 0x000149b0
`WldpIsDebugAllowed` | 15 (0xf) | Exported Function | 0x100147e0 | 0x000147e0
`WldpSetDynamicCodeTrust2` | 20 (0x14) | Exported Function | 0x10014ae0 | 0x00014ae0
`WldpIsClassInApprovedList` | 14 (0xe) | Exported Function | 0x10014020 | 0x00014020
`WldpIsAllowedEntryPoint` | 13 (0xd) | Exported Function | 0x10015f30 | 0x00015f30
`WldpGetLockdownPolicy` | 12 (0xc) | Exported Function | 0x100070c0 | 0x000070c0
`WldpEnableDeveloperMode` | 11 (0xb) | Exported Function | 0x10013d40 | 0x00013d40
`WldpDisableDeveloperMode` | 10 (0xa) | Exported Function | 0x10013c30 | 0x00013c30
`WldpCheckWcosDeviceEncryptionSecure` | 9 (0x9) | Exported Function | 0x10017170 | 0x00017170
`WldpCheckSecurityWatermarkState` | 8 (0x8) | Exported Function | 0x10016d40 | 0x00016d40
`WldpCheckRetailConfiguration` | 7 (0x7) | Exported Function | 0x10007b50 | 0x00007b50
`WldpCheckDeviceEncryptionNotStarted` | 6 (0x6) | Exported Function | 0x10017110 | 0x00017110
`WldpIsAppApprovedByPolicy` | 1 (0x1) | Exported Function | 0x10006c00 | 0x00006c00
`WldpSetWindowsLockdownRestriction` | 4 (0x4) | Exported Function | 0x10013230 | 0x00013230


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wldp.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/667e1e1d7c290ff579039ea8a5e653115b50983f2ca7cef4b76a3ed1272cf523/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wldp.dll](wldp.dll-8482B38653241529ABB357FCB4369B7F.md) | 38




MIT License. Copyright (c) 2020 Strontic.


