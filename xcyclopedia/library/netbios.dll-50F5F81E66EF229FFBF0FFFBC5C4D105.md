---
title: netbios.dll | NetBIOS Interface Library
excerpt: What is netbios.dll?
---

# netbios.dll 

* File Path: `C:\Windows\system32\netbios.dll`
* Description: NetBIOS Interface Library

## Hashes

Type | Hash
-- | --
MD5 | `50F5F81E66EF229FFBF0FFFBC5C4D105`
SHA1 | `55BEF93005F7E5B21F947BFE3A2E55F1B99C73D2`
SHA256 | `C9782319E585F7DEC0F6A9570C54494C4F1FA7B3470B6630E2BDC6936611DEB9`
SHA384 | `0A36BBE0C72032DBE6E570D46A97F6CD8094334F00F59283281C5917369530DA120D47BE081E98C7FA504E1EAE5DA0C4`
SHA512 | `A213B3065D60D3F622B6E78B392F66C544BF74568DA93C78372C2BAAB71B4E5AC1265ED683B9CC67AE8416BF88BE6CA6C8485A545BF1254261B8D2DF81D3CCFF`
SSDEEP | `384:TmisdMQW+XKJS1F5MMDFWuLTN1lPyPcajTNbWDBW:Tmis2OmI6cB/hP+ca3NU`
IMP | `855A0D82FF8D830A77E42D269FDF302B`
PESHA1 | `2FE17A1A2C8C9120085854BA458AF2153D0B1C42`
PE256 | `D96E641049216414556ABDA368909BE1C9DC723EB21306C919EC83B9335D0523`

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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/c9782319e585f7dec0f6a9570c54494c4f1fa7b3470b6630e2bdc6936611deb9/detection/


## Possible Misuse

*The following table contains possible examples of `netbios.dll` being misused. While `netbios.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


