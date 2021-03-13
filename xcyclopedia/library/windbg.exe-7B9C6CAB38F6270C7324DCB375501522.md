---
title: windbg.exe | Windows GUI symbolic debugger
excerpt: What is windbg.exe?
---

# windbg.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\windbg.exe`
* Description: Windows GUI symbolic debugger

## Screenshot

![windbg.exe](screenshots/windbg.exe-8CC7AB7DC9C670809113929568FB3F31-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `7B9C6CAB38F6270C7324DCB375501522`
SHA1 | `6F76ABE530B3B6F946CE0F3CD149FFDB821D7EB1`
SHA256 | `E864C79EBAF473CD7DD5859DE079635FA09DDA67725E81C1D1907BA9E406C290`
SHA384 | `D4E2BFC871685530F7D10BB12F32DAC3B0AA48B18758D6431E0B4D5D4F30BBF35CAF4CB5A9039AB9D38E5358108E8E4E`
SHA512 | `867DE687517E881CC59725995D9AF6E07608C96CE74AC47DDDDC69FE5DF54D39CD310C8C030536DE31C8D44A928632F7CD6A5E0E269F70778D206639883FC451`
SSDEEP | `6144:RZdtMZJQwAAHsrZBJkbngc0ORL7fomCThLwQwM0yg7nZ4GwKrte4A3c:TU/HscgQ/Ct6Jusrte4Gc`
IMP | `58EACDD61DFF9F4A855CF087FAC2BEF8`
PESHA1 | `266A04EE5D86B6590824D9147AFEF2F1EB7B604A`
PE256 | `AD582815107B816232B649A95777EA0225A20A3515D2386705360BC946FC09F4`

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
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/e864c79ebaf473cd7dd5859de079635fa09dda67725e81c1d1907ba9e406c290/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\windbg.exe](windbg.exe-DA8D9E0797323466972BAF573BA7C02D.md) | 32

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


