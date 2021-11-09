---
title: jsc.exe | jsc.exe
excerpt: What is jsc.exe?
---

# jsc.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\jsc.exe`
* Description: jsc.exe

## Hashes

Type | Hash
-- | --
MD5 | `94C8E57A80DFCA2482DEDB87B93D4FD9`
SHA1 | `5729E6C7D2F5AB760F0093B9D44F8AC0F876A803`
SHA256 | `39E87F0EDCDD15582CFEFDFAB1975AADD2C7CA1E3A5F07B1146CE3206F401BB5`
SHA384 | `C5A46056673F0C19F547678539B818C6EC50E261B418CBF78DC377649D244C223C700846E43CFD2D21CF43418A498D0F`
SHA512 | `1798A3607B2B94732B52DE51D2748C86F9453343B6D8A417E98E65DDB38E9198CDCB2F45BF60823CB429B312466B28C5103C7588F2C4EF69FA27BFDB4F4C67DC`
SSDEEP | `768:DeSZaMT79n3DwU8ZCM2o1QG/n29WERqqJaqW/P8+4W:DeoaElzEZ2fG/nmkK4s+4W`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `8234926D09B2F79069027A5A37DF2B63FC397B06`
PE256 | `814BBB177F256F4BBEF2E2542176A62E6BA6F07D5138B147762FF4BAB4866779`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) JScript Compiler version 14.00.4084
for Microsoft (R) .NET Framework version 4.0.30319
Copyright (C) Microsoft Corporation. All rights reserved.

jsc [options] <source files> [[options] <source files>...]

                         JScript Compiler Options

                           - OUTPUT FILES -
  /out:<file>              Specify name of binary output file
  /t[arget]:exe            Create a console application (default)
  /t[arget]:winexe         Create a windows application
  /t[arget]:library        Create a library assembly
  /platform:<platform>     Limit which platforms this code can run on; must be x86, Itanium, x64, or any cpu, which is the default

                           - INPUT FILES -
  /autoref[+|-]            Automatically reference assemblies based on imported namespaces and fully-qualified names (on by default)
  /lib:<path>              Specify additional directories to search in for references
  /r[eference]:<file list> Reference metadata from the specified assembly file
                           <file list>: <assembly name>[;<assembly name>...]

                           - RESOURCES -
  /win32res:<file>         Specifies Win32 resource file (.res)
  /res[ource]:<info>       Embeds the specified resource
                           <info>: <filename>[,<name>[,public|private]]
  /linkres[ource]:<info>   Links the specified resource to this assembly
                           <info>: <filename>[,<name>[,public|private]]

                           - CODE GENERATION -
  /debug[+|-]              Emit debugging information
  /fast[+|-]               Disable language features to allow better code generation
  /warnaserror[+|-]        Treat warnings as errors
  /w[arn]:<level>          Set warning level (0-4)

                           - MISCELLANEOUS -
  @<filename>              Read response file for more options
  /?                       Display help
  /help                    Display help
  /d[efine]:<symbols>      Define conditional compilation symbol(s)
  /nologo                  Do not display compiler copyright banner
  /print[+|-]              Provide print() function

                           - ADVANCED -
  /codepage:<id>           Use the specified code page ID to open source files
  /lcid:<id>               Use the specified lcid for messages and default code page
  /nostdlib[+|-]           Do not import standard library (mscorlib.dll) and change autoref default to off
  /utf8output[+|-]         Emit compiler output in UTF-8 character encoding
  /versionsafe[+|-]        Specify default for members not marked 'override' or 'hide'


```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\jsc.exe |
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

* Original Filename: jsc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.8.4084.0 built by: NET48REL1
* Product Version: 14.0.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/39e87f0edcdd15582cfefdfab1975aadd2c7ca1e3a5f07b1146ce3206f401bb5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\jsc.exe](jsc.exe-1B0E9D39693B026B951BBF2A25BA61A0.md) | 74
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\jsc.exe](jsc.exe-1B0E9D39693B026B951BBF2A25BA61A0.md) | 74
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\jsc.exe](jsc.exe-94C8E57A80DFCA2482DEDB87B93D4FD9.md) | 100

## Possible Misuse

*The following table contains possible examples of `jsc.exe` being misused. While `jsc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `Name: Jsc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- Command: jsc.exe scriptfile.js`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `Description: Use jsc.exe to compile javascript code stored in scriptfile.js and output scriptfile.exe.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- Command: jsc.exe /t:library Library.js`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `Description: Use jsc.exe to compile javascript code stored in Library.js and output Library.dll.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\Jsc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\Jsc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v2.0.50727\Jsc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v2.0.50727\Jsc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Jsc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Jsc.yml) | `- IOC: Jsc.exe should normally not run a system unless it is used for development.`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


