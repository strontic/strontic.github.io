---
title: procexp.exe | Sysinternals Process Explorer
excerpt: What is procexp.exe?
---

# procexp.exe 

* File Path: `C:\SysinternalsSuite\procexp.exe`
* Description: Sysinternals Process Explorer

## Hashes

Type | Hash
-- | --
MD5 | `4BEB112371B140401E8602529735EA5D`
SHA1 | `CD6EE082F8BB39C3A7B1E2A73B4A719360145FBC`
SHA256 | `6470116B78B88A3062225D66A7A6040C507B9C5094550E33AECE520BFB88AB57`
SHA384 | `E5BBD9199A88BC871A94F8CCB7D30EB38B3E17A71792306BA7601DB2CC838FE96E8E5FAC1058D9FFEE82EB36C6E0EB93`
SHA512 | `0EB9B8109FC67D8BDBED58115F013FC28F704138F4EFED8131386CBBC73DCAC76D5022F22D0F54FEA1AE23D5B209E979E51A13337129F5FB8B17930A153B69FC`
SSDEEP | `49152:DO0LlXr5Y6NbFSAM88j5j/gXYWZz1gXU8a8kDKfzLL:1LMQFSI0+eEIlL`
IMP | `F1D93E5D6F71D30385BE0C8D6AEC3CC8`
PESHA1 | `5BDAE213C66C4D58767AD9ACA790829491581567`
PE256 | `BF1CBEEE6902AC7F49850D267E8D348997D1FBE44B9E7A81845B07AC268C681D`

## Runtime Data

### Child Processes:
procexp64.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\aclui.dll.mui | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\Procexp32bitSection | Section


### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\procexp.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Procexp.exe
* Product Name: Process Explorer
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 16.32
* Product Version: 16.32
* Language: English (United States)
* Legal Copyright: Copyright  1998-2020 Mark Russinovich 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6470116b78b88a3062225d66a7a6040c507b9c5094550e33aece520bfb88ab57/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\procexp64.exe](procexp64.exe-6A36347F94713B99C0FC103C6F205719.md) | 55

## Possible Misuse

*The following table contains possible examples of `procexp.exe` being misused. While `procexp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_lsass_dump_generic.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_lsass_dump_generic.yml) | `- '\procexp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\procexp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_procexplorer_driver_created_in_tmp_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_procexplorer_driver_created_in_tmp_folder.yml) | `- '*\procexp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `- '\procexp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_service_installed.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_service_installed.yml) | `- '*\procexp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 C:\ADS\procexp.cab c:\ADS\file.txt:procexp.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | \| download_url \| Download URL \| String \| https://live.sysinternals.com/procexp.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $fname1 = "$env:TEMP\procexp.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $sheet.Cells.Item(2,1) = "procexp.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | Stop-Process -Name "procexp*" -ErrorAction Ignore | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | Remove-Item "$env:TEMP\procexp.exe" -ErrorAction Ignore | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | extrac32 #{path}\procexp.cab #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | findstr /V /L W3AllLov3DonaldTrump #{path}\procexp.exe > #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $s2 = "procexp" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"procexp",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


