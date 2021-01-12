---
title: helper.exe | Firefox Helper
excerpt: What is helper.exe?
---

# helper.exe 

* File Path: `C:\Program Files\Mozilla Firefox\uninstall\helper.exe`
* Description: Firefox Helper

## Hashes

Type | Hash
-- | --
MD5 | `4958534E5BCCC61DF92FFE8C75449A3E`
SHA1 | `44B28EFAF47404229DED05A139991F11025A1994`
SHA256 | `4A634A544816803777F9563B6A7F8C249F533A673D9272DB00C52091C6014349`
SHA384 | `71E0A27FB732A3C3B1BEADDB86A8EDCDAA342E733DCBAFBD71A2D573BC50CCE0D556B75EAEAD37022636BD8035D0A311`
SHA512 | `A1112981A369990C2EA388C2EC7C9C72B8DCE45BEFDF919D448D7DE0CE1C67122E9874ECC51F7955A9D5BF44B2F6577A91AF1A67EC3BAC383BC09F97977D9E71`
SSDEEP | `12288:PcUUjD58lP7y8H+RNUDDvmEP77+7qB3DWKtsm453:P5p/eRSu7C3D1tT453`

## Signature

* Status: Signature verified.
* Serial: `0DDEB53F957337FBEAF98C4A615B149D`
* Thumbprint: `91CABEA509662626E34326687348CAF2DD3B4BBA`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: E="release+certificates@mozilla.com", CN=Mozilla Corporation, OU=Firefox Engineering Operations, O=Mozilla Corporation, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: helper.exe
* Product Name: Firefox
* Company Name: Mozilla Corporation
* File Version: 79.0
* Product Version: 79.0
* Language: English (United States)
* Legal Copyright: Mozilla Corporation


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Mozilla Firefox\uninstall\helper.exe](helper.exe-34EAD4BDF94FFBC7C4336E5279B748AC.md) | 88
[C:\Program Files\Mozilla Firefox\uninstall\helper.exe](helper.exe-955304089E5347F4322D7FC3E76B0AC4.md) | 88
[C:\program files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-40F9693E22DFF3BAC12327E1AFC040C6.md) | 65
[C:\Program Files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-8FA842C0D816C2DEB70A40213C7E62D3.md) | 65
[C:\Program Files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-BB2FD747BDC619EB96D693D665F403C7.md) | 68

## Possible Misuse

*The following table contains possible examples of `helper.exe` being misused. While `helper.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_winlogon_helper_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_winlogon_helper_dll.yml) | `title: Winlogon Helper DLL` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_winlogon_helper_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_winlogon_helper_dll.yml) | `description: Winlogon.exe is a Windows component responsible for actions at logon/logoff as well as the secure attention sequence (SAS) triggered by Ctrl-Alt-Delete. Registry entries in HKLM\Software[Wow6432Node]Microsoft\Windows NT\CurrentVersion\Winlogon\ and HKCU\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ are used to manage additional helper programs and functionalities that support Winlogon. Malicious modifications to these Registry keys may cause Winlogon to load and execute malicious DLLs and/or executables.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `description: Detects persitence via netsh helper` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `- 'helper'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `- Command: netsh.exe add helper C:\Path\file.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `Description: Load (execute) NetSh.exe helper DLL file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `Description: Helper binary for Assistive Technology (AT)` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Command: netsh.exe add helper C:\Users\User\file.dll` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "RC2FM helper DLL",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `==== RC2FM helper DLL` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1547.004 Winlogon Helper DLL](../../T1547.004/T1547.004.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1547.004 Winlogon Helper DLL](../../T1547.004/T1547.004.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Launch Daemon](../../T1543.004/T1543.004.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [Gatekeeper Bypass](../../T1553.001/T1553.001.md) \| Unsecured Credentials [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [Path Interception by Unquoted Path](../../T1574.009/T1574.009.md) \| [Hide Artifacts](../../T1564/T1564.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Systemd Timers [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \| [Password Filter DLL](../../T1556.002/T1556.002.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \|  \| Process Doppelgänging [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Local Account](../../T1136.001/T1136.001.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [File Deletion](../../T1070.004/T1070.004.md) \| [Security Account Manager](../../T1003.002/T1003.002.md) \|  \|  \|  \|  \| [Remote Access Software](../../T1219/T1219.md) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Path Interception [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Hidden File System [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Steal or Forge Kerberos Tickets [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \| Symmetric Cryptography [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Shortcut Modification](../../T1547.009/T1547.009.md) \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \| [Odbcconf](../../T1218.008/T1218.008.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \|  \| Portable Executable Injection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | # T1546.007 - Netsh Helper DLL | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | <blockquote>Adversaries may establish persistence by executing malicious content triggered by Netsh Helper DLLs. Netsh.exe (also referred to as Netshell) is a command-line scripting utility used to interact with the network configuration of a system. It contains functionality to add helper DLLs for extending functionality of the utility. (Citation: TechNet Netsh) The paths to registered netsh.exe helper DLLs are entered into the Windows Registry at <code>HKLM\SOFTWARE\Microsoft\Netsh</code>. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | Adversaries can use netsh.exe helper DLLs to trigger execution of arbitrary code in a persistent manner. This execution would take place anytime netsh.exe is executed, which could happen automatically, with another persistence technique, or if other software (ex: VPN) is present on the system that executes netsh.exe as part of its normal functionality. (Citation: Github Netsh Helper CS Beacon)(Citation: Demaske Netsh Persistence)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | - [Atomic Test #1 - Netsh Helper DLL Registration](#atomic-test-1---netsh-helper-dll-registration) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | ## Atomic Test #1 - Netsh Helper DLL Registration | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | netsh.exe add helper #{helper_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | # T1547.004 - Winlogon Helper DLL | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | <blockquote>Adversaries may abuse features of Winlogon to execute DLLs and/or executables when a user logs in. Winlogon.exe is a Windows component responsible for actions at logon/logoff as well as the secure attention sequence (SAS) triggered by Ctrl-Alt-Delete. Registry entries in <code>HKLM\Software[\\Wow6432Node\\]\Microsoft\Windows NT\CurrentVersion\Winlogon\</code> and <code>HKCU\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\</code> are used to manage additional helper programs and functionalities that support Winlogon. (Citation: Cylance Reg Persistence Sept 2013)  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Bypasses User Account Control using the Windows 10 Features on Demand Helper (fodhelper.exe). Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | PowerShell code to bypass User Account Control using the Windows 10 Features on Demand Helper (fodhelper.exe). Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [apis.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/apis.md) | , , Winlogon Helper DLL, , Timestomp, , , , , , | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_dec15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_dec15.yar) | description = "Dropped C&C helper DLL for AZZY 4.3" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_crypto_miner.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_crypto_miner.yar) | description = "Detects helper script used in a crypto miner campaign" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_anomalies_keyword_combos.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_anomalies_keyword_combos.yar) | $fp5 = "Firefox Helper" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s2 = "AcroTray - Adobe Acrobat Distiller helper application" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s2 = "Virtual hardware upgrade helper service" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


