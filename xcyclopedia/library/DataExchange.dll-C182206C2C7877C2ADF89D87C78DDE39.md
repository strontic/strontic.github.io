---
title: DataExchange.dll | Data exchange
excerpt: What is DataExchange.dll?
---

# DataExchange.dll 

* File Path: `C:\Windows\SysWOW64\DataExchange.dll`
* Description: Data exchange

## Hashes

Type | Hash
-- | --
MD5 | `C182206C2C7877C2ADF89D87C78DDE39`
SHA1 | `C8ADC798EB418D11C0AB2F62D25853791EB5CB86`
SHA256 | `3F0948C53C09907D300592B70392DB9B80AC395436AFE257B30E80C658A863E6`
SHA384 | `6DFB24999A3490C8931B6A730414D7BFFDF2BF2E99321F3585C6C6009EF6E772AEA4430D7E40478864FF3FA46E59EA43`
SHA512 | `A80B2A02DFD94C01F965EE0001BD308146C663D765BEAA0D3AB4AD1FAB72BBC31552E7134747E778B0F6A2712E112F0E626DDFE219A8666F22153B38818C5DFA`
SSDEEP | `3072:6+82jXcfvnD/dVCeG57CGJsYvqBF8LrfR5+Muv2h1OfH6+:6T7fvD/dVz1aqBF8HJgvgIH6+`
IMP | `3AFA5E90E5E1914AE49B3285E1A065CF`
PESHA1 | `308BEAECE71899FBBFFEFF24C099AAA23F737FFB`
PE256 | `1D9C9E46C6AB0B29EE01B97FED8B4F81F1DBA70B76BECFE7ADD22512222D784D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 3 | Exported Function
`DllGetActivationFactory` | 2 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DataExchange.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3f0948c53c09907d300592b70392db9b80ac395436afe257b30e80c658a863e6/detection/


## Possible Misuse

*The following table contains possible examples of `DataExchange.dll` being misused. While `DataExchange.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_apt_muddywater_dnstunnel.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_apt_muddywater_dnstunnel.yml) | `- 'DataExchange.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


