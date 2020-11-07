---
title: cliconfg.dll | SQL Client Configuration Utility DLL
excerpt: What is cliconfg.dll?
---

# cliconfg.dll 

* File Path: `C:\Windows\system32\cliconfg.dll`
* Description: SQL Client Configuration Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `2018592EF19BF65AD701AC836FF55D11`
SHA1 | `B7E6BBD8914BD654F665C581405160E46E9465F1`
SHA256 | `25EAC1A7AD0B7F62A251A9CCB90AEF80EDBCC8434C63E28690C153D7A8EFB97B`
SHA384 | `B7D7821A67B861C6E09C90962D1DE723A83F5D103F7E5E237E43FD96711D14AF4A9E910D7D2FB07622E24C0A19834B4E`
SHA512 | `B224870F2A2F3FBBFECB613A2A8750D1198A74D8FA49D5FAFE40AAE23732CF7F46AF045A39F0A9AA066D8B79D0FF3DD2F524B099B319FCF3ACD99B28D974716B`
SSDEEP | `1536:HOpesecEVenfnXCAjPu2D+UlJYyp5zFjMr2X:HHseonqoPuDUcgFjMro`
IMP | `448BA250441B2714E4FB5A2B490E55F1`
PESHA1 | `A9B9560EF5F7D5C86AF894B7B2D6A5148E091304`
PE256 | `E6503A696DB42E3A1DB7BDA6888AB8CD5D57DE6E391145A37FB142F81F77404C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ClientConfigureAddEdit` | 2 | Exported Function
`CPlApplet` | 1 | Exported Function
`OnInitDialogMain` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cliconfg.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/25eac1a7ad0b7f62a251a9ccb90aef80edbcc8434c63e28690c153d7a8efb97b/detection/


## Possible Misuse

*The following table contains possible examples of `cliconfg.dll` being misused. While `cliconfg.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x2 = "del /f /q %TEMP%\\setup.cab && cliconfg.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x1 = "cmd /c taskkill /im cliconfg.exe /f /t && del /f /q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


