﻿---
title: uninstall.exe | ImgBurn Installer
excerpt: What is uninstall.exe?
---

# uninstall.exe 

* File Path: `C:\Program Files (x86)\ImgBurn\uninstall.exe`
* Description: ImgBurn Installer

## Hashes

Type | Hash
-- | --
MD5 | `EFF839D29DBB06677A85117D036E29C6`
SHA1 | `473823C718F3DB95D27F14B783E68C08F13CADED`
SHA256 | `1B5CB8035B18D06B5219F2E7D30200CA343C0CE6763962C7C41534AECC2B1C80`
SHA384 | `11538F744BBDF79A2A8D9FE98A0139ABCE0CCF4AA36628B8D4D1137C03EC53FD084006DC2236D9B02D0C8B367D11C13F`
SHA512 | `CB4FB2B054E3430DF934CD30BE220E13C2F86BF2DBC6E2A46D59FA4F7D9C6FECA9CBC44FB1CC49BFAE7AA39623D26D8F4510FA9A0584A1F64110CAE87117AFF3`
SSDEEP | `1536:oRPYqa5pic6jXFdL2KiMcH8gg+SsN7buCryG4DelpkF1LSQHYc:MPA6jXFN2McH8b+vnuCryGmjGS`
IMP | `B1A57B635B23FFD553B3FD1E0960B2BD`
PESHA1 | `0F4D40AF47FFBB84AC78D408F19D060CDED15151`
PE256 | `2BBB62D6A0B90D21CC3241688452DE54486A247AC7C774A9A5AAB73580814104`

## Runtime Data

### Child Processes:
Au_.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\ImgBurn\uninstall.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\ImgBurn\uninstall.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: ImgBurn
* Company Name: LIGHTNING UK!
* File Version: 2.5.8.0
* Product Version: 2.5.8.0
* Language: English (United Kingdom)
* Legal Copyright: Copyright 2005 - 2016
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1b5cb8035b18d06b5219f2e7d30200ca343c0ce6763962c7c41534aecc2b1c80/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\NVDA\uninstall.exe](uninstall.exe-2F5FBCA5E5E61BB01D8E7A69340BF951.md) | 46
[C:\Program Files (x86)\NVDA\uninstall.exe](uninstall.exe-F5B1D84438A3E34FDAD1AF8AC4623F40.md) | 52

## Possible Misuse

*The following table contains possible examples of `uninstall.exe` being misused. While `uninstall.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_software_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_software_discovery.yml) | `ScriptBlockText\|contains\|all:    # Example: Get-ItemProperty HKLM:\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\* \| Select-Object DisplayName, DisplayVersion, Publisher, InstallDate \| Format-Table -Autosize`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uninstall_crowdstrike_falcon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_uninstall_crowdstrike_falcon.yml) | `title: Uninstall Crowdstrike Falcon`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uninstall_crowdstrike_falcon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_uninstall_crowdstrike_falcon.yml) | `- ' /uninstall'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uninstall_crowdstrike_falcon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_uninstall_crowdstrike_falcon.yml) | `- Uninstall by admin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_disable_raccine.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_disable_raccine.yml) | `title: Raccine Uninstall`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wmic_security_product_uninstall.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wmic_security_product_uninstall.yml) | `title: Wmic Uninstall Security Product`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wmic_security_product_uninstall.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wmic_security_product_uninstall.yml) | `- 'call uninstall'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `Description: The Installer tool is a command-line utility that allows you to install and uninstall server resources by executing the installer components in specified assemblies`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `uninstall`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `uninstall-lock`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #11: Uninstall Sysmon [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #21: Uninstall Crowdstrike Falcon on Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: InstallUtil Uninstall method call - /U variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #6: InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Regasm Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Regsvcs Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #11: Uninstall Sysmon [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #21: Uninstall Crowdstrike Falcon on Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: InstallUtil Uninstall method call - /U variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #6: InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Regasm Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Regsvcs Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1095.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1095/T1095.md) | if( $null -eq (Get-ItemProperty HKLM:\Software\Microsoft\Windows\CurrentVersion\Uninstall\* \| ?{$_.DisplayName -like "Microsoft Visual C++*"}) ) { | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #5 - InstallUtil Uninstall method call - /U variant](#atomic-test-5---installutil-uninstall-method-call---u-variant) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #6 - InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant](#atomic-test-6---installutil-uninstall-method-call---installtypenotransaction-actionuninstall-variant) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #5 - InstallUtil Uninstall method call - /U variant | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Executes the Uninstall Method. Upon execution, version information will be displayed the .NET framework install utility. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | InstallUtil Uninstall method execution test failure. Installer assembly execution output did not match the expected output. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #6 - InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | $CommandLine = "/logfile= /logtoconsole=false /installtype=notransaction /action=uninstall `"$InstallerAssemblyFullPath`"" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Executes the Uninstall Method. Upon execution, help information will be displayed for InstallUtil. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | - [Atomic Test #1 - Regasm Uninstall Method Call Test](#atomic-test-1---regasm-uninstall-method-call-test) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | - [Atomic Test #2 - Regsvcs Uninstall Method Call Test](#atomic-test-2---regsvcs-uninstall-method-call-test) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | ## Atomic Test #1 - Regasm Uninstall Method Call Test | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | Executes the Uninstall Method, No Admin Rights Required. Upon execution, "I shouldn't really execute either." will be displayed. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | ## Atomic Test #2 - Regsvcs Uninstall Method Call Test | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | Executes the Uninstall Method, No Admin Rights Required, Requires SNK. Upon execution, "I shouldn't really execute" will be displayed | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | $file = 'C:\Program Files (x86)\TeamViewer\uninstall.exe' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | get-package *'LogMeIn Client'* -ErrorAction Ignore \| uninstall-package  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1505.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1505.002/T1505.002.md) | Uninstall-TransportAgent #{transport_agent_identity} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | Get-ItemProperty HKLM:\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\* \| Select-Object DisplayName, DisplayVersion, Publisher, InstallDate \| Format-Table -Autosize | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | Get-ItemProperty HKLM:\Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\* \| Select-Object DisplayName, DisplayVersion, Publisher, InstallDate \| Format-Table -Autosize | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | - [Atomic Test #11 - Uninstall Sysmon](#atomic-test-11---uninstall-sysmon) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | - [Atomic Test #21 - Uninstall Crowdstrike Falcon on Windows](#atomic-test-21---uninstall-crowdstrike-falcon-on-windows) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | ## Atomic Test #11 - Uninstall Sysmon | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Uninstall Sysinternals Sysmon for Defense Evasion | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | ## Atomic Test #21 - Uninstall Crowdstrike Falcon on Windows | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Uninstall Crowdstrike Falcon. If the WindowsSensor.exe path is not provided as an argument we need to search for it. Since the executable is located in a folder named with a random guid we need to identify it before invoking the uninstaller. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if (Test-Path "#{falcond_path}") {. "#{falcond_path}" /repair /uninstall /quiet } else { Get-ChildItem -Path "C:\ProgramData\Package Cache" -Include "WindowsSensor.exe" -Recurse \| % { $sig=$(Get-AuthenticodeSignature -FilePath $_.FullName); if ($sig.Status -eq "Valid" -and $sig.SignerCertificate.DnsNameList -eq "CrowdStrike, Inc.") { . "$_" /repair /uninstall /quiet; break;} }} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $x4 = "%s version %s already has persistence installed. If you want to uninstall," fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $s2 = "rundll32.exe \"%s\", UnInstall /update %s" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_buzus_softpulse.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_buzus_softpulse.yar) | $s4 = "CurrentVersion\\Uninstall\\avast" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $a7 = "Uninstall.jarPK" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $a = "Unable to uninstall the fgexec service" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "%s -Uninstall                        -->To Uninstall The Service" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s6 = "Can't uninstall,maybe the backdoor is not installed or,the Password you INPUT is" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


