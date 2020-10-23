---
title: RegAsm.exe | Microsoft .NET Assembly Registration Utility
excerpt: What is RegAsm.exe?
---

# RegAsm.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\RegAsm.exe`
* Description: Microsoft .NET Assembly Registration Utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `A4EB36BAE72C5CB7392F2B85609D4A7E`
SHA1 | `5C58053A3A18C0226B98A4AC7E7320581300B6C9`
SHA256 | `DC45704BA97D974D157C1C4A27DBA402AFA595EAC2468D8DEF2EE8D0A2EE9A81`
SHA384 | `D01ADC95EF11EDBFD6B1EA1D926A7030A9782B655C641CACE6D5529287D2396E6226DB90DFD0F30FADD9E303A5962668`
SHA512 | `8EBDD20B7C1EE87AA3766D812960B0D8CFA0A6BA6E371F730E589895D202DD540EB475F69940261C1532E90D1030370E9EB5102CADBF6E546F99B350DE79B95A`
SSDEEP | `768:/8XcJiMjm2ieHFYPyCsSuJbn8dBhFwjSMF6Iq8KSYDKvc7qWk81:zYMaNyFYPYSAb8dBnWHsPDKvcN91`
IMP | `n/a`
PESHA1 | `EC1B45DF76B912BCAB4A524A47D2C3EF82EC98B1`
PE256 | `AC8DAEF33BF5CFD6A93FD30A9100A1F89413C0794F31A91F716A8CB4907BAA0D`

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
RegAsm : error RA0000 : Could not load file or assembly 'file:///C:\Windows\help' or one of its dependencies. Access is denied.

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\RegAsm.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/dc45704ba97d974d157c1c4a27dba402afa595eac2468d8def2ee8d0a2ee9a81/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe](RegAsm.exe-0D5DF43AF2916F47D00C1573797C1A13.md) | 83

## Possible Misuse

*The following table contains possible examples of `RegAsm.exe` being misused. While `RegAsm.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\regasm.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `Name: Regasm.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Command: regasm.exe AllTheThingsx64.dll ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Command: regasm.exe /U AllTheThingsx64.dll ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v2.0.50727\regasm.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v2.0.50727\regasm.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\regasm.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\regasm.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- IOC: regasm.exe executing dll file` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regasm.yml) | `- Link: https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `Description: Regsvcs and Regasm are Windows command-line utilities that are used to register .NET Component Object Model (COM) assemblies` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvcs.yml) | `- Link: https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/` | 
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



MIT License. Copyright (c) 2020 Strontic.


