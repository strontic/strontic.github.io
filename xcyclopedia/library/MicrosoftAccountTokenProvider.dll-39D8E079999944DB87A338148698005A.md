---
title: MicrosoftAccountTokenProvider.dll | Microsoft Account Token Provider
excerpt: What is MicrosoftAccountTokenProvider.dll?
---

# MicrosoftAccountTokenProvider.dll 

* File Path: `C:\Windows\SysWOW64\MicrosoftAccountTokenProvider.dll`
* Description: Microsoft Account Token Provider

## Hashes

Type | Hash
-- | --
MD5 | `39D8E079999944DB87A338148698005A`
SHA1 | `53BBED05EEB6B275E5FEB95F939D31A3FB9B2784`
SHA256 | `5426B804B78B43247AC6CDA00F35BB60296F08D84B6034277FA9A345BF4B9224`
SHA384 | `5D83D484F0DB915B5DDB5C54E458BFC056CE235D61F590400CC9C7ACB673EB4EA338A0988C2527B40522CDBCF9B4B861`
SHA512 | `936FC6FB7413BA94FC43CC8BE359B83F57082A94E71BD60CBCFD7E14C7D48961E94C047DF6092D57FE88FA886E87B8939AD18BA7563642067E23058BA69DA936`
SSDEEP | `3072:eWGRl++1Oo6Ec2nImlDNt8laqdVMwSZqkWzfK3q2Fq2iUX:eWIk+nh/CYqdVhY0zfSq2X`
IMP | `A102FC590522CA5812455F3719AE28C7`
PESHA1 | `A3E3877BDC7785C9247042F3C27365E422DD83AB`
PE256 | `DACA0A57CEDB30D8605818D885C4D01094F6AA5DAEFADD2BA14238D88F013E35`

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

* Original Filename: MicrosoftAccountTokenProvider.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/5426b804b78b43247ac6cda00f35bb60296f08d84b6034277fa9a345bf4b9224/detection/


## Possible Misuse

*The following table contains possible examples of `MicrosoftAccountTokenProvider.dll` being misused. While `MicrosoftAccountTokenProvider.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `ImageLoaded\|endswith: MicrosoftAccountTokenProvider.dll` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


