---
title: System.DirectoryServices.Protocols.dll | .NET Framework
excerpt: What is System.DirectoryServices.Protocols.dll?
---

# System.DirectoryServices.Protocols.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.DirectoryServices.Protocols.dll`
* Description: .NET Framework
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `6D38FF0558E098204FB73D771D2C0454`
SHA1 | `7F2AA17FD75B0B80AE33CB574A1E05B990503A07`
SHA256 | `0C895A915330F9B3CA564EB5CE1B004E199C4351897C334F36EF38DB8C47022F`
SHA384 | `2D4C1B777CFB25A56096A69988B6D8C8BD923AAF68BA6270DDB0223E31DF575DA49B7B25B63217FEEF67A81715728B14`
SHA512 | `BFFE60C2E6D4C53D2717D668087472B029E684C63EF1A9286C288F87A36FF3EF08A8767AD3490DC2F966B5FA15723186675B434ECC9D855D979E86A3B55D3AAB`
SSDEEP | `768:891fDSclIiOjeszZQRjGY7C0xY7EdZqqrUaBeC6Z/Tp9UiDqWBIu8/5D12v3:Eq+GY7MomgeCYLpWi1Byh+`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `F741D5E8D233A99FE55A16C5044CC166F93F2CB1`
PE256 | `6F1BB30B0334A09121A345DD6CDE8D8F5024715A167F7BAE889165997C2DF364`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.DirectoryServices.Protocols.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/0c895a915330f9b3ca564eb5ce1b004e199c4351897c334f36ef38db8c47022f/detection


## Possible Misuse

*The following table contains possible examples of `System.DirectoryServices.Protocols.dll` being misused. While `System.DirectoryServices.Protocols.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | [System.Reflection.Assembly]::LoadWithPartialName("System.DirectoryServices.Protocols") \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | $di = new-object System.DirectoryServices.Protocols.LdapDirectoryIdentifier("#{domain}",389) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | $conn = new-object System.DirectoryServices.Protocols.LdapConnection($di, $credz, [System.DirectoryServices.Protocols.AuthType]::#{auth}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | [System.Reflection.Assembly]::LoadWithPartialName("System.DirectoryServices.Protocols") \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | $di = new-object System.DirectoryServices.Protocols.LdapDirectoryIdentifier("#{domain}",389) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | $conn = new-object System.DirectoryServices.Protocols.LdapConnection($di, $credz, [System.DirectoryServices.Protocols.AuthType]::#{auth}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


