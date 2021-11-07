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


