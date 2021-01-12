---
title: System.EnterpriseServices.dll | Microsoft .NET Services Support Infrastructure
excerpt: What is System.EnterpriseServices.dll?
---

# System.EnterpriseServices.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.EnterpriseServices.dll`
* Description: Microsoft .NET Services Support Infrastructure
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `AEC7ACD95186430CC5109613ED4D0C79`
SHA1 | `126F4A2BE2AFC1146480D8F813A70D5BC6CB41CA`
SHA256 | `DD4A32B4A8B99158389E1ADB8ECCA42994E0DB0B1BC847D82BED169A16B3C17E`
SHA384 | `987E7914042191CCA1C4815E56B01A0FDA13CC8AEEDC3428B6C43F8EE0B96ACD4EA18B5DC1ED9C2441E041A6EAC27D7B`
SHA512 | `E5BA7DC001DC647FFDE7B6AF88B5B7F14150C5D5A68A09976140F96DD5FF812B0A315C0D37E51849D3B54C034D2E54892B853462B8FFEEEEFDDD5EB831D2D14F`
SSDEEP | `1536:8oJo2qzfdKDMb6vk3iy5oJY+26Aq47IAl62wiQN/mWG6G+cKp2zFJIDoeB1zQtEV:AVaRsgu8x8if`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `7B76A7D1102FDAFD083E852553B7E5C7214E84B2`
PE256 | `E95C30FFDAF682E5094ED584ECFF99B6DF9278BF6E3FE92871D5F4D19BF30983`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.EnterpriseServices.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/dd4a32b4a8b99158389e1adb8ecca42994e0db0b1bc847d82bed169a16b3c17e/detection


## Possible Misuse

*The following table contains possible examples of `System.EnterpriseServices.dll` being misused. While `System.EnterpriseServices.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /r:System.EnterpriseServices.dll /out:"#{output_file}" /target:library #{source_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /r:System.EnterpriseServices.dll /out:"#{output_file}" /target:library /keyfile:$env:Temp\key.snk #{source_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


