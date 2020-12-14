---
title: netbios.dll | NetBIOS Interface Library
excerpt: What is netbios.dll?
---

# netbios.dll 

* File Path: `C:\Windows\SysWOW64\netbios.dll`
* Description: NetBIOS Interface Library

## Hashes

Type | Hash
-- | --
MD5 | `6985D4FF4EA34E0C19BADBAF86DB70CE`
SHA1 | `6E3F7002620F42DCE71696226CDDD12E0C2816A6`
SHA256 | `B22EC08C746AB17A2E95D72E74F478BC875A049A46576458F4DFDDE4FCB1B03D`
SHA384 | `D6F9647D3F48A50EC576B66A4C836D09F47835B72F8752F6DFBA4350617714D4E4A49047FB9CEA73E334E359B5192C19`
SHA512 | `8109B89E015FCB28B0B0B6191EC70B834F56F1F19A5F48D0F6C5D6EB0B3A9F63B0F23A31A92F7B41F9F8853F99B63A8C3772A602B6B42AF80C89A74F42191851`
SSDEEP | `384:ERBpA1eHyloxy+IYhdWw21lPyPc6aWDBWYy:ERB21eSlopXWw0P+csd`
IMP | `1F003D6B213CBED428A6B0FDF5062A32`
PESHA1 | `F0CF42722D570829FB8437219453A7A340975A02`
PE256 | `EC976449A7593E37D6F76BD23CC9D6E99F8A3BE365D2C28B5545D1BF77C8E953`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`Netbios` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netbios.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/b22ec08c746ab17a2e95d72e74f478bc875a049a46576458f4dfdde4fcb1b03d/detection/


## Possible Misuse

*The following table contains possible examples of `netbios.dll` being misused. While `netbios.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `server_nb_computer_name: zeek.ntlm.server.name.netbios` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | \| connectaddress \| Specifies the IPv4 address to which to connect. Acceptable values are IP address, computer NetBIOS name, or computer DNS name. If an address is not specified, the default is the local computer. \| string \| 127.0.0.1\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | * NetBIOS / SMB / Samba (139/TCP & 445/TCP) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | * NetBIOS / SMB / Samba (139/TCP & 445/TCP) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s3 = "Enable answers for netbios wredir suffix queries. Answering to wredir will likely break stuff on the network." fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Auto-generated rule on file NetBIOS Name Scanner.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "response.write \"<font color=blue size=2>NetBios Name: \\\\\"  & Snet.ComputerName &" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


