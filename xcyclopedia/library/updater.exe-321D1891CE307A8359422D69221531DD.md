---
title: updater.exe | Thunderbird Software Updater
---

# updater.exe 

* File Path: `C:\Program Files\Mozilla Thunderbird\updater.exe`
* Description: Thunderbird Software Updater

## Hashes

Type | Hash
-- | --
MD5 | `321D1891CE307A8359422D69221531DD`
SHA1 | `AEE034CC2BBE90037CE61ECD5034A1991BD6EF80`
SHA256 | `7DC408D6FB2A0840334F05FD87D5C8C4B04F60F3A09C6AFB6CF53881698CFB58`
SHA384 | `7221408BBEE4A63993382AB8219568242382F9185026A9581A0299871037EAA7F93AD81320DF9DBA0E88CD4677D4AFBF`
SHA512 | `EBD0E7EF0352DC70044ED24C641019266F77F1E0DEC6C8C5B3A019E6C0BC7DE29240DA54627AAB0A5740720A452A6B3F5DF1240A45417873BC68EB4DDAB39F69`
SSDEEP | `6144:ow7eEo9z5dv8jAEW9vqpI8/ucD1HBNpoj0Jg3PfcKrKywA:L1M83LeC1VJAdGyF`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: updater patch-dir install-dir apply-to-dir [wait-pid [callback-working-dir callback-path args...]]

```

## Signature

* Status: Signature verified.
* Serial: `0DDEB53F957337FBEAF98C4A615B149D`
* Thumbprint: `91CABEA509662626E34326687348CAF2DD3B4BBA`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: E="release+certificates@mozilla.com", CN=Mozilla Corporation, OU=Firefox Engineering Operations, O=Mozilla Corporation, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: updater.exe
* Product Name: Thunderbird
* Company Name: Mozilla Foundation
* File Version: 78.1.0
* Product Version: 78.1.0
* Language: Language Neutral
* Legal Copyright: License: MPL 2

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Mozilla Firefox\updater.exe](updater.exe-904B85E7D09E0CEE3294D10F947E3183.md) | 36
[C:\Program Files\Mozilla Firefox\updater.exe](updater.exe-B0DC65F40D4D45A9E42628902C35422F.md) | 36
[C:\program files\Mozilla Thunderbird\updater.exe](updater.exe-BF0362D3182C55DB7143EFA1098CEB6D.md) | 41

## Possible Misuse

*The following table contains possible examples of `updater.exe` being misused. While `updater.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONLOGON*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *DAILY*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONIDLE*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *Updater*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `description: Detects execution of the Notepad++ updater in a suspicious directory, which is often used in DLL side-loading attacks` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- 'C:\Users\\*\AppData\Local\Notepad++\updater\gup.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- 'C:\Users\\*\AppData\Roaming\Notepad++\updater\gup.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- 'C:\Program Files\Notepad++\updater\gup.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- 'C:\Program Files (x86)\Notepad++\updater\gup.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- Execution of tools named GUP.exe and located in folders different than Notepad++\updater` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Gpup.yml) | `- 'C:\Program Files (x86)\Notepad++\updater\gpup.exe    '` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Update.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Update.yml) | `- Link: https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/microsoft-teams-updater-living-off-the-land/` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-kryptocibule.json](https://github.com/eset/malware-ioc/blob/master/kryptocibule/misp-kryptocibule.json) | `"value": "%ProgramFiles(X86)%\\Adobe\\Acrobat Reader DC\\Reader\\Update\\Updater.exe",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `.Updater (`Updater.exe`)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `%ProgramFiles(X86)%\Adobe\Acrobat Reader DC\Reader\Update\Updater.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Upon successful execution, powershell.exe will be copied and renamed to updater.exe and load amsi.dll from a non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | copy %windir%\System32\windowspowershell\v1.0\powershell.exe %APPDATA%\updater.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | %APPDATA%\updater.exe -Command exit | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | del %APPDATA%\updater.exe >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | 		$s12 = "Intel Integrated Graphics Updater" fullword wide /* PEStudio Blacklist: strings */ /* score: '12.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | 		$s5 = "Adobe Flash Plugin Updater" fullword wide /* PEStudio Blacklist: strings */ /* score: '11.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nkminer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nkminer.yar) |       $f = "C:\\Windows\\Sys64\\updater.exe" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | 		$string10 = "DynDNS\\Updater\\config.dyndns" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


