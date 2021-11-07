---
title: sethc.exe | Accessibility shortcut keys
excerpt: What is sethc.exe?
---

# sethc.exe 

* File Path: `C:\Windows\SysWOW64\sethc.exe`
* Description: Accessibility shortcut keys

## Hashes

Type | Hash
-- | --
MD5 | `999F4E59B7DB7AC9BA0A6F8DA894E2B9`
SHA1 | `F4ADDE09E6993D881CDB992141028AA2A750679D`
SHA256 | `CE13C119E81D353FD25FF6088AD011251259210BB2F2E72399A67887A4F2C2FB`
SHA384 | `002E575EFD71C915910A0CA5A6FBD438360A2587BD5279640158DF2B98BAA2B98FB38BC5CD93684AAF6483BDC17BDEFE`
SHA512 | `F84C9D0D8D4F4C042D95DF1419E762728D1685557D4E9307458A0670A8CF1449C50D63E1DA447B7C9AFEE8BCFF1DC876C441809039CF5D2F722D0CCE710D246F`
SSDEEP | `6144:v/eV0vQYHKAlGr66uFz2LJGRg4kLNnei36cw:nuChpFCdUc`
IMP | `1BA2225EBB5F11B47CA8667F66733C88`
PESHA1 | `8C0E4D5FDE7D552CF390B3C63C55CC35904E3027`
PE256 | `78249B15336B9368D3FB5EC698CA5A3179DB6CC2D7929F8A484EE688AC8B557B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\sethc.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sethc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/ce13c119e81d353fd25ff6088ad011251259210bb2f2e72399a67887a4f2c2fb/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-0490B8F08575C7AB5F358B07C1617F28.md) | 69
[C:\windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1EF5808E2ADC8AD7892E45551CE5C5CF.md) | 65
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-6CF3E7D021A16A86178F840D787F2E4C.md) | 61
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-9A846ED516E009A8409800B19402EF39.md) | 66
[C:\Windows\system32\sethc.exe](sethc.exe-062940BA26F1204EBD5F62DF37D0C3A7.md) | 72
[C:\Windows\system32\sethc.exe](sethc.exe-0D68CE0D6D390F926B4ECE77E44D4E30.md) | 66
[C:\windows\system32\sethc.exe](sethc.exe-EE69991DCEA4CA4189F42DEEE5D7666A.md) | 63
[C:\Windows\system32\sethc.exe](sethc.exe-F00FAB17E7FE21D930AA4A6CABD2381F.md) | 74
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-07A336072239B2FAEC1FEA0E23A23A88.md) | 71
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1913FD496CAFF87B409FAC35CD876274.md) | 60
[C:\windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-69D795102CADA9D5FEC1089138DA48AF.md) | 68
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-C5897612D16810BE94A68C5EB6950598.md) | 69
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-406DBF91AAFCBA4331AA0B487D578E33.md) | 80
[C:\windows\SysWOW64\sethc.exe](sethc.exe-5EBDA250D9AD873C3879282AC6F49FB7.md) | 66
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-9FE388226A8EF1B085441E21A3B0A57D.md) | 60

## Possible Misuse

*The following table contains possible examples of `sethc.exe` being misused. While `sethc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stickykey_like_backdoor.yml) | `- 'sethc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- 'sethc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sticky_keys_unauthenticated_privileged_console_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sticky_keys_unauthenticated_privileged_console_access.yml) | `- "copy /y C:\\windows\\system32\\cmd.exe C:\\windows\\system32\\sethc.exe"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_stickykey_like_backdoor.yml) | `- '\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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


