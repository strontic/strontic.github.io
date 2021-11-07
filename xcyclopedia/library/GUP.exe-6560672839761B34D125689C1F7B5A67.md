---
title: GUP.exe | WinGup for Notepad++
excerpt: What is GUP.exe?
---

# GUP.exe 

* File Path: `C:\Program Files (x86)\Notepad++\updater\GUP.exe`
* Description: WinGup for Notepad++

## Screenshot

![GUP.exe](screenshots/GUP.exe-6C7A654714374E2CC0BEF20FD8CEE7A8-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `6560672839761B34D125689C1F7B5A67`
SHA1 | `22A86687563EBC3C49497DEE5672BB977EF24E5B`
SHA256 | `285D1F375EEDB5DC30B2962ED45187F1FE07CFD09DE101FACA8A1B2416E6BD69`
SHA384 | `7F885D523407A4A4023EE62452B06F44275FEC66BB8C87F0689E4AD1BB0B274433FC23944D696538FB9C6110A35A2DA4`
SHA512 | `342D1B7970AC08FDC2E32561B9E94A17F632ACB40067D2A4697BA7B971E9FFA8FD6D92248DC1C307A41975449C4D80B885B2E95FA1FAE73E16756C622924A288`
SSDEEP | `12288:hPIHfuY5dwaOjXgq3Z5LbCS8fRwlGaEn+LaSJ3Kw8+bxAaWUeICV+YEcBpbQD/Mt:hPI2qqHCXfRwlGaEn1AbxdWUrCVyYpE+`
IMP | `13987573249DB409531745D87AA89A4D`
PESHA1 | `16C29DBD0F7CF1EB5111DE00B6DBD5C16DFF5DBB`
PE256 | `C61F61E676036BBEE1AD32EA5C9B5415DFCB4441A9826ADEC992FF1104A61CF4`

## Runtime Data

### Window Title:
GUP Command Argument Help

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_a8625c1886757984 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Notepad++\updater\GUP.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `01342592A0010CB1109C11C0519CFD24`
* Thumbprint: `7649DC70ECA74657C1BAE0128492098AE47097FF`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Notepad++", O="Notepad++", L=Saint Cloud, S=Ile-de-France, C=FR

## File Metadata

* Original Filename: gup.exe
* Product Name: WinGup for Notepad++
* Company Name: Don HO don.h@free.fr
* File Version: 5.21
* Product Version: 5.21
* Language: English (United States)
* Legal Copyright: Copyright 2018 by Don HO
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/285d1f375eedb5dc30b2962ed45187f1fe07cfd09de101faca8a1b2416e6bd69/detection


## Possible Misuse

*The following table contains possible examples of `GUP.exe` being misused. While `GUP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `Image\|endswith: '\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- '\Users\\*\AppData\Local\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- '\Users\\*\AppData\Roaming\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- '\Program Files\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- '\Program Files (x86)\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- Execution of tools named GUP.exe and located in folders different than Notepad++\updater`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `FC37AC7523CF3B4020EC46D6A47BC26957E3C054` \| gup.exe           \| Abused legitimate application    \| Clean file                             \|`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: DLL Side-Loading using the Notepad++ GUP.exe binary [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: DLL Side-Loading using the Notepad++ GUP.exe binary [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | - [Atomic Test #1 - DLL Side-Loading using the Notepad++ GUP.exe binary](#atomic-test-1---dll-side-loading-using-the-notepad-gupexe-binary) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | ## Atomic Test #1 - DLL Side-Loading using the Notepad++ GUP.exe binary | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | \| gup_executable \| GUP is an open source signed binary used by Notepad++ for software updates \| Path \| PathToAtomicsFolder&#92;T1574.002&#92;bin&#92;GUP.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | ##### Description: Gup.exe binary must exist on disk at specified location (#{gup_executable}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | Invoke-WebRequest "https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/bin/GUP.exe?raw=true" -OutFile "#{gup_executable}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


