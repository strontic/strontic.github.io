---
title: csc.exe | Visual C# Command Line Compiler
excerpt: What is csc.exe?
---

# csc.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe`
* Description: Visual C# Command Line Compiler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `F65B029562077B648A6A5F6A1AA76A66`
SHA1 | `528973416456C780051889CA1709510B6BF73370`
SHA256 | `4A6D0864E19C0368A47217C129B075DDDF61A6A262388F9D21045D82F3423ED7`
SHA384 | `D82B3A803450C7171E92B99C9F408D086F08250E012C5E0E612CFAC17BFBF1DD53110067D3BC4B8E191F7D2BBB0522D1`
SHA512 | `5C3B01B025AF8A872EAF6D1F5B98B918E277D1BE328BAD387E09C49687219A2F222C07012E1BCB31C3ED262B7E2256BEEA36F358FBAF6C0159583985AA5AFE69`
SSDEEP | `49152:xMSyAKnixTRPjSI3TyYHTEtlC5nPebVm+PW/I8YfSkLd2OQFNcgc73Ps:7VxT+QoB8YfScnQFNX43Ps`
IMP | `EE1E569AD02AA1F7AECA80AC0601D80D`
PESHA1 | `6AB2E92B2724CBD53886384B9049D52040A221C4`
PE256 | `EEC59E3CFCF63DC6D233406A1447E9FE2B406706E1AA06B6BAEC4B0660896648`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Visual C# Compiler version 4.8.4084.0
for C# 5
Copyright (C) Microsoft Corporation. All rights reserved.

This compiler is provided as part of the Microsoft (R) .NET Framework, but only supports language versions up to C# 5, which is no longer the latest version. For compilers that support newer versions of the C# programming language, see http://go.microsoft.com/fwlink/?LinkID=533240

                        Visual C# Compiler Options

                        - OUTPUT FILES -
/out:<file>                    Specify output file name (default: base name of file with main class or first file)
/target:exe                    Build a console executable (default) (Short form: /t:exe)
/target:winexe                 Build a Windows executable (Short form: /t:winexe)
/target:library                Build a library (Short form: /t:library)
/target:module                 Build a module that can be added to another assembly (Short form: /t:module)
/target:appcontainerexe        Build an Appcontainer executable (Short form: /t:appcontainerexe)
/target:winmdobj               Build a Windows Runtime intermediate file that is consumed by WinMDExp (Short form: /t:winmdobj)
/doc:<file>                    XML Documentation file to generate
/platform:<string>             Limit which platforms this code can run on: x86, Itanium, x64, arm, anycpu32bitpreferred, or anycpu. The default is anycpu.

                        - INPUT FILES -
/recurse:<wildcard>            Include all files in the current directory and subdirectories according to the wildcard specifications
/reference:<alias>=<file>      Reference metadata from the specified assembly file using the given alias (Short form: /r)
/reference:<file list>         Reference metadata from the specified assembly files (Short form: /r)
/addmodule:<file list>         Link the specified modules into this assembly
/link:<file list>              Embed metadata from the specified interop assembly files (Short form: /l)

                        - RESOURCES -
/win32res:<file>               Specify a Win32 resource file (.res)
/win32icon:<file>              Use this icon for the output
/win32manifest:<file>          Specify a Win32 manifest file (.xml)
/nowin32manifest               Do not include the default Win32 manifest
/resource:<resinfo>            Embed the specified resource (Short form: /res)
/linkresource:<resinfo>        Link the specified resource to this assembly (Short form: /linkres)
                               Where the resinfo format is <file>[,<string name>[,public|private]]

                        - CODE GENERATION -
/debug[+|-]                    Emit debugging information
/debug:{full|pdbonly}          Specify debugging type ('full' is default, and enables attaching a debugger to a running program)
/optimize[+|-]                 Enable optimizations (Short form: /o)

                        - ERRORS AND WARNINGS -
/warnaserror[+|-]              Report all warnings as errors
/warnaserror[+|-]:<warn list>  Report specific warnings as errors
/warn:<n>                      Set warning level (0-4) (Short form: /w)
/nowarn:<warn list>            Disable specific warning messages

                        - LANGUAGE -
/checked[+|-]                  Generate overflow checks
/unsafe[+|-]                   Allow 'unsafe' code
/define:<symbol list>          Define conditional compilation symbol(s) (Short form: /d)
/langversion:<string>          Specify language version mode: ISO-1, ISO-2, 3, 4, 5, or Default

                        - SECURITY -
/delaysign[+|-]                Delay-sign the assembly using only the public portion of the strong name key
/keyfile:<file>                Specify a strong name key file
/keycontainer:<string>         Specify a strong name key container
/highentropyva[+|-]            Enable high-entropy ASLR
/enforcecodeintegrity[+|-]     Enforce code intergrity checks on all inputs to the compiler and enable loading compiled assemblies by other programs that enforce code integrity if the operating system is configured to do so.

                        - MISCELLANEOUS -
@<file>                        Read response file for more options
/help                          Display this usage message (Short form: /?)
/nologo                        Suppress compiler copyright message
/noconfig                      Do not auto include CSC.RSP file

                        - ADVANCED -
/baseaddress:<address>         Base address for the library to be built
/bugreport:<file>              Create a 'Bug Report' file
/codepage:<n>                  Specify the codepage to use when opening source files
/utf8output                    Output compiler messages in UTF-8 encoding
/main:<type>                   Specify the type that contains the entry point (ignore all other possible entry points) (Short form: /m)
/fullpaths                     Compiler generates fully qualified paths
/filealign:<n>                 Specify the alignment used for output file sections
/pdb:<file>                    Specify debug information file name (default: output file name with .pdb extension)
/errorendlocation              Output line and column of the end location of each error
/preferreduilang               Specify the preferred output language name.
/nostdlib[+|-]                 Do not reference standard library (mscorlib.dll)
/subsystemversion:<string>     Specify subsystem version of this assembly
/lib:<file list>               Specify additional directories to search in for references
/errorreport:<string>          Specify how to handle internal compiler errors: prompt, send, queue, or none. The default is queue.
/appconfig:<file>              Specify an application configuration file containing assembly binding settings
/moduleassemblyname:<string>   Name of the assembly which this module will be a part of


```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: csc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4a6d0864e19c0368a47217c129b075dddf61a6a262388f9d21045d82f3423ed7/detection/


## Possible Misuse

*The following table contains possible examples of `csc.exe` being misused. While `csc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_8759.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_8759.yml) | `description: Detects Winword starting uncommon sub process csc.exe as used in exploits for CVE-2017-8759` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_8759.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_8759.yml) | `Image: '*\csc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `#- '\csc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc.yml) | `title: Suspicious Parent of Csc.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc.yml) | `description: Detects a suspicious parent of csc.exe, which could by a sign of payload delivery` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc.yml) | `Image: '*\csc.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `title: Suspicious Csc.exe Source File Folder` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `description: Detects a suspicious execution of csc.exe, which uses a source in a suspicious folder (e.g. AppData)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `Image: '*\csc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `Name: Csc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `- Command: csc.exe -out:My.exe File.cs` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `Description: Use CSC.EXE to compile C# code stored in File.cs and output the compiled version to My.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `Description: Use CSC.EXE to compile C# code stored in File.cs and output the compiled version to a dll file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\Csc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\Csc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `- IOC: Csc.exe should normally not run a system unless it is used for development. ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Microsoft.Workflow.Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Microsoft.Workflow.Compiler.yml) | `- IOC: The presence of csc.exe or vbc.exe as child processes of Microsoft.Workflow.Compiler.exe` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`csc.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Compile After Delivery using csc.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Compile After Delivery using csc.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1010/T1010.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe -out:#{output_file_name} #{input_source_code} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | <blockquote>Adversaries may attempt to make payloads difficult to discover and analyze by delivering files to victims as uncompiled code. Text-based source code files may subvert analysis and scrutiny from protections targeting executables/binaries. These payloads will need to be compiled before execution; typically via native utilities such as csc.exe or GCC/MinGW.(Citation: ClearSky MuddyWater Nov 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | - [Atomic Test #1 - Compile After Delivery using csc.exe](#atomic-test-1---compile-after-delivery-using-cscexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | ## Atomic Test #1 - Compile After Delivery using csc.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | Compile C# code using csc.exe binary used by .NET | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe /out:#{output_file} #{input_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /out:"#{output_file}" /target:exe #{source_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /r:System.EnterpriseServices.dll /out:"#{output_file}" /target:library #{source_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /r:System.EnterpriseServices.dll /out:"#{output_file}" /target:library /keyfile:$env:Temp\key.snk #{source_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


