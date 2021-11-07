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
MD5 | `5D066739708F659F6C31A8CD1B82739F`
SHA1 | `D55E92546FC3ED6A217FB12A1CE10CF31FF12906`
SHA256 | `D860BE76A3E88ABFB48A9B5618E90ECAC15F6D6BE73C46A20EE91026BCA0699B`
SHA384 | `6FFD4B7F1DA7C2050CCF7851C1C00D370AD44DC2B1A8B0082830AC2C94FC3208727075A2164ADA335D529836D5366B5F`
SHA512 | `E0E3542210EA2714897843E974C8AA1F74FC567CE00D21F1476FDD9FDC1B4A61E4A27ED0B62A5FC35BB5950647028DF3928E3DEBA62342C61DD2865CD483E611`
SSDEEP | `49152:2R9K+qUe1+b3y4cd5YXYTRztuogkmmqKz783vn:qiU8LVkkm1n`
IMP | `E271C2DFB162A6CC94E6F7A86AC38D11`
PESHA1 | `36205268333987DD37178FC286EF6B105C9D86D6`
PE256 | `C1F78697A7ED241D879D27C9894B2992F4F4DDC8E565A452B34114E1C9A3C47F`

## Runtime Data

### Child Processes:
opera.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Opera\launcher.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\dbghelp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |


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
* File Version: 81.0.4196.31
* Product Version: 81.0.4196.31
* Language: English (United States)
* Legal Copyright: Copyright Opera Software 2021
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d860be76a3e88abfb48a9b5618e90ecac15f6d6be73c46a20ee91026bca0699b/detection


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


