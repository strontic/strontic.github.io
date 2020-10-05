---
title: SgrmEnclave.dll | System Guard Runtime Monitor Enclave
excerpt: What is SgrmEnclave.dll?
---

# SgrmEnclave.dll 

* File Path: `C:\Windows\system32\SgrmEnclave.dll`
* Description: System Guard Runtime Monitor Enclave

## Hashes

Type | Hash
-- | --
MD5 | `A699D15E664D11530ADE964860897BEC`
SHA1 | `1BD97BBFF76117571AD40FB16CD4F793CDAB1BB3`
SHA256 | `DF0CA10001B8654C43ED1BBAD12C2CD0277F2469A4DFE42914DCB0226892A998`
SHA384 | `29DCCF98B989FCC416019576CFBA92A043B2027E18CB0B9FD6445455CEC95917A789901AD6937A2BB06D9F8A4E1FA7AA`
SHA512 | `A9CE31545D2B277E89A3A422D674909D2AE33A300BF2844A0D07F36AE67CB294BA967BC8F223F589DB2B7E47DF8922680C6FC1D593D8D73D81139E04DA451EFE`
SSDEEP | `6144:96/sYhT4mUFMDydLZdJmw51/GmL4EF15XrtLVO/WhW:z0T4mk8uJmwn1ZXrNVdE`
IMP | `2A6193075FECC3D6E7DE3B87CEA23C91`
PESHA1 | `2FE4D5B34534829EB8654470EECF488AF1122563`
PE256 | `140CCE904ADD929F6E2CC07B7A71EC9D88AB6EDB34293AAAD5910744FD9A8906`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`EngHostInitialize` | 8 | Exported Function
`EngHostGetSessionReport` | 7 | Exported Function
`EngHostNotify` | 9 | Exported Function
`EngHostShutdown` | 11 | Exported Function
`EngHostReinitialize` | 10 | Exported Function
`EngHostGetSessionCertificate` | 6 | Exported Function
`EngHostCreateAttestationClient` | 2 | Exported Function
`EngHostAttest` | 1 | Exported Function
`EngHostDestroyAttestationClient` | 3 | Exported Function
`EngHostGetRuntimeReport` | 5 | Exported Function
`EngHostDispatchThread` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SgrmEnclave.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.153 (WinBuild.160101.0800)
* Product Version: 10.0.19041.153
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/df0ca10001b8654c43ed1bbad12c2cd0277f2469a4dfe42914dcb0226892a998/detection/


## Possible Misuse

*The following table contains possible examples of `SgrmEnclave.dll` being misused. While `SgrmEnclave.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $fp1 = "SgrmEnclave" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


