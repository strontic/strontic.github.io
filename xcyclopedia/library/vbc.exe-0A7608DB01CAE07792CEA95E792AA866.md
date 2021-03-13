---
title: vbc.exe | Visual Basic Command Line Compiler
excerpt: What is vbc.exe?
---

# vbc.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\vbc.exe`
* Description: Visual Basic Command Line Compiler

## Hashes

Type | Hash
-- | --
MD5 | `0A7608DB01CAE07792CEA95E792AA866`
SHA1 | `71DFF876E4D5EDB6CEA78FEE7AA15845D4950E24`
SHA256 | `C16336AB32195B08C1678220FBE0256FEE865F623E2B32FCFA4D9825FD68977E`
SHA384 | `049291992D3D37046548513A278BCAAA23C0790E2AA35BD29A580C71D79B9AFF9003B995EA82C1FA917848DF11028DD8`
SHA512 | `990A6FA1B8ADB6727B1DCD8931AD84FDCB556533B78F896A71EAE2A7E3AE3222E4B8EFAA4B629CED2841211750E0D8A75DDD546A983C2E586918DD8BA4E0DC42`
SSDEEP | `49152:S6F5PsH1IaspqACp//9NqqAJN77F29ZJOx2uc:jw16psLqqAJN77F29jOx27`
IMP | `1460E2E6D7F8ECA4240B7C78FA619D15`
PESHA1 | `EC37F19EAD9F15E77719725C8D2ECFFBC04FD487`
PE256 | `33FD318B74C56B7653FE068D490047F1FF8FCDBB2CCFDC3F2E029548D54836CC`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Visual Basic Compiler version 14.8.4084
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
C:\Windows\Microsoft.NET\Framework\v4.0.30319\vbc.exe |
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

* Original Filename: vbc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.8.4084.0
* Product Version: 14.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/c16336ab32195b08c1678220fbe0256fee865f623e2b32fcfa4d9825fd68977e/detection


## Possible Misuse

*The following table contains possible examples of `vbc.exe` being misused. While `vbc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Microsoft.Workflow.Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Microsoft.Workflow.Compiler.yml) | `- IOC: The presence of csc.exe or vbc.exe as child processes of Microsoft.Workflow.Compiler.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `Name: vbc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `- Command: vbc.exe /target:exe c:\temp\vbs\run.vb`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\vbc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vbc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Vbc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v3.5\vbc.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


