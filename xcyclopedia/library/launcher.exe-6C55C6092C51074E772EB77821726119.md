---
title: launcher.exe | Opera Internet Browser
excerpt: What is launcher.exe?
---

# launcher.exe 

* File Path: `C:\program files\Opera\launcher.exe`
* Description: Opera Internet Browser

## Hashes

Type | Hash
-- | --
MD5 | `6C55C6092C51074E772EB77821726119`
SHA1 | `D5FE3305EB181DE3F5E557A91C5A3088972A8433`
SHA256 | `E7043BFDEFFFB0EBC799C7087CE435506775470CB4C46F341C77EB9ECAECD355`
SHA384 | `CF380E491ABFF3CC23480C689B75F7DC244A81BC170C45AE3F918CC01238E554B97B862E96E977228AEAA5A0E23C4D24`
SHA512 | `DA6238925EE2783C3FAC01E2228015A8BD54C47E4EBFE7ECC03625B57274E87671CD5F9970147EE3C28048BD137F5D10F1FCB5F39419BA92270B949957D4D4B6`
SSDEEP | `24576:Ac/qn2FsLUT4yINSbkuwNdjNx5ZoJbaZ7hivd:d/pbbKNdZxsJeZy`

## Runtime Data

### Child Processes:
opera.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(RW-)   C:\Users\user\Documents | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\program files\Opera\launcher.exe |
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
* File Version: 70.0.3728.133
* Product Version: 70.0.3728.133
* Language: English (United States)
* Legal Copyright: Copyright Opera Software 2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Opera\launcher.exe](launcher.exe-751653ECA8194D01F6A9A2F66314ACA7.md) | 91

## Possible Misuse

*The following table contains possible examples of `launcher.exe` being misused. While `launcher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_clip_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_clip_services.yml) | `title: Invoke-Obfuscation CLIP+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_clip_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_clip_services_security.yml) | `title: Invoke-Obfuscation CLIP+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_stdin_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_stdin_services.yml) | `title: Invoke-Obfuscation STDIN+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_stdin_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_stdin_services_security.yml) | `title: Invoke-Obfuscation STDIN+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_var_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_var_services.yml) | `title: Invoke-Obfuscation VAR+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_var_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_var_services_security.yml) | `title: Invoke-Obfuscation VAR+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_rundll_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_rundll_services.yml) | `title: Invoke-Obfuscation RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_rundll_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_rundll_services.yml) | `description: Detects Obfuscated Powershell via RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_rundll_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_rundll_services_security.yml) | `title: Invoke-Obfuscation RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_rundll_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_rundll_services_security.yml) | `description: Detects Obfuscated Powershell via RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_var_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_var_services.yml) | `title: Invoke-Obfuscation VAR++ LAUNCHER OBFUSCATION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_var_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_var_services.yml) | `description: Detects Obfuscated Powershell via VAR++ LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_var_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_var_services_security.yml) | `title: Invoke-Obfuscation VAR++ LAUNCHER OBFUSCATION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_var_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_var_services_security.yml) | `description: Detects Obfuscated Powershell via VAR++ LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_clip.yml) | `title: Invoke-Obfuscation CLIP+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_stdin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_stdin.yml) | `title: Invoke-Obfuscation STDIN+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_var.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_var.yml) | `title: Invoke-Obfuscation VAR+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_rundll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_via_rundll.yml) | `title: Invoke-Obfuscation RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_rundll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_via_rundll.yml) | `description: Detects Obfuscated Powershell via RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_var.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_via_var.yml) | `title: Invoke-Obfuscation VAR++ LAUNCHER OBFUSCATION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_var.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_via_var.yml) | `description: Detects Obfuscated Powershell via VAR++ LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_clip_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_clip_in_scriptblocktext.yml) | `title: Invoke-Obfuscation CLIP+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_stdin_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_stdin_in_scriptblocktext.yml) | `title: Invoke-Obfuscation STDIN+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_var_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_var_in_scriptblocktext.yml) | `title: Invoke-Obfuscation VAR+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_rundll_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_via_rundll_in_scriptblocktext.yml) | `title: Invoke-Obfuscation RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_rundll_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_via_rundll_in_scriptblocktext.yml) | `description: Detects Obfuscated Powershell via RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_var_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_via_var_in_scriptblocktext.yml) | `title: Invoke-Obfuscation VAR++ LAUNCHER OBFUSCATION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_var_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_via_var_in_scriptblocktext.yml) | `description: Detects Obfuscated Powershell via VAR++ LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_clip.yml) | `title: Invoke-Obfuscation CLIP+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_stdin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_stdin.yml) | `title: Invoke-Obfuscation STDIN+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_var.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_var.yml) | `title: Invoke-Obfuscation VAR+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_rundll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_via_rundll.yml) | `title: Invoke-Obfuscation RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_rundll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_via_rundll.yml) | `description: Detects Obfuscated Powershell via RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_var.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_via_var.yml) | `title: Invoke-Obfuscation VAR++ LAUNCHER OBFUSCATION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_var.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_via_var.yml) | `description: Detects Obfuscated Powershell via VAR++ LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_covenant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_covenant.yml) | `title: Covenant Launcher Indicators`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_clip+_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_clip+_services.yml) | `title: Invoke-Obfuscation CLIP+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_stdin+_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_stdin+_services.yml) | `title: Invoke-Obfuscation STDIN+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_var+_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_var+_services.yml) | `title: Invoke-Obfuscation VAR+ Launcher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_via_rundll_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_via_rundll_services.yml) | `title: Invoke-Obfuscation RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_via_rundll_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_via_rundll_services.yml) | `description: Detects Obfuscated Powershell via RUNDLL LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_via_var++_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_via_var++_services.yml) | `title: Invoke-Obfuscation VAR++ LAUNCHER OBFUSCATION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_via_var++_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_via_var++_services.yml) | `description: Detects Obfuscated Powershell via VAR++ LAUNCHER`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `.Main launcher (`armsvc.exe`)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-ramsay.json](https://github.com/eset/malware-ioc/blob/master/ramsay/misp-ramsay.json) | `"comment": "Installer Launcher",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `==== VMProtected launcher`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s0 = "Launcher.EXE" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cobaltstrike_evasive.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cobaltstrike_evasive.yar) | description = "Detects CobaltStrike MZ header ReflectiveLoader launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s1 = "* Failed to get connection information.  Aborting launcher!" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | description = "Process injector/launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | description = "Equation Group Malware - EoP package and malware launcher" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


