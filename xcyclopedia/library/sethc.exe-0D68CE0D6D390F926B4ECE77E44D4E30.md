---
title: sethc.exe | Accessibility shortcut keys
excerpt: What is sethc.exe?
---

# sethc.exe 

* File Path: `C:\Windows\system32\sethc.exe`
* Description: Accessibility shortcut keys

## Hashes

Type | Hash
-- | --
MD5 | `0D68CE0D6D390F926B4ECE77E44D4E30`
SHA1 | `7F6E66F120ECA805FB2E7C99DF74BC00E16F5E04`
SHA256 | `2DFCAA75BFB6EFBD24A0862C80F90798BE480F656A434C5ACE7EEB618835C78A`
SHA384 | `90AE8ACCE39E0C24525523425362A3A25BA9F40C8FB30C5255C2D2F15158B0083ED767E5413CE65A21F156C22DAED461`
SHA512 | `C978C7814BCF20C1529407F73465B8258500D39FCD5947CE5C3A87CC3FF1EEF5764F8C29746A5DCC15D10BFDF096AFCDAFE4F11C84ADDF764E332E67895F4565`
SSDEEP | `6144:u3Gw3vDeZOj+jC6uFz2LJGRg4kLNnei36cw:u2uquFCdUc`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sethc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-0490B8F08575C7AB5F358B07C1617F28.md) | 61
[C:\windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1EF5808E2ADC8AD7892E45551CE5C5CF.md) | 77
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-6CF3E7D021A16A86178F840D787F2E4C.md) | 77
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-9A846ED516E009A8409800B19402EF39.md) | 61
[C:\Windows\system32\sethc.exe](sethc.exe-062940BA26F1204EBD5F62DF37D0C3A7.md) | 63
[C:\windows\system32\sethc.exe](sethc.exe-EE69991DCEA4CA4189F42DEEE5D7666A.md) | 75
[C:\Windows\system32\sethc.exe](sethc.exe-F00FAB17E7FE21D930AA4A6CABD2381F.md) | 61
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-07A336072239B2FAEC1FEA0E23A23A88.md) | 60
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1913FD496CAFF87B409FAC35CD876274.md) | 71
[C:\windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-69D795102CADA9D5FEC1089138DA48AF.md) | 80
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-C5897612D16810BE94A68C5EB6950598.md) | 61
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-406DBF91AAFCBA4331AA0B487D578E33.md) | 61
[C:\windows\SysWOW64\sethc.exe](sethc.exe-5EBDA250D9AD873C3879282AC6F49FB7.md) | 79
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-999F4E59B7DB7AC9BA0A6F8DA894E2B9.md) | 66
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-9FE388226A8EF1B085441E21A3B0A57D.md) | 77

## Possible Misuse

*The following table contains possible examples of `sethc.exe` being misused. While `sethc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- '*\CurrentVersion\Image File Execution Options\sethc.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*cmd.exe sethc.exe *'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Two common accessibility programs are <code>C:\Windows\System32\sethc.exe</code>, launched when the shift key is pressed five times and <code>C:\Windows\System32\utilman.exe</code>, launched when the Windows + U key combination is pressed. The sethc.exe program is often referred to as "sticky keys", and has been used by adversaries for unauthenticated access through a remote desktop login screen. (Citation: FireEye Hikit Rootkit) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Replace sticky keys binary (sethc.exe) with cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | copy C:\Windows\System32\sethc.exe C:\Windows\System32\sethc_backup.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | takeown /F C:\Windows\System32\sethc.exe /A | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | icacls C:\Windows\System32\sethc.exe /grant Administrators:F /t | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | copy /Y C:\Windows\System32\cmd.exe C:\Windows\System32\sethc.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | copy /Y C:\Windows\System32\sethc_backup.exe C:\Windows\System32\sethc.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s1 = "success = obj.run(\"cmd /c takeown /f %SystemRoot%\\system32\\sethc.exe&echo y\| " ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file T00ls Lpk Sethc v4.0.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file T00ls Lpk Sethc v3.0.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file T00ls Lpk Sethc v2.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s2 = "\\dllcache\\sethc.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s2 = "\\sethc.exe /G everyone:F" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "\\sethc.exe /G everyone:F" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s3 = "\\dllcache\\sethc.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s3 = "\\sethc.exe /G everyone:F" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Sethc.exe has been replaced - Indicates Remote Access Hack RDP" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s4 = "SETHC.EXE" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "sethc.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


