---
title: vbc.exe | Visual Basic Command Line Compiler
excerpt: What is vbc.exe?
---

# vbc.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\vbc.exe`
* Description: Visual Basic Command Line Compiler

## Hashes

Type | Hash
-- | --
MD5 | `A731372E6F6978CE25617AE01B143351`
SHA1 | `EAB9863A3B7FE5BA2C916A5115C4F13D0984FF89`
SHA256 | `19A3CFBC90E877DF30E938FB55785AC3BA8E2E30A54FFBB5AF6E0EC9430F9E4B`
SHA384 | `96434D9E7D03EE395ABB9D4D39CDA7D4E3F9DBD3D9C629E8553CC0CB084F87F754692A894069B20EB4E7AC131589081C`
SHA512 | `4824C046C2B8370DC290FFBEC0C2AA17A4CC22ED2B313E33D72E4AEC5D01AB9E6E9676848752D37D95AAFA9818F35B233BF70E7A84E0FA0106D22C5F07A38B0D`
SSDEEP | `49152:4EF5PsH1IaspqACp//9NqqAJN77F29ZJOx22p:bw16psLqqAJN77F29jOx2O`
IMP | `1460E2E6D7F8ECA4240B7C78FA619D15`
PESHA1 | `E030E501C10B0AA70B406A88204F2BE062CDA8DD`
PE256 | `DD25C9C61C3F2BFBE4FBA5A396979D8E35274D2B63F4885AC64B1137C7828DC7`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Visual Basic Compiler version 14.8.4161
for Visual Basic 2012
Copyright (c) Microsoft Corporation.  All rights reserved.

This compiler is provided as part of the Microsoft (R) .NET Framework, but only supports language versions up to Visual Basic 2012, which is no longer the latest version. For compilers that support newer versions of the Visual Basic programming language, see http://go.microsoft.com/fwlink/?LinkID=533241

                  Visual Basic Compiler Options

                                  - OUTPUT FILE -
/out:<file>                       Specifies the output file name.
/target:exe                       Create a console application (default). (Short form: /t)
/target:winexe                    Create a Windows application.
/target:library                   Create a library assembly.
/target:module                    Create a module that can be added to an assembly.
/target:appcontainerexe           Create a Windows application that runs in AppContainer.
/target:winmdobj                  Create a Windows Metadata intermediate file
/doc[+|-]                         Generates XML documentation file.
/doc:<file>                       Generates XML documentation file to <file>.

                                  - INPUT FILES -
/addmodule:<file_list>            Reference metadata from the specified modules.
/link:<file_list>                 Embed metadata from the specified interop assembly. (Short form: /l)
/recurse:<wildcard>               Include all files in the current directory and subdirectories according to the wildcard specifications.
/reference:<file_list>            Reference metadata from the specified assembly. (Short form: /r)

                                  - RESOURCES -
/linkresource:<resinfo>           Links the specified file as an external assembly resource. resinfo:<file>[,<name>[,public|private]] (Short form: /linkres)
/nowin32manifest                  The default manifest should not be embedded in the manifest section of the output PE.
/resource:<resinfo>               Adds the specified file as an embedded assembly resource. resinfo:<file>[,<name>[,public|private]] (Short form: /res)
/win32icon:<file>                 Specifies a Win32 icon file (.ico) for the default Win32 resources.
/win32manifest:<file>             The provided file is embedded in the manifest section of the output PE.
/win32resource:<file>             Specifies a Win32 resource file (.res).

                                  - CODE GENERATION -
/optimize[+|-]                    Enable optimizations.
/removeintchecks[+|-]             Remove integer checks. Default off.
/debug[+|-]                       Emit debugging information.
/debug:full                       Emit full debugging information (default).
/debug:pdbonly                    Emit PDB file only.

                                  - ERRORS AND WARNINGS -
/nowarn                           Disable all warnings.
/nowarn:<number_list>             Disable a list of individual warnings.
/warnaserror[+|-]                 Treat all warnings as errors.
/warnaserror[+|-]:<number_list>   Treat a list of warnings as errors.

                                  - LANGUAGE -
/define:<symbol_list>             Declare global conditional compilation symbol(s). symbol_list:name=value,... (Short form: /d)
/imports:<import_list>            Declare global Imports for namespaces in referenced metadata files. import_list:namespace,...
/langversion:<number>             Specify language version: 9|10|11.
/optionexplicit[+|-]              Require explicit declaration of variables.
/optioninfer[+|-]                 Allow type inference of variables.
/rootnamespace:<string>           Specifies the root Namespace for all type declarations.
/optionstrict[+|-]                Enforce strict language semantics.
/optionstrict:custom              Warn when strict language semantics are not respected.
/optioncompare:binary             Specifies binary-style string comparisons. This is the default.
/optioncompare:text               Specifies text-style string comparisons.

                                  - MISCELLANEOUS -
/help                             Display this usage message. (Short form: /?)
/noconfig                         Do not auto-include VBC.RSP file.
/nologo                           Do not display compiler copyright banner.
/quiet                            Quiet output mode.
/verbose                          Display verbose messages.

                                  - ADVANCED -
/baseaddress:<number>             The base address for a library or module (hex).
/bugreport:<file>                 Create bug report file.
/codepage:<number>                Specifies the codepage to use when opening source files.
/delaysign[+|-]                   Delay-sign the assembly using only the public portion of the strong name key.
/errorreport:<string>             Specifies how to handle internal compiler errors; must be prompt, send, none, or queue (default).
/filealign:<number>               Specify the alignment used for output file sections.
/highentropyva[+|-]               Enable high-entropy ASLR.
/keycontainer:<string>            Specifies a strong name key container.
/keyfile:<file>                   Specifies a strong name key file.
/libpath:<path_list>              List of directories to search for metadata references. (Semi-colon delimited.)
/main:<class>                     Specifies the Class or Module that contains Sub Main. It can also be a Class that inherits from System.Windows.Forms.Form. (Short form: /m)
/moduleassemblyname:<string>      Name of the assembly which this module will be a part of.
/netcf                            Target the .NET Compact Framework.
/nostdlib                         Do not reference standard libraries (system.dll and VBC.RSP file).
/platform:<string>                Limit which platforms this code can run on; must be x86, x64, Itanium, arm, AnyCPU32BitPreferred or anycpu (default).
/sdkpath:<path>                   Location of the .NET Framework SDK directory (mscorlib.dll).
/subsystemversion:<version>       Specify subsystem version of the output PE. version:<number>[.<number>]
/utf8output[+|-]                  Emit compiler output in UTF8 character encoding.
@<file>                           Insert command-line settings from a text file.
/vbruntime[+|-|*]                 Compile with/without the default Visual Basic runtime.
/vbruntime:<file>                 Compile with the alternate Visual Basic runtime in <file>.


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\vbc.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vbc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.8.4161.0
* Product Version: 14.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/19a3cfbc90e877df30e938fb55785ac3ba8e2e30a54ffbb5af6e0ec9430f9e4b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\vbc.exe](vbc.exe-0A7608DB01CAE07792CEA95E792AA866.md) | 93

## Possible Misuse

*The following table contains possible examples of `vbc.exe` being misused. While `vbc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_visual_basic_compiler.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_visual_basic_compiler.yml) | `ParentImage\|endswith: '\vbc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Microsoft.Workflow.Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Microsoft.Workflow.Compiler.yml) | `- IOC: The presence of csc.exe or vbc.exe as child processes of Microsoft.Workflow.Compiler.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `Name: vbc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `- Command: vbc.exe /target:exe c:\temp\vbs\run.vb`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\vbc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v3.5\vbc.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


