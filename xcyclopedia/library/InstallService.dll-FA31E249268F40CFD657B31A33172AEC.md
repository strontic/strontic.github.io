---
title: InstallService.dll | InstallService
excerpt: What is InstallService.dll?
---

# InstallService.dll 

* File Path: `C:\Windows\SysWOW64\InstallService.dll`
* Description: InstallService

## Hashes

Type | Hash
-- | --
MD5 | `FA31E249268F40CFD657B31A33172AEC`
SHA1 | `4497D20348BFE29BFF493A8CF97506DA926579E7`
SHA256 | `5312F8D5C5D43BF899A0A628DC1995DCD931FE720B12A107C9382A553E5FCC64`
SHA384 | `9B5CF759867D18117EE6ED8EAE9766FEED3484243C5243A9612ED8C5D1DC93F364436AB3D52858D7A81908AD01672857`
SHA512 | `C5A62FECDB2CC2DBEBD059A3238AA514D680DEFEDB4B19C0369BEB67B848309667EFB5F1EBD8EF31CCCFFF6D0A68B5E55FAC58B60EE8DBBA1E43543C05488CBF`
SSDEEP | `49152:rE5JwOI9g2qcsGCeGTZa+RAuw0hLWD5ytixELrFW9oFz9o4mrAWZvNlQ5qEGvg:yJwOUzuTZa+RrLWNytfLpW2Fz9o4mrAR`
IMP | `ACD5BE695D7681FEA987FE5FF9526398`
PESHA1 | `ED32DF57A1460CBE43781EDA7044DEE2911E2B45`
PE256 | `AF172ECB207877A8511E85C71FD1A3DC798C18E8592687AE153686774B6FEE0C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 4 | Exported Function
`ServiceMain` | 1 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function
`DllGetActivationFactory` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: InstallService.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/5312f8d5c5d43bf899a0a628dc1995dcd931fe720b12a107c9382a553e5fcc64/detection/


## Possible Misuse

*The following table contains possible examples of `InstallService.dll` being misused. While `InstallService.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "InstallService" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


