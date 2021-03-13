---
title: snmptrap.exe | SNMP Trap
excerpt: What is snmptrap.exe?
---

# snmptrap.exe 

* File Path: `C:\Windows\system32\snmptrap.exe`
* Description: SNMP Trap

## Hashes

Type | Hash
-- | --
MD5 | `58983BFDDDB09E21AF8F3BA3EC45FC7D`
SHA1 | `EC79F827947C95B9BA0C4E9584E45A06553CAB5C`
SHA256 | `9CFC867BECEC3E1FCE830526108F7A7C3E9B0E2FC001EE6CDE6E49C956F781E9`
SHA384 | `15733B97A92F22DF8FFC04D20E6C385968C7B7D7B9102B1122A759359ACB4321F9AA04185414EF7367C8E14E6111D7A5`
SHA512 | `0289414E398B7E001571DD94C5B77655A00C435E81CA9002AAA8F6012BD4BA34B793FD6C4063BC851FF69A6DBAE8938DF90D38BAAAC687FD6AFD289BC4E4A1F6`
SSDEEP | `384:0ulRaMStzN+lsamt6ZCCW2gOUy2QsifpKWqyW:06RwteA35y2f+u`
IMP | `1B8B61707212B76DF87FB8E972F18842`
PESHA1 | `99C1BDF6629F43A41D7AA89B5070AFCD808F8F8A`
PE256 | `5A264565B4F3E3506FA7C9103CC915207344FCF2BF323798BC96ACF2D5253F29`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: snmptrap.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/9cfc867becec3e1fce830526108f7a7c3e9b0e2fc001ee6cde6e49c956f781e9/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\snmptrap.exe](snmptrap.exe-78172782B1E1E26933D67A9DA912158C.md) | 54

## Possible Misuse

*The following table contains possible examples of `snmptrap.exe` being misused. While `snmptrap.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [52771610-2322-44cf-816b-a7df42b4c086.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/persistence/52771610-2322-44cf-816b-a7df42b4c086.yml) | `This is an example technique. snmptrap.exe should be changed in the command`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [52771610-2322-44cf-816b-a7df42b4c086.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/persistence/52771610-2322-44cf-816b-a7df42b4c086.yml) | `Copy-Item -Path "C:\Windows\System32\snmptrap.exe" -Destination $path`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


