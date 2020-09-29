---
title: AudioEndpointBuilder.dll | Windows Audio Endpoint Builder
excerpt: What is AudioEndpointBuilder.dll?
---

# AudioEndpointBuilder.dll 

* File Path: `C:\Windows\system32\AudioEndpointBuilder.dll`
* Description: Windows Audio Endpoint Builder

## Hashes

Type | Hash
-- | --
MD5 | `710A23DC7AB97C319D85DF1E0E617292`
SHA1 | `08BA929D5C5B00191DA42597EAF676E94FCEAEC7`
SHA256 | `C1F5DB110F6470150EB4240FD3491B3164E9C25EE9621057EBD15F12DE718856`
SHA384 | `2994099E36681788A40797280D37F43C120807CEB567442E82B8EB913CDD6E9FAAEEFD8B31B12F080159EF443ACF4111`
SHA512 | `D5A8C26EAD3420F4BA2E9FC9176DDBE3C8327E3C238AD0659831C2E44673BEB0E99EF68CD1FD38461BD5FF898868FE46A7FC219DE971416E1CFC4D6C81E55EAC`
SSDEEP | `12288:8KoPCK4ggjHD6BNW2xsshSu2dSFo8zKY7RT43ZJMhK1Xrn:8DCK43jHIxxP4SFo8zKY7RTuJMhK17`
IMP | `C7DF49C133F4B6BF924B85DF003024DE`
PESHA1 | `94E17592AB936F14FAE8D7586169BDBA779A76BA`
PE256 | `9D7D10F3E01A99A6E48BF1A0419DE56C8DA7AEA7C0A2EFC1DEDED49D86C4AD71`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ServiceMain` | 1 (0x1) | Exported Function | 0x0000000180015e70 | 0x00015e70
`SvchostPushServiceGlobals` | 2 (0x2) | Exported Function | 0x0000000180017240 | 0x00017240


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioepb.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/c1f5db110f6470150eb4240fd3491b3164e9c25ee9621057ebd15f12de718856/detection/


## Possible Misuse

*The following table contains possible examples of `AudioEndpointBuilder.dll` being misused. While `AudioEndpointBuilder.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_ryuk.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/win_mal_ryuk.yml) | `- '*\net.exe stop "audioendpointbuilder" *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


