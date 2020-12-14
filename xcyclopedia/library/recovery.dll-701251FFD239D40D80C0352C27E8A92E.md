---
title: recovery.dll | Recovery Control Panel
excerpt: What is recovery.dll?
---

# recovery.dll 

* File Path: `C:\Windows\system32\recovery.dll`
* Description: Recovery Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `701251FFD239D40D80C0352C27E8A92E`
SHA1 | `55246724814ACFB3C2B972252BAA3784D5A23F18`
SHA256 | `1B9A7FFD5E7E29A638DE64977AC2E8B4B3BD2334EA761C9773A1D4C45B115DA3`
SHA384 | `900F481C54C6CCF1BF8C2808972195A41C61FC8BCF0447F8FBC2A87CF0EB2EDBD1A9207E434BF35A24F1B66506F3C89A`
SHA512 | `DDE72F9BB6E65FA12D4768797C7F2635D3578F530B900A05BC55373CDBDCFD0B09D184783B5754E4D1192524DFE49D7F151AB462664B8D5F1DC31E063554ACBC`
SSDEEP | `3072:gBJO4rLxVfsQ1vJ1w2pLtnKsED2UDotutuniweiiJD43:gfXLjp5J1w2pLtnKsBS`
IMP | `E55945011FDE37B6836CEE609C18A8F4`
PESHA1 | `03578F9331ADD57F34ABB073EA9DB98873796D61`
PE256 | `521406870FEAA20957A9B4EAFEBDBCE8FD653C9B60E660E2B0D9D0122955829C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RECOVERY.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/1b9a7ffd5e7e29a638de64977ac2e8b4b3bd2334ea761c9773a1d4c45b115da3/detection/


## Possible Misuse

*The following table contains possible examples of `recovery.dll` being misused. While `recovery.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [aws_rds_public_db_restore.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_rds_public_db_restore.yml) | `description: Detects the recovery of a new public database instance from a snapshot. It may be a part of data exfiltration.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_creddumper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_mal_creddumper.yml) | `- Legitimate Administrator using credential dumping tool for password recovery` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_tools_dropped_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_cred_dump_tools_dropped_files.yml) | `- Legitimate Administrator using tool for password recovery` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mimikatz_command_line.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mimikatz_command_line.yml) | `- Legitimate Administrator using tool for password recovery` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_tools_named_pipes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_cred_dump_tools_named_pipes.yml) | `- Legitimate Administrator using tool for password recovery` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-crutch-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-crutch-event.json) | `"comment": "Recovery C&C",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1490 Inhibit System Recovery](../../T1490/T1490.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Windows - Disable Windows Recovery Console Repair [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - T1490 Inhibit System Recovery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - T1490 Inhibit System Recovery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1490 Inhibit System Recovery](../../T1490/T1490.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: Windows - Disable Windows Recovery Console Repair [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/linux-matrix.md) | \| Spearphishing via Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Unix Shell](../../T1059.004/T1059.004.md) \| [Cron](../../T1053.003/T1053.003.md) \| Local Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Disable or Modify System Firewall](../../T1562.004/T1562.004.md) \| OS Credential Dumping [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Network Sniffing](../../T1040/T1040.md) \|  \| Email Collection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Scheduled Transfer [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| External Proxy [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Inhibit System Recovery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/macos-matrix.md) | \| Trusted Relationship [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Software Deployment Tools [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Event Triggered Execution [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Kernel Modules and Extensions [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Execution Guardrails [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| OS Credential Dumping [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Process Discovery](../../T1057/T1057.md) \|  \| Keylogging [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Scheduled Transfer [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| External Proxy [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Inhibit System Recovery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \| Spearphishing Link [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Malicious File](../../T1204.002/T1204.002.md) \| Boot or Logon Initialization Scripts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [COR_PROFILER](../../T1574.012/T1574.012.md) \| Code Signing [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Forced Authentication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Network Service Scanning](../../T1046/T1046.md) \| SSH [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Data from Removable Media [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Scheduled Transfer [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| External Proxy [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Inhibit System Recovery](../../T1490/T1490.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \| Spearphishing via Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Scheduled Task](../../T1053.005/T1053.005.md) \| [Change Default File Association](../../T1546.001/T1546.001.md) \| Component Object Model Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Control Panel](../../T1218.002/T1218.002.md) \| [Group Policy Preferences](../../T1552.006/T1552.006.md) \| Peripheral Device Discovery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Software Deployment Tools [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Email Forwarding Rule [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Scheduled Transfer [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| External Proxy [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Inhibit System Recovery](../../T1490/T1490.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | # T1490 - Inhibit System Recovery | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | <blockquote>Adversaries may delete or remove built-in operating system data and turn off services designed to aid in the recovery of a corrupted system to prevent recovery.(Citation: Talos Olympic Destroyer 2018)(Citation: FireEye WannaCry 2017) Operating systems may contain features that can help fix corrupted systems, such as a backup catalog, volume shadow copies, and automatic repair features. Adversaries may disable or delete system recovery features to augment the effects of [Data Destruction](https://attack.mitre.org/techniques/T1485) and [Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486).(Citation: Talos Olympic Destroyer 2018)(Citation: FireEye WannaCry 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | A number of native Windows utilities have been used by adversaries to disable or delete system recovery features: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | * <code>bcdedit.exe</code> can be used to disable automatic Windows recovery features by modifying boot configuration data - <code>bcdedit.exe /set {default} bootstatuspolicy ignoreallfailures & bcdedit /set {default} recoveryenabled no</code></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | - [Atomic Test #4 - Windows - Disable Windows Recovery Console Repair](#atomic-test-4---windows---disable-windows-recovery-console-repair) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | ## Atomic Test #4 - Windows - Disable Windows Recovery Console Repair | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | Disables repair by the Windows Recovery Console on boot. This technique is used by numerous ransomware families and APT malware such as Olympic Destroyer. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | Adversaries may attempt to shutdown/reboot a system after impacting it in other ways, such as [Disk Structure Wipe](https://attack.mitre.org/techniques/T1561/002) or [Inhibit System Recovery](https://attack.mitre.org/techniques/T1490), to hasten the intended effects on system availability.(Citation: Talos Nyetya June 2017)(Citation: Talos Olympic Destroyer 2018)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | <blockquote>Adversaries may create or modify Windows services to repeatedly execute malicious payloads as part of persistence. When Windows boots up, it starts programs or applications called services that perform background system functions.(Citation: TechNet Services) Windows service configuration information, including the file path to the service's executable or recovery programs/commands, is stored in the Windows Registry. Service configurations can be modified using utilities such as sc.exe and [Reg](https://attack.mitre.org/software/S0075).  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_buckeye.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_buckeye.yar) | $s8 = "Chrome Password Recovery" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_lockergoga.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_lockergoga.yar) | $rn1 = "This may lead to the impossibility of recovery of the certain files." wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | Identifier: Windows Password Recovery | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file loader.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file loader64.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file ast.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file ast64.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "Windows Password Recovery" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file ast64.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $fp5 = "Disaster Recovery Module" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


