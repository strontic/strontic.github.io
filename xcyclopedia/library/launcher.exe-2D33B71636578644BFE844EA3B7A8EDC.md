---
title: launcher.exe | Opera Internet Browser
excerpt: What is launcher.exe?
---

# launcher.exe 

* File Path: `C:\Program Files\Opera\launcher.exe`
* Description: Opera Internet Browser

## Hashes

Type | Hash
-- | --
MD5 | `2D33B71636578644BFE844EA3B7A8EDC`
SHA1 | `30C72D829D14BD8B37109DAE1B234354396CC229`
SHA256 | `ABE39FE53362785419CDE37BB5CFB209EDC00E0772FEDFAB520F21CB231ED46E`
SHA384 | `9E26093F60B8E673174122E0B8D8159ED79B5C97BD1B9F4788C65525F95D5158D0C38D2EB091F4075595854488F03EA6`
SHA512 | `5BE6C8AC24ADEB2F328AAA5970525C0C871DEC5D57289E179FE37875249A45FFE77BFF4B45C37BA382ECE5F8161713876CD6477C4FA6881AD54889A6E1CB6B99`
SSDEEP | `24576:pOF4j7Ztlm2zXuVHniBz8sCzzf6s32PzTtLvcmdA:0C7Dlmi2sCf6smnta`
IMP | `36851E1C9922AA7E01142CE3BA9880DB`
PESHA1 | `E68910278E8600E5A1A139A8D558320C9F73727A`
PE256 | `B6572FEB92A220B3767E4F429520B1CAB6568641DB3C29EED8A074474BA687BA`

## Runtime Data

### Child Processes:
opera.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000003.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Opera\launcher.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `05F4210DB2B283A32FF2AED29FCB68A4`
* Thumbprint: `878B0B298671F44FC739C08D826BB22DB1A2A021`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Opera Software AS, O=Opera Software AS, L=Oslo, C=NO, SERIALNUMBER=916 368 127, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.3=NO

## File Metadata

* Original Filename: 
* Product Name: Opera Internet Browser
* Company Name: Opera Software
* File Version: 71.0.3770.171
* Product Version: 71.0.3770.171
* Language: English (United States)
* Legal Copyright: Copyright Opera Software 2020
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/abe39fe53362785419cde37bb5cfb209edc00e0772fedfab520f21cb231ed46e/detection/


## Possible Misuse

*The following table contains possible examples of `launcher.exe` being misused. While `launcher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_covenant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_covenant.yml) | `title: Covenant Launcher Indicators`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `.Main launcher (`armsvc.exe`)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-ramsay.json](https://github.com/eset/malware-ioc/blob/master/ramsay/misp-ramsay.json) | `"comment": "Installer Launcher",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `==== VMProtected launcher`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s0 = "Launcher.EXE" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s1 = "* Failed to get connection information.  Aborting launcher!" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | description = "Process injector/launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | description = "Equation Group Malware - EoP package and malware launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


