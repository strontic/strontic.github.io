---
title: launcher.exe | Opera Internet Browser
---

# launcher.exe 

* File Path: `C:\Program Files\Opera\launcher.exe`
* Description: Opera Internet Browser

## Hashes

Type | Hash
-- | --
MD5 | `751653ECA8194D01F6A9A2F66314ACA7`
SHA1 | `E69114164F08F5ADAA9F180A55331593D9010296`
SHA256 | `73550B0620BCC5F7088BDDA70E86A08499AD1375CEB1FB975731521964734DE2`
SHA384 | `A3067E3F484CE3F57E0A6FA07C669755FAECA36086926CD8DEC8AFE105D1500644180722AC64B36D9C2264AD8D7C007A`
SHA512 | `ECE5BBC423D0949BB6C6DE8676419177BB98941814D804EF743219E3BA577C1352E9D7221EBD709A8FA8EBD14C4B3258C45B41E0F8778BBD3FE5F8CE32E5AE3E`
SSDEEP | `24576:+c/qn2FsLUT4yINSdkuwNdjNx5ZoJbaZ7h+v8:n/pbdKNdZxsJeZP`

## Runtime Data

### Child Processes:
opera.exe

## Signature

* Status: Signature verified.
* Serial: `0D31C23EB2249CE611B953FB16EA0D25`
* Thumbprint: `373CD800B048D39CE2057A09937093EA73BCDE5F`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Opera Software AS, O=Opera Software AS, L=Oslo, C=NO, SERIALNUMBER=916 368 127, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.3=NO

## File Metadata

* Original Filename: 
* Product Name: Opera Internet Browser
* Company Name: Opera Software
* File Version: 70.0.3728.106
* Product Version: 70.0.3728.106
* Language: English (United States)
* Legal Copyright: Copyright Opera Software 2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Opera\launcher.exe](launcher.exe-6C55C6092C51074E772EB77821726119.md) | 91

## Possible Misuse

*The following table contains possible examples of `launcher.exe` being misused. While `launcher.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_covenant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_covenant.yml) | `title: Covenant Launcher Indicators` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `.Main launcher (`armsvc.exe`)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-ramsay.json](https://github.com/eset/malware-ioc/blob/master/ramsay/misp-ramsay.json) | `"comment": "Installer Launcher",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `==== VMProtected launcher` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) |     Launcher: command_prompt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s0 = "Launcher.EXE" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) |       $s1 = "* Failed to get connection information.  Aborting launcher!" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) |         description = "Process injector/launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | 		description = "Equation Group Malware - EoP package and malware launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


