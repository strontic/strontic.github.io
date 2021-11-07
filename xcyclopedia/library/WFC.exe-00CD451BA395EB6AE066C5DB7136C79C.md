---
title: WFC.exe | Microsoft Windows Workflow Foundation Compiler
excerpt: What is WFC.exe?
---

# WFC.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\WFC.exe`
* Description: Microsoft Windows Workflow Foundation Compiler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `00CD451BA395EB6AE066C5DB7136C79C`
SHA1 | `34AAE15BCF61D46A7170F3700015BD3DF01E53A2`
SHA256 | `8B66EF24A75AEFD4392210B3F340FDE5D3506EBC4BA1484E4E91E44570B85BFC`
SHA384 | `FE743C3E66C1B250043C0147FEFFAB930D5FAA0A26BA40396F7377678BE733F7F99C246DA057524297621887FE9DD13A`
SHA512 | `9C20B269663A3114EA5249AB455ADF77288A2142E937969E7B79B49AECDAA62496BB1461ED311EC501BD2CB8A02C8FAEB7D510CAC963ED73DD3B8845AC8B19E0`
SSDEEP | `1536:JFnVMMEogd8/Iz12L1LMDukPx6y0+uumbmqmKZ4N:JFnVbEbd8/Iz12xLMDukcy0+uu6m4Z4N`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `58E5F334FB46F7B0E0864ED1F2D5C9E24847F6C5`
PE256 | `D78D6B51C9C9A8BFF00056C0DCBDB3EE4B62BCE96733D2BF2851FC6E63E1233C`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Windows Workflow Compiler version 4.8.4084.0
Copyright (C) Microsoft Corporation. All rights reserved.


                 Windows Workflow Compiler Options

wfc.exe <Xoml file list> /target:assembly [<vb/cs file list>] [/language:...]
        [/out:...] [/reference:...] [/library:...] [/debug...] [/nocode...]
        [/checktypes...] [/resource:<resource info>]

                        - OUTPUT FILE -
/out:<file>                 Output file name
/target:assembly            Build a Windows Workflow assembly (default).
                            Short form: /t:assembly
/target:exe		    Build a Windows Workflow application.
                            Short form: /t:exe
/delaysign[+|-]             Delay-sign the assembly using only the public portion
                            of the strong name key.
/keyfile:<file>             Specifies a strong name key file.
/keycontainer:<string>      Specifies a strong name key container.

                        - INPUT FILES -
<Xoml file list>            Xoml source file name(s).
<vb/cs file list>           Code-beside file name(s).
/reference:<file list>      Reference metadata from the specified assembly file(s).
                            Short form is '/r:'.
/library:<path list>        Set of directories where to lookup for the references.
                            Short form is '/lib:'.
/resource:<resinfo>         Embed the specified resource. Short form is '/res:'.
                            resinfo format is <file>[,<name>[,public|private]].

Rules and freeform layout files must be embedded as assembly resources.
The resource name is constructed by using the namespace and type name
of the activity. For example, an activity named "MyActivity" in namespace
"WFProject" would require resource names "WFProject.MyActivity.rules"
and/or "WFProject.MyActivity.layout".

                        - CODE GENERATION -
/debug[+|-]                 Emit full debugging information. The default is '+'.
/nocode[+|-]                Disallow code-beside model.
                            The default is '-'. Short form is '/nc:'.
/checktypes[+|-]            Check for permitted types in wfc.exe.config file.
                            The default is '-'. Short form is '/ct:'.

                        - LANGUAGE -
/language:[cs|vb]           The language to use for the generated class.
                            The default is 'CS' (C#). Short form is '/l:'.
/rootnamespace:<string>     Specifies the root Namespace for all type declarations.
                            Valid only for 'VB' (Visual Basic) language.
                            Short form is '/rns:'.

                        - MISCELLANEOUS -
/help                       Display this usage message. Short form is '/?'.
/nologo                     Suppress compiler copyright message. Short form is '/n'.
/nowarn                     Ignore compiler warnings. Short form is '/w'.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\WFC.exe |
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

* Original Filename: wfc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8b66ef24a75aefd4392210b3f340fde5d3506ebc4ba1484e4e91e44570b85bfc/detection


## Possible Misuse

*The following table contains possible examples of `WFC.exe` being misused. While `WFC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wfc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wfc.yml) | `Name: Wfc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wfc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wfc.yml) | `- Command: wfc.exe c:\path\to\test.xoml`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wfc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wfc.yml) | `- Path: C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\wfc.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


