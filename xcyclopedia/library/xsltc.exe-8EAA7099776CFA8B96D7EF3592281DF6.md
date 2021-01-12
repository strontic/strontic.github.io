---
title: xsltc.exe | Microsoft .NET Framework XSLT Compiler
excerpt: What is xsltc.exe?
---

# xsltc.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\xsltc.exe`
* Description: Microsoft .NET Framework XSLT Compiler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `8EAA7099776CFA8B96D7EF3592281DF6`
SHA1 | `667F9FDF7143EFEDA7C8EB7FD13ED47FD09464A5`
SHA256 | `005CF08BAB825948F28FEE8EDD110453CFAEEBF42FF8EFA700B5A8656847EE11`
SHA384 | `78F6816E4C05587F4C1F23805B6E6C7A4746712CD754C5FD4125196A0BB77BF2084B19947451378B9A0E00229625B715`
SHA512 | `825E35E0E6BB01BAF48A759B737BC9EE932066676D4D29E3EE727A253F49AA180682D42BE91A2BE2CF504E122A6D94D0F4A7DE935037E3228A7D508526B124C9`
SSDEEP | `768:9bUWXHRo5QM3r7MP0mG0/zdxSruPy3aG66Iq83jygVg8JS9NNTzkhqWSq8p0:9bZXHR8QMrB90Ld9a/JDUgdNNXkfSHp0`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `486A2AF89CE325D084DD3410B8A988AA35D88C43`
PE256 | `A4A7BE350899624F25A57E6C3FCD525A132CF4822369189EDA80522DCF98A4DA`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) XSLT Compiler version 4.8.4084.0
[Microsoft (R) .NET Framework version 4.8.4300]
Copyright (C) Microsoft Corporation. All rights reserved.

xsltc [options] [/class:<name>] <source file> [[/class:<name>] <source file>...]

                      XSLT Compiler Options

                        - OUTPUT FILES -
/out:<file>             Specify name of binary output file (default: name of the first source file)
/version:<version>      Specify an assembly version
/delaysign[+|-]         Delay-sign the assembly using only the public portion of the strong name key
/keyfile:<file>         Specify a strong name key file
/keycontainer:<string>  Specify a strong name key container
/platform:<string>      Limit which platforms this code can run on: x86, Itanium, x64, or anycpu, which is the default

                        - RESOURCES -
/win32res:<file>        Specify a Win32 resource file (.res)

                        - CODE GENERATION -
/class:<name>           Specify name of the class for compiled stylesheet (short form: /c)
/debug[+|-]             Emit debugging information
/debug:{full|pdbonly}   Specify debugging type ('full' is default and enables attaching a debugger)
/settings:<list>        Specify security settings in the format (dtd|document|script)[+|-],...
                        Dtd enables DTDs in stylesheets, document enables document() function, script enables <msxsl:script> element

                        - MISCELLANEOUS -
@<file>                 Insert command-line settings from a text file
/help                   Display this usage message (short form: /?)
/nologo                 Suppress compiler copyright message

```

### Usage (stderr):
```cmhg

Unhandled Exception: System.IO.FileNotFoundException: Could not load file or assembly 'System.Data.SqlXml, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089' or one of its dependencies. The system cannot find the file specified.
   at Microsoft.Xslt.Compiler.ImproveErrorText(String errorText)
   at Microsoft.Xslt.Compiler.PrintError(ErrorKind errorKind, String errorNumber, String errorText)
   at Microsoft.Xslt.Compiler.Run(String[] args)
   at Microsoft.Xslt.Compiler.Main(String[] args)

```

### Child Processes:
conhost.exe xsltc.exe WerFault.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\mscorlib\v4.0_4.0.0.0__b77a5c561934e089\mscorlib.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Xml\v4.0_4.0.0.0__b77a5c561934e089\System.XML.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System\v4.0_4.0.0.0__b77a5c561934e089\System.dll | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\Users\user | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_6092 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\xsltc.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: xsltc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/005cf08bab825948f28fee8edd110453cfaeebf42ff8efa700b5a8656847ee11/detection





MIT License. Copyright (c) 2020 Strontic.


