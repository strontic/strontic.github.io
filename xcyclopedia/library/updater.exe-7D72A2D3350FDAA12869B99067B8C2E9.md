---
title: updater.exe | CDBurnerXP Updater
excerpt: What is updater.exe?
---

# updater.exe 

* File Path: `C:\Program Files\CDBurnerXP\updater.exe`
* Description: CDBurnerXP Updater

## Hashes

Type | Hash
-- | --
MD5 | `7D72A2D3350FDAA12869B99067B8C2E9`
SHA1 | `BB19FFF09988F50C53F0C7C2753D4EA6C60274BB`
SHA256 | `D552A297A9393EA9A0AAD2B5649D7D7749D9A098ECB8CDE0823C3674024A28CE`
SHA384 | `EAFEAFCA6F1513AE76450A2B478CA0AD4D2B9FAAB3B55F12E020210DD222CFEEDABF858ECB72F5DBB1BF80F58401CDD5`
SHA512 | `E0C8B54FADBAA8778C2EBF1F477838E9227BF3B5A6F1F8AEF0BB41283666D9DA44A5B023C8633919B88A3A445910F29CE8F82D898250AEBA9C5A9A089C465034`
SSDEEP | `384:Q2cAbR1ciHKCrQOAPFtEXW0do6J0DeOVSi2SWsaS:jbR1OOAdAa6GiBlSX`
PESHA1 | `27972A2FF680B7C4178F357B32566E1B71FC2F06`
PE256 | `F6F14A343D8522F74F20BCAEC1B50A9E29903935C086D0648A3A3BDF8BB69FAA`

## Runtime Data

### Usage (stderr):
```cmhg

Unhandled Exception: System.ComponentModel.Win32Exception: The system cannot find the file specified
   at System.Diagnostics.Process.StartWithShellExecuteEx(ProcessStartInfo startInfo)
   at System.Diagnostics.Process.Start(ProcessStartInfo startInfo)
   at CDBurnerXP.Net.Updater.Program.Main(String[] args)

```

### Child Processes:
updater.exe WerFault.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\xCyclopedia | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_4616 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\CDBurnerXP\updater.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `0847C0D333578DAFA9934DA5A3788807`
* Thumbprint: `1DF029D672CDF9B2963CD9CB3ABD36D7795A12FE`
* Issuer: CN=thawte SHA256 Code Signing CA, O="thawte, Inc.", C=US
* Subject: CN=Canneverbe Limited, OU=Canneverbe Limited, O=Canneverbe Limited, L=Goch, S=North Rhine-Westphalia, C=DE

## File Metadata

* Original Filename: updater.exe
* Product Name: CDBurnerXP Updater
* Company Name: Canneverbe Limited
* File Version: 4.5.8.7128
* Product Version: 4.5.8.7128
* Language: Language Neutral
* Legal Copyright: Copyright 2008 Canneverbe Limited
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d552a297a9393ea9a0aad2b5649d7d7749d9a098ecb8cde0823c3674024a28ce/detection/


## Possible Misuse

*The following table contains possible examples of `updater.exe` being misused. While `updater.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONLOGON*/TN *Updater*/TR *powershell*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *DAILY*/TN *Updater*/TR *powershell*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONIDLE*/TN *Updater*/TR *powershell*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *Updater*/TN *Updater*/TR *powershell*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_disable_raccine.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_disable_raccine.yml) | `- 'Raccine Rules Updater'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `description: Detects execution of the Notepad++ updater in a suspicious directory, which is often used in DLL side-loading attacks`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Users\\*\AppData\Local\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Users\\*\AppData\Roaming\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Program Files\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- ':\Program Files (x86)\Notepad++\updater\GUP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_gup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_gup.yml) | `- Execution of tools named GUP.exe and located in folders different than Notepad++\updater`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Gpup.yml) | `- 'C:\Program Files (x86)\Notepad++\updater\gpup.exe    '`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Update.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Update.yml) | `- Link: https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/microsoft-teams-updater-living-off-the-land/`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-kryptocibule.json](https://github.com/eset/malware-ioc/blob/master/kryptocibule/misp-kryptocibule.json) | `"value": "%ProgramFiles(X86)%\\Adobe\\Acrobat Reader DC\\Reader\\Update\\Updater.exe",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `.Updater (`Updater.exe`)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `%ProgramFiles(X86)%\Adobe\Acrobat Reader DC\Reader\Update\Updater.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Upon successful execution, powershell.exe will be copied and renamed to updater.exe and load amsi.dll from a non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | copy %windir%\System32\windowspowershell\v1.0\powershell.exe %APPDATA%\updater.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | %APPDATA%\updater.exe -Command exit | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | del %APPDATA%\updater.exe >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | $s12 = "Intel Integrated Graphics Updater" fullword wide /* PEStudio Blacklist: strings */ /* score: '12.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | $s5 = "Adobe Flash Plugin Updater" fullword wide /* PEStudio Blacklist: strings */ /* score: '11.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nkminer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nkminer.yar) | $f = "C:\\Windows\\Sys64\\updater.exe" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $string10 = "DynDNS\\Updater\\config.dyndns" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [1258b063-27d6-489b-a677-4807faacf868.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/1258b063-27d6-489b-a677-4807faacf868.yml) | `"microsoft.tri.sensor.updater",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


