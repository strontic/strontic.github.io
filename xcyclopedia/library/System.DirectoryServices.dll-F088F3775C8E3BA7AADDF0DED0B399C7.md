---
title: System.DirectoryServices.dll | .NET Framework
excerpt: What is System.DirectoryServices.dll?
---

# System.DirectoryServices.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.DirectoryServices.dll`
* Description: .NET Framework
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `F088F3775C8E3BA7AADDF0DED0B399C7`
SHA1 | `A922F2EFF86DF1D2A641121A0A46B3046DA5814F`
SHA256 | `BBCFFC9F0F819D46017FBCDBDF7970B26D027C8DBCCB796C9C2080F75ABBBB14`
SHA384 | `CB89C1D426E44D967B9334455AB550591545F69EF9C20BCFEAEFF7B2EADF6576C450F0C80162F6CBD42417A827CB8A0A`
SHA512 | `B80B111F4187E0C56F0B4882140A264FF764E9A4FD85A521500FF10BD85998E90935A7483F03B9E076D3EAC58EF8228B81D857E7A8E30C2880E0E0D3BCAF7D8E`
SSDEEP | `1536:IfpNF3JFTFx6o4RJAJUK7172cRdAblQY3xBIeRxTDhN1DzM4/Za:IfpNF3VQuUK717TRglQOxBIwNdz/Ra`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `BA115F8C476C9815371AD30B7479101900556064`
PE256 | `7801552352CD840235D7DB46CA34C8A0228AB7737C77D1DD014C3A9C4A4436DB`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.DirectoryServices.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/bbcffc9f0f819d46017fbcdbdf7970b26d027c8dbccb796c9c2080f75abbbb14/detection


## Possible Misuse

*The following table contains possible examples of `System.DirectoryServices.dll` being misused. While `System.DirectoryServices.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | [System.Reflection.Assembly]::LoadWithPartialName("System.DirectoryServices.Protocols") \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | $di = new-object System.DirectoryServices.Protocols.LdapDirectoryIdentifier("#{domain}",389) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | $conn = new-object System.DirectoryServices.Protocols.LdapConnection($di, $credz, [System.DirectoryServices.Protocols.AuthType]::#{auth}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | [System.Reflection.Assembly]::LoadWithPartialName("System.DirectoryServices.Protocols") \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | $di = new-object System.DirectoryServices.Protocols.LdapDirectoryIdentifier("#{domain}",389) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | $conn = new-object System.DirectoryServices.Protocols.LdapConnection($di, $credz, [System.DirectoryServices.Protocols.AuthType]::#{auth}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_kerberoast.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_kerberoast.yar) | $s1 = "$ForestInfo = [System.DirectoryServices.ActiveDirectory.Forest]::GetCurrentForest()" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


