---
title: RegSvcs.exe | Microsoft .NET Services Installation Utility
excerpt: What is RegSvcs.exe?
---

# RegSvcs.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegSvcs.exe`
* Description: Microsoft .NET Services Installation Utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `9D352BC46709F0CB5EC974633A0C3C94`
SHA1 | `1969771B2F022F9A86D77AC4D4D239BECDF08D07`
SHA256 | `2C1EEB7097023C784C2BD040A2005A5070ED6F3A4ABF13929377A9E39FAB1390`
SHA384 | `AAE75E0B7A687B971D7F3C9694934F26243E79FE1487DBB8E7A255096694D7E8CF48E186F4C97832E1B0F5ADCDA09490`
SHA512 | `13C714244EC56BEEB202279E4109D59C2A43C3CF29F90A374A751C04FD472B45228CA5A0178F41109ED863DBD34E0879E4A21F5E38AE3D89559C57E6BE990A9B`
SSDEEP | `768:4BbSoy+SdIBf0k2dsjYg6Iq8S1GYqWH8BR:noOIBf0ddsjY/ZGyc7`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `4FB62C3E5D8C0DE365BC6580A84DA17568B1A18A`
PE256 | `7E9CDAB4247511B6F2B3B360D0F2677688955F3093092F99659FD13EB371D4DD`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Services Installation Utility Version 4.8.4084.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Invalid option: '--help'

USAGE: regsvcs.exe [options] AssemblyName
Options:
    /? or /help     Display this usage message.
    /fc             Find or create target application (default).
    /c              Create target application, error if it already exists.
    /exapp          Expect an existing application.
    /tlb:<tlbfile>  Filename for the exported type library.
    /appname:<name> Use the specified name for the target application.
    /parname:<name> Use the specified name or id for the target partition.
    /extlb          Use an existing type library.
    /reconfig       Reconfigure existing target application (default).
    /noreconfig     Don't reconfigure existing target application.
    /u              Uninstall target application.
    /nologo         Suppress logo output.
    /quiet          Suppress logo output and success output.
    /componly       Configure components only, no methods or interfaces.
    /appdir:<path>  Set application root directory to specified path.


```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegSvcs.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RegSvcs.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/2c1eeb7097023c784c2bd040a2005a5070ed6f3a4abf13929377a9e39fab1390/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\RegSvcs.exe](RegSvcs.exe-DC67ADE51149EC0C373A379473895BA1.md) | 74

## Possible Misuse

*The following table contains possible examples of `RegSvcs.exe` being misused. While `RegSvcs.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\regsvcs.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\regsvcs.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Link: https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `Name: Regsvcs.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `Description: Regsvcs and Regasm are Windows command-line utilities that are used to register .NET Component Object Model (COM) assemblies` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `- Command: regsvcs.exe AllTheThingsx64.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `- Path: C:\Windows\System32\regsvcs.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `- Path: C:\Windows\SysWOW64\regsvcs.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `- Link: https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.009 Regsvcs/Regasm](../../T1218.009/T1218.009.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Regsvcs Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.009 Regsvcs/Regasm](../../T1218.009/T1218.009.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Regsvcs Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \|  \|  \| [Regsvcs/Regasm](../../T1218.009/T1218.009.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \|  \|  \| [Regsvcs/Regasm](../../T1218.009/T1218.009.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | # T1218.009 - Regsvcs/Regasm | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | <blockquote>Adversaries may abuse Regsvcs and Regasm to proxy execution of code through a trusted Windows utility. Regsvcs and Regasm are Windows command-line utilities that are used to register .NET [Component Object Model](https://attack.mitre.org/techniques/T1559/001) (COM) assemblies. Both are digitally signed by Microsoft. (Citation: MSDN Regsvcs) (Citation: MSDN Regasm) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | Both utilities may be used to bypass application control through use of attributes within the binary to specify code that should be run before registration or unregistration: <code>[ComRegisterFunction]</code> or <code>[ComUnregisterFunction]</code> respectively. The code with the registration and unregistration attributes will be executed even if the process is run under insufficient privileges and fails to execute. (Citation: LOLBAS Regsvcs)(Citation: LOLBAS Regasm)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | - [Atomic Test #2 - Regsvcs Uninstall Method Call Test](#atomic-test-2---regsvcs-uninstall-method-call-test) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | ## Atomic Test #2 - Regsvcs Uninstall Method Call Test | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\regsvcs.exe #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


