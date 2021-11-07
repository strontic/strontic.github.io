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
MD5 | `955304089E5347F4322D7FC3E76B0AC4`
SHA1 | `7FD0CF37B020450D512FD5BA193BE8013E5E7108`
SHA256 | `FD88B09D22F87EA4DBE88BA67B89531D5B8ADB21BD279A0EF6506F3360A1273A`
SHA384 | `8B25F0F2582A9E1882E74D0BED996E0AF5CF9F12325450174B8F33A8D608845665827ACABF1C214B4B34A221A97B6EFF`
SHA512 | `64DAFA3DD0EB0271138F7D7FB7CB37A4E1339218DC1B88578D4A658F66F385E5C69469ECFC6773EAD84DC32C8E9A579F2D567421DB6197E8566FA35874691DF0`
SSDEEP | `12288:xcUUjD5cxP7y8H+RNUDDvAP77+7qB3DWKtsm45M:x59/eR1u7C3D1tT45M`
IMP | `E2A592076B17EF8BFB48B7E03965A3FC`
PESHA1 | `A879D9D33664F16E1DC75F239187C2DEC1D06520`
PE256 | `F4124ADC4CEC65B86CA41C39D50AC850B4A9D64F94EF06E239852333F8CD1138`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files\Mozilla Firefox\uninstall\helper.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* File Version: 81.0
* Product Version: 81.0
* Language: English (United States)
* Legal Copyright: Mozilla Corporation
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/fd88b09d22f87ea4dbe88ba67b89531d5b8adb21bd279a0ef6506f3360a1273a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Mozilla Firefox\uninstall\helper.exe](helper.exe-34EAD4BDF94FFBC7C4336E5279B748AC.md) | 88
[C:\Program Files\Mozilla Firefox\uninstall\helper.exe](helper.exe-4958534E5BCCC61DF92FFE8C75449A3E.md) | 88
[C:\Program Files\Mozilla Firefox\uninstall\helper.exe](helper.exe-4FFCFBE9E8F8D41B4FCA6598B313BC9C.md) | 52
[C:\Program Files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-3B1D817E52F9DA64E69F67CB27EB2FFD.md) | 58
[C:\program files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-40F9693E22DFF3BAC12327E1AFC040C6.md) | 65
[C:\Program Files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-8FA842C0D816C2DEB70A40213C7E62D3.md) | 65
[C:\Program Files\Mozilla Thunderbird\uninstall\helper.exe](helper.exe-BB2FD747BDC619EB96D693D665F403C7.md) | 65

## Possible Misuse

*The following table contains possible examples of `helper.exe` being misused. While `helper.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_winlogon_helper_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_winlogon_helper_dll.yml) | `title: Winlogon Helper DLL`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_winlogon_helper_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_winlogon_helper_dll.yml) | `description: Winlogon.exe is a Windows component responsible for actions at logon/logoff as well as the secure attention sequence (SAS) triggered by Ctrl-Alt-Delete. Registry entries in HKLM\Software[Wow6432Node]Microsoft\Windows NT\CurrentVersion\Winlogon\ and HKCU\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ are used to manage additional helper programs and functionalities that support Winlogon. Malicious modifications to these Registry keys may cause Winlogon to load and execute malicious DLLs and/or executables.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `description: Detects persitence via netsh helper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `- 'helper'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_pcwutl.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_pcwutl.yml) | `- Use of Program Compatibility Troubleshooter Helper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_asep_reg_keys_modification.yml) | `- '\Explorer\Browser Helper Objects'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Netsh.yml) | `- Command: netsh.exe add helper C:\Path\file.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Netsh.yml) | `Description: Load (execute) NetSh.exe helper DLL file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `Description: Helper binary for Assistive Technology (AT)`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Command: netsh.exe add helper C:\Users\User\file.dll`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "RC2FM helper DLL",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `==== RC2FM helper DLL`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_helper_dll.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_helper_dll.yml) | `title: InvisiMole Helper DLLs dropped`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1547.004 Winlogon Helper DLL](../../T1547.004/T1547.004.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1547.004 Winlogon Helper DLL](../../T1547.004/T1547.004.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Local Account](../../T1136.001/T1136.001.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [File Deletion](../../T1070.004/T1070.004.md) \| Unsecured Credentials [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Path Interception by Search Order Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Hidden Files and Directories](../../T1564.001/T1564.001.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Systemd Service](../../T1543.002/T1543.002.md) \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \| [Pass the Ticket](../../T1550.003/T1550.003.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \|  \| [Process Hollowing](../../T1055.012/T1055.012.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Logon Script (Windows)](../../T1037.001/T1037.001.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| File and Directory Permissions Modification [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Silver Ticket [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \| Traffic Signaling [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [Parent PID Spoofing](../../T1134.004/T1134.004.md) \| Hidden File System [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Steal or Forge Kerberos Tickets [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \| Web Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Shortcut Modification](../../T1547.009/T1547.009.md) \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \| [Odbcconf](../../T1218.008/T1218.008.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \|  \| Portable Executable Injection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | Invoke-WebRequest -OutFile C:\Users\$env:username\Downloads\GoToAssist.exe "https://launch.getgo.com/launcher2/helper?token=e0-FaCddxmtMoX8_cY4czssnTeGvy83ihp8CLREfvwQshiBW0_RcbdoaEp8IA-Qn8wpbKlpGIflS-39gW6RuWRM-XHwtkRVMLBsp5RSKp-a3PBM-Pb1Fliy73EDgoaxr-q83WtXbLKqD7-u3cfDl9gKsymmhdkTGsXcDXir90NqKj92LsN_KpyYwV06lIxsdRekhNZjNwhkWrBa_hG8RQJqWSGk6tkZLVMuMufmn37eC2Cqqiwq5bCGnH5dYiSUUsklSedRLjh4N46qPYT1bAU0qD25ZPr-Kvf4Kzu9bT02q3Yntj02ZA99TxL2-SKzgryizoopBPg4Ilfo5t78UxKTYeEwo4etQECfkCRvenkTRlIHmowdbd88zz7NiccXnbHJZehgs6_-JSVjQIdPTXZbF9T5z44mi4BQYMtZAS3DE86F0C3D4Tcd7fa5F6Ve8rQWt7pvqFCYyiJAailslxOw0LsGyFokoy65tMF980ReP8zhVcTKYP8s8mhGXihUQJQPNk20Sw&downloadTrigger=restart&renameFile=1" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
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
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_dec15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_dec15.yar) | description = "Dropped C&C helper DLL for AZZY 4.3" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_crypto_miner.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_crypto_miner.yar) | description = "Detects helper script used in a crypto miner campaign" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_anomalies_keyword_combos.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_anomalies_keyword_combos.yar) | $fp5 = "Firefox Helper" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s2 = "AcroTray - Adobe Acrobat Distiller helper application" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s2 = "Virtual hardware upgrade helper service" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


