---
title: RegAsm.exe | Microsoft .NET Assembly Registration Utility
excerpt: What is RegAsm.exe?
---

# RegAsm.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe`
* Description: Microsoft .NET Assembly Registration Utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `0D5DF43AF2916F47D00C1573797C1A13`
SHA1 | `230AB5559E806574D26B4C20847C368ED55483B0`
SHA256 | `C066AEE7AA3AA83F763EBC5541DAA266ED6C648FBFFCDE0D836A13B221BB2ADC`
SHA384 | `3B4D3715DC2C5CC65579F673250BB355D5B9590ECAB1BE1E2F845090E5482CEC6C05D9DD7167B39FEA785B1850EFA498`
SHA512 | `F96CF9E1890746B12DAF839A6D0F16F062B72C1B8A40439F96583F242980F10F867720232A6FA0F7D4D7AC0A7A6143981A5A130D6417EA98B181447134C7CFE2`
SSDEEP | `768:X8XcJiMjm2ieHlPyCsSuJbn8dBhFwlSMF6Iq8KSYDKbQ22qWqO8w1R:rYMaNylPYSAb8dBnsHsPDKbQBqTY`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `045ADCAA09C5A7BE1AB28595CDEF3EB76103573A`
PE256 | `1D9DF24BC73C37A5CD72E6E4090260B968EBD50C4A74035C02851F46A118B515`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft .NET Framework Assembly Registration Utility version 4.8.4084.0
for Microsoft .NET Framework version 4.8.4084.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Syntax: RegAsm AssemblyName [Options]
Options:
    /unregister          Unregister types
    /tlb[:FileName]      Export the assembly to the specified type library
                         and register it
    /regfile[:FileName]  Generate a reg file with the specified name
                         instead of registering the types. This option
                         cannot be used with the /u or /tlb options
    /codebase            Set the code base in the registry
    /registered          Only refer to already registered type libraries
    /asmpath:Directory   Look for assembly references here
    /nologo              Prevents RegAsm from displaying logo
    /silent              Silent mode. Prevents displaying of success messages
    /verbose             Displays extra information
    /? or /help          Display this usage message

```

### Usage (stderr):
```cmhg
RegAsm : error RA0000 : Failed to load 'C:\Users\user\help' because it is not a valid .NET assembly

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe |
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

* Original Filename: RegAsm.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c066aee7aa3aa83f763ebc5541daa266ed6c648fbffcde0d836a13b221bb2adc/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\RegAsm.exe](RegAsm.exe-A4EB36BAE72C5CB7392F2B85609D4A7E.md) | 83

## Possible Misuse

*The following table contains possible examples of `RegAsm.exe` being misused. While `RegAsm.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/tools/regasm-exe-assembly-registration-tool`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `Image\|endswith: '\regasm.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `CommandLine\|endswith: '\regasm.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\regasm.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `Name: Regasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Command: regasm.exe AllTheThingsx64.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Command: regasm.exe /U AllTheThingsx64.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v2.0.50727\regasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v2.0.50727\regasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\regasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\regasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- IOC: regasm.exe executing dll file`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Link: https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `Description: Regsvcs and Regasm are Windows command-line utilities that are used to register .NET Component Object Model (COM) assemblies`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `- Link: https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.009 Regsvcs/Regasm](../../T1218.009/T1218.009.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Regasm Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.009 Regsvcs/Regasm](../../T1218.009/T1218.009.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Regasm Uninstall Method Call Test [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \|  \|  \| [Regsvcs/Regasm](../../T1218.009/T1218.009.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \|  \|  \| [Regsvcs/Regasm](../../T1218.009/T1218.009.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | # T1218.009 - Regsvcs/Regasm | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | <blockquote>Adversaries may abuse Regsvcs and Regasm to proxy execution of code through a trusted Windows utility. Regsvcs and Regasm are Windows command-line utilities that are used to register .NET [Component Object Model](https://attack.mitre.org/techniques/T1559/001) (COM) assemblies. Both are digitally signed by Microsoft. (Citation: MSDN Regsvcs) (Citation: MSDN Regasm) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | Both utilities may be used to bypass application control through use of attributes within the binary to specify code that should be run before registration or unregistration: <code>[ComRegisterFunction]</code> or <code>[ComUnregisterFunction]</code> respectively. The code with the registration and unregistration attributes will be executed even if the process is run under insufficient privileges and fails to execute. (Citation: LOLBAS Regsvcs)(Citation: LOLBAS Regasm)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | - [Atomic Test #1 - Regasm Uninstall Method Call Test](#atomic-test-1---regasm-uninstall-method-call-test) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | ## Atomic Test #1 - Regasm Uninstall Method Call Test | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\regasm.exe /U #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig_oct17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig_oct17.yar) | $s2 = "C:\\Windows\\Microsoft.NET\\Framework\\v2.0.50727\\RegAsm.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


