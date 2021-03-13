---
title: windbg.exe | Windows GUI symbolic debugger
excerpt: What is windbg.exe?
---

# windbg.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\windbg.exe`
* Description: Windows GUI symbolic debugger

## Screenshot

![windbg.exe](screenshots/windbg.exe-8CC7AB7DC9C670809113929568FB3F31-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `DA8D9E0797323466972BAF573BA7C02D`
SHA1 | `D30AED1C1A36DCCC8EA450BDCDA91B6618421C14`
SHA256 | `8B53689B92EE1492A61DBA5476496A807A7954E0171C1B35C906C3EAB1C37465`
SHA384 | `C66BE4204D8812FD73C0EBC6577EC85B72FEC1486B1CAE2B7C47A6EA5F7CD897678CC0ECEA3D9B26DD191B69C43DD88F`
SHA512 | `6923DE22E95D9D318FC12F0DA11624158FAC8B70936F4BCD2481A9379BE10868FC5803DB8593198C379B916D3AF4A4C7BE9C55798D4D9C345743A19C94B779DF`
SSDEEP | `6144:TQzBThs0lDuWZWwxGFZ+f1wvxKjQjhDnrEw/rl1kwJzF1MfsUZu3Gyg7nZ4GwKrk:TQzlhdc+f1yF9boC1kwJz8wOusrte4Y`
IMP | `F97D651BFA105F22F8A9A2474779DAE8`
PESHA1 | `E6B74D05771CCD639B898C2B43A6CE6F938E04BC`
PE256 | `0648918A493C82086E9D586EDDDBE37FCE782CD06788BF0C63A945DC25858002`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: windbg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 452

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/8b53689b92ee1492a61dba5476496a807a7954e0171c1b35c906c3eab1c37465/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\windbg.exe](windbg.exe-7B9C6CAB38F6270C7324DCB375501522.md) | 32
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\windbg.exe](windbg.exe-8CC7AB7DC9C670809113929568FB3F31.md) | 35

## Possible Misuse

*The following table contains possible examples of `windbg.exe` being misused. While `windbg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `title: Possible App Whitelisting Bypass via WinDbg/CDB as a Shellcode Runner`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `- http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Link: http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html`{:.highlight .language-yaml} | 
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_deviceguard_evasion.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_deviceguard_evasion.yar) | reference = "http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"windbg",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


