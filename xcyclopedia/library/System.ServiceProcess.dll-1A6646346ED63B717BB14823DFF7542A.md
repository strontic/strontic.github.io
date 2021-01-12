---
title: System.ServiceProcess.dll | .NET Framework
excerpt: What is System.ServiceProcess.dll?
---

# System.ServiceProcess.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.ServiceProcess.dll`
* Description: .NET Framework
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `1A6646346ED63B717BB14823DFF7542A`
SHA1 | `C94A9B5320E099B34A29A4945FDF1F0C57B4099E`
SHA256 | `DF410C53A7EF75D96ECA5C0664227BC7201991A6C457C101D3A3670AE7719896`
SHA384 | `25F54F7B4602958A4E142A6C70ED9E28EF8A86A90D8EE9D6FC65E64FA17343AE516AE019DE6C93B737508D44E80D0EFB`
SHA512 | `8C8739E24E1F09B8609D6ABAF99AE8DF5FF1C0DF69AF6D6368F0C583ABC6DF03EBEE14B36507A5C8776FE7748C4AECE7697B4A4EB7DB66EBF1D320BE80FD8029`
SSDEEP | `768:3g8F0Z4utb2Kyh74iJZ1ih8CnjFxaltQ1GhdE2QaXeMqWkx8+Q5ioK43:3K3buB4rrjFmQqdrQaO+l+KiFo`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `A41B50632F77B561459045BCB09DEC2708E199C3`
PE256 | `F4C96E354E54F60CB84C00C576BD9AB5D274725BAB5BD4EBC49C1745A1DF5FC5`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.ServiceProcess.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/df410c53a7ef75d96eca5c0664227bc7201991a6c457c101d3a3670ae7719896/detection


## Possible Misuse

*The following table contains possible examples of `System.ServiceProcess.dll` being misused. While `System.ServiceProcess.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "ServiceController[] kQmRu=System.ServiceProcess.ServiceController.GetServices();" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s12 = "<%@ import Namespace=\"System.ServiceProcess\"%>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


