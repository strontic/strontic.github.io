---
title: updater.exe | Firefox Software Updater
excerpt: What is updater.exe?
---

# updater.exe 

* File Path: `C:\Program Files\Mozilla Firefox\updater.exe`
* Description: Firefox Software Updater

## Hashes

Type | Hash
-- | --
MD5 | `019CF18ADC3FA81FA314F8B3ED9061C1`
SHA1 | `1892F40B831D653C1056EF1EBE4DC28A49862753`
SHA256 | `A8393B5C7E98F4102AE599FB337003782CEF5EE7FD48AF20C647518CC08A3733`
SHA384 | `A6C3263444E69F39A8BA1DC43446102845DE295CD42B3588894F81E02ED58AA5E144A6E5A923E0B4E9742563C9B52AF8`
SHA512 | `3195CD7DFA5B527F947FB55B8F23C601987FF5999A60DEAA4C288E5E32CCAE954ED107BF551DD7A215F8BF28C120C847C478AF8F0A94BFAFF763CDF5151D82BF`
SSDEEP | `6144:n/G/jvr2WhT9kTEMZuZUO+ykXxoN2A10U5uuNc4OexIBNd0XYAusqJg3PfcKrKyG:n/G/jKWhyQSOwBMVGe/W1JAdGyG`
IMP | `5629AE476C183894D4236EAC48C5723F`
PESHA1 | `7B7ED870EF2F60A524473EDAA406B6502743C439`
PE256 | `529AE871BCAF7BDE41125D5E1C93B2BCB088ACEE1A3B2D572453B3E396229795`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: updater patch-dir install-dir apply-to-dir [wait-pid [callback-working-dir callback-path args...]]

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Mozilla Firefox\updater.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `0DDEB53F957337FBEAF98C4A615B149D`
* Thumbprint: `91CABEA509662626E34326687348CAF2DD3B4BBA`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: E="release+certificates@mozilla.com", CN=Mozilla Corporation, OU=Firefox Engineering Operations, O=Mozilla Corporation, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: updater.exe
* Product Name: Firefox
* Company Name: Mozilla Foundation
* File Version: 81.0
* Product Version: 81.0
* Language: Language Neutral
* Legal Copyright: License: MPL 2
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a8393b5c7e98f4102ae599fb337003782cef5ee7fd48af20c647518cc08a3733/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Mozilla Firefox\updater.exe](updater.exe-904B85E7D09E0CEE3294D10F947E3183.md) | 35
[C:\Program Files\Mozilla Firefox\updater.exe](updater.exe-B0DC65F40D4D45A9E42628902C35422F.md) | 33
[C:\Program Files\Mozilla Thunderbird\updater.exe](updater.exe-07D16EADF927C51C736FA89A68A9F379.md) | 36
[C:\Program Files\Mozilla Thunderbird\updater.exe](updater.exe-321D1891CE307A8359422D69221531DD.md) | 33
[C:\program files\Mozilla Thunderbird\updater.exe](updater.exe-BF0362D3182C55DB7143EFA1098CEB6D.md) | 35

## Possible Misuse

*The following table contains possible examples of `updater.exe` being misused. While `updater.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONLOGON*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *DAILY*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONIDLE*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *Updater*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `description: Detects execution of the Notepad++ updater in a suspicious directory, which is often used in DLL side-loading attacks` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Users\\*\AppData\Local\Notepad++\updater\GUP.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Users\\*\AppData\Roaming\Notepad++\updater\GUP.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Program Files\Notepad++\updater\GUP.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Program Files (x86)\Notepad++\updater\GUP.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | $s12 = "Intel Integrated Graphics Updater" fullword wide /* PEStudio Blacklist: strings */ /* score: '12.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | $s5 = "Adobe Flash Plugin Updater" fullword wide /* PEStudio Blacklist: strings */ /* score: '11.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nkminer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nkminer.yar) | $f = "C:\\Windows\\Sys64\\updater.exe" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $string10 = "DynDNS\\Updater\\config.dyndns" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


