---
title: jsc.exe | jsc.exe
excerpt: What is jsc.exe?
---

# jsc.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\jsc.exe`
* Description: jsc.exe

## Hashes

Type | Hash
-- | --
MD5 | `1B0E9D39693B026B951BBF2A25BA61A0`
SHA1 | `9CBF99A8DC23BE60834609663E7A338FC5D093D6`
SHA256 | `FFEC0DE61D7ACCBDA9D57EE5B297FCD4725E971A061DA41AD0C5751C496EF6A4`
SHA384 | `1E61495455F2A56E2C394A6624B8D4471F4D3BB5AA7E9686EEFE785A063CD46BB23517B6A8B74CB3D600E7757BA62863`
SHA512 | `89C453B4C0E183EC62D32C00617B8056D346225A4B0B38681129BE828A34B2F94A20F6344266B6E8F9B2C15D9A244DC9BA049C85D2D126F44984DA5CAF6B5A09`
SSDEEP | `768:TeSZaMT79n3DwU8ZCM2odQG/7s9WERqqGFWyD:TeoaElzEZ2bG/7okJMyD`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `6FFC2473393CF1C34BBC424B5F64469F468A1512`
PE256 | `2AD6C3E963126DF18FC52D7926D49397F95ED9974051844F37F454E4D3063B88`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) JScript Compiler version 14.00.4161
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
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\jsc.exe |
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

* Original Filename: jsc.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.8.4161.0 built by: NET48REL1
* Product Version: 14.0.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/ffec0de61d7accbda9d57ee5b297fcd4725e971a061da41ad0c5751c496ef6a4/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\jsc.exe](jsc.exe-94C8E57A80DFCA2482DEDB87B93D4FD9.md) | 74
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\jsc.exe](jsc.exe-1B0E9D39693B026B951BBF2A25BA61A0.md) | 100
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\jsc.exe](jsc.exe-94C8E57A80DFCA2482DEDB87B93D4FD9.md) | 74

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


