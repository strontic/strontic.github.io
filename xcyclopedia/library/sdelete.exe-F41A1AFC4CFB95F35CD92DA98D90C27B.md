---
title: sdelete.exe | Secure file delete
excerpt: What is sdelete.exe?
---

# sdelete.exe 

* File Path: `C:\SysinternalsSuite\sdelete.exe`
* Description: Secure file delete

## Hashes

Type | Hash
-- | --
MD5 | `F41A1AFC4CFB95F35CD92DA98D90C27B`
SHA1 | `B9C162E7817D7D99720FD97D9F7CAB342DD2812A`
SHA256 | `746DE8E02F1E64A707CE060A7D851B5D014698CA8692BD7AA945B40E06B01A07`
SHA384 | `A3131F9A43F3B39BDA41E32517C8F7712B283747F7F7FD350BAEA76D429BF0F62FBEE759F55F615AF80742D3F17CA43C`
SHA512 | `F8BEAA0DFE055687AABA6D342AF70379025325842AE7526D1453457EEDC90AA937CDB7DECC8A21BEF4D35BB0249A7BDF70AFAF37C57D5415AB33D294624BC9C2`
SSDEEP | `3072:oVJIiYscwdU1tjW/rhbPk16Z1zGpNdZUFIsIS6xtiC9WgKS6:ognPGPJ1y4IG2HKB`
IMP | `3B6B9B865564EEA9D1DD9D75F7A15C08`
PESHA1 | `619AF11A3DA87F5A19A738C425B3C66CEC0BB1D0`
PE256 | `294E53CEB34569E322DCF7C1FE7B47FDA4934E3C299029A5314188869E96CCA0`

## Runtime Data

### Usage (stdout):
```cmhg

SDelete v2.02 - Secure file delete
Copyright (C) 1999-2018 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: sdelete [-p passes] [-r] [-s] [-q] <file or directory> [...]
       sdelete [-p passes] [-z|-c [percent free]] <drive letter [...]>
       sdelete [-p passes] [-z|-c] <physical disk number>
   -c         Clean free space. Specify an option amount of space
              to leave free for use by a running system.
   -p         Specifies number of overwrite passes (default is 1)
   -r         Remove Read-Only attribute
   -s         Recurse subdirectories
   -z         Zero free space (good for virtual disk optimization)
   -nobanner  Do not display the startup banner and copyright message.

Disks must not have any volumes in order to be cleaned.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\sdelete.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdelete.exe
* Product Name: Sysinternals Sdelete
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.02
* Product Version: 2.02
* Language: English (United States)
* Legal Copyright: Copyright (C) 1999-2018 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/746de8e02f1e64a707ce060a7d851b5d014698ca8692bd7aa945b40e06b01a07/detection/


## Possible Misuse

*The following table contains possible examples of `sdelete.exe` being misused. While `sdelete.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_sdelete.yml) | `title: Secure Deletion with SDelete`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_sdelete.yml) | `description: Detects renaming of file while deletion with SDelete tool.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_sdelete.yml) | `- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/sdelete.htm`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_sdelete.yml) | `- https://docs.microsoft.com/en-gb/sysinternals/downloads/sdelete`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_sdelete.yml) | `- Legitimate usage of SDelete`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sysinternals_sdelete_file_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_delete/sysmon_sysinternals_sdelete_file_deletion.yml) | `title: Sysinternals SDelete File Deletion`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sysinternals_sdelete_file_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_delete/sysmon_sysinternals_sdelete_file_deletion.yml) | `description: A General detection to trigger for the deletion of files by Sysinternals SDelete. It looks for the common name pattern used to rename files.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sysinternals_sdelete_file_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_delete/sysmon_sysinternals_sdelete_file_deletion.yml) | `- Legitime usage of SDelete`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_sdelete.yml) | `title: Sysinternals SDelete Delete File`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_sdelete.yml) | `description: Use of SDelete to erase a file not the free space`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_sdelete.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_sdelete.yml) | `OriginalFileName: sdelete.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sysinternals_sdelete_registry_keys.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_sysinternals_sdelete_registry_keys.yml) | `title: Sysinternals SDelete Registry Keys`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sysinternals_sdelete_registry_keys.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_sysinternals_sdelete_registry_keys.yml) | `description: A General detection to trigger for the creation or modification of .*\Software\Sysinternals\SDelete registry keys. Indicators of the use of Sysinternals SDelete tool.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sysinternals_sdelete_registry_keys.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_sysinternals_sdelete_registry_keys.yml) | `TargetObject\|contains: '\Software\Sysinternals\SDelete'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "Malware, tools, or other non-native files dropped or created on a system by an adversary may leave traces behind as to what was done within a network and how. Adversaries may remove these files over the course of an intrusion to keep their footprint low or remove them at the end as part of the post-intrusion cleanup process.\n\nThere are tools available from the host operating system to perform cleanup, but adversaries may use other tools as well. Examples include native [cmd](https://attack.mitre.org/software/S0106) functions such as DEL, secure deletion tools such as Windows Sysinternals SDelete, or other third-party file deletion tools. (Citation: Trend Micro APT Attack Tools)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Malware, tools, or other non-native files dropped or created on a system by an adversary may leave traces behind as to what was done within a network and how. Adversaries may remove these files over the course of an intrusion to keep their footprint low or remove them at the end as part of the post-intrusion cleanup process.\n\nThere are tools available from the host operating system to perform cleanup, but adversaries may use other tools as well. Examples include native [cmd](https://attack.mitre.org/software/S0106) functions such as DEL, secure deletion tools such as Windows Sysinternals SDelete, or other third-party file deletion tools. (Citation: Trend Micro APT Attack Tools)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `"description": "Malware, tools, or other non-native files dropped or created on a system by an adversary may leave traces behind as to what was done within a network and how. Adversaries may remove these files over the course of an intrusion to keep their footprint low or remove them at the end as part of the post-intrusion cleanup process.\n\nThere are tools available from the host operating system to perform cleanup, but adversaries may use other tools as well. Examples include native [cmd](https:\/\/attack.mitre.org\/software\/S0106) functions such as DEL, secure deletion tools such as Windows Sysinternals SDelete, or other third-party file deletion tools. (Citation: Trend Micro APT Attack Tools)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Windows - Overwrite file with Sysinternals SDelete [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Windows - Overwrite file with Sysinternals SDelete [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | There are tools available from the host operating system to perform cleanup, but adversaries may use other tools as well. Examples include native [cmd](https://attack.mitre.org/software/S0106) functions such as DEL, secure deletion tools such as Windows Sysinternals SDelete, or other third-party file deletion tools. (Citation: Trend Micro APT Attack Tools)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | - [Atomic Test #1 - Windows - Overwrite file with Sysinternals SDelete](#atomic-test-1---windows---overwrite-file-with-sysinternals-sdelete) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | ## Atomic Test #1 - Windows - Overwrite file with Sysinternals SDelete | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | Overwrites and deletes a file using Sysinternals SDelete. Upon successful execution, "Files deleted: 1" will be displayed in | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | \| sdelete_exe \| Path of sdelete executable \| Path \| $env:TEMP&#92;Sdelete&#92;sdelete.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | Invoke-WebRequest "https://download.sysinternals.com/files/SDelete.zip" -OutFile "$env:TEMP\SDelete.zip" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | Expand-Archive $env:TEMP\SDelete.zip $env:TEMP\Sdelete -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | Remove-Item $env:TEMP\SDelete.zip -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


