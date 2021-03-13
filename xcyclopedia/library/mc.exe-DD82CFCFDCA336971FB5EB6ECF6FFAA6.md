---
title: mc.exe | Windows Message Compiler
excerpt: What is mc.exe?
---

# mc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mc.exe`
* Description: Windows Message Compiler

## Hashes

Type | Hash
-- | --
MD5 | `DD82CFCFDCA336971FB5EB6ECF6FFAA6`
SHA1 | `37E9D0CE60FF94243C7A62A57FF1FBD059CED735`
SHA256 | `8F6403F5C28E71D9DB6B0A20EC73048D8642E71C4D13FDF39CDE10C5A6BEA863`
SHA384 | `F683603A8C83F748C4413B9ADA12D5D6C2D023C5A447C249192197C1644D93915EF1C4E1A049A907FB348D6019C2F084`
SHA512 | `5604D1983C15D1039D17AAFE968F9038DBD306D4987908765873B4936E0CF225FAB4E3F40FDE7059F216908A98E0266302ABA014678D30F24C0439A893F90BE6`
SSDEEP | `6144:kWJTsALlsv3YXvfWKc7Iyq8B9xS2IVy9RL3LWPt2wetWmtt6egDM:5TsAPoIyq8B9xS2ay9RLbGvetQegY`
IMP | `92F3573E061FE0EC3B22C9D8DC0080E1`
PESHA1 | `39E75EB29655DF13B9829657BB092C4E56294B02`
PE256 | `3F9DEB7830E0FE3DA0EF6D4BBF9EF5BA4C64293AE8A85622C0FC94C496F68E71`

## Runtime Data

### Usage (stderr):
```cmhg
mc : error : Invalid switch: -.
mc : error :  Missing argument for -h switch.
mc : error :  Missing argument for -e switch.
mc : error : Invalid switch: l.
mc : error :  Missing argument for -p switch.
Microsoft (R) Message Compiler  Version 10.0.19041
Copyright (c) Microsoft Corporation. All rights reserved.

Usage:

MC [-?aAbcdnouUv] [-m <length>] [-h <path>] [-e <extension>] [-r <path>]
   [-x <path>] [-w <file>] [-W <file>] [-z <basename> ] [-cp <encoding>]
   [-km | -um | -generateProjections | -cs <namespace>]
   [-mof] [-p <prefix>] [-P <prefix>]
   [<filename.man>] [<filename.mc>]

   -?               - Displays this message.
   -a               - Indicates that the input .mc file is CP_ACP (default).
                      Ignored if the .mc file has a UTF-8 or UTF-16LE BOM.
   -A               - DEPRECATED. Encode .BIN messages using CP_ACP (ANSI).
   -b               - .BIN filename should have .mc filename included for
                      uniqueness.
   -c               - Sets the Customer bit in all of the message IDs.
   -d               - FACILITY and SEVERITY values should be printed as decimal
                      in header file (default is hexadecimal).
   -e <extension>   - The extension for the C include file (1-3 chars).
   -h <path>        - The path for the C include file. Default is: ".\"
   -m <length>      - Warn if any message exceeds <length> characters.
   -n               - NUL-terminate all message table strings.
   -o               - Generate OLE2 header file (use HRESULT definition instead
                      of status code definition).
   -r <path>        - The directory for the RC include file and the binary
                      message resource files it includes. Default is: ".\"
   -s <path>        - Generate a separate binary resource per provider.
                      Generate summary global resource MCGenResource.BIN.
   -t <path>        - Validate against baseline resource.
   -u               - Indicates that the input .mc file is UTF-16LE. This flag
                      is required when the .mc file is UTF-16LE without a BOM.
                      Ignored if the .mc file has a UTF-8 or UTF-16LE BOM.
   -U               - Encode .BIN messages using UTF-16LE (default).
   -U8              - Encode .BIN messages using UTF8. Resulting message table
                      will only be usable on Windows 20h1 or later.
   -v               - Enables verbose output.
   -W <file>        - The path to a custom winmeta.xml file (rarely needed).
   -w <file>        - The path to a custom eventman.xsd file (rarely needed).
   -x <path>        - The path for the .dbg C include file that maps message
                      IDs to their symbolic names. This option can only be used
                      with a message text file.
   -z <basename>    - The base name of the generated files. Default is the base
                      name of the input file.
   <filename.man>   - The name of the manifest file to compile.
   <filename.mc>    - The name of a message file to compile.

   Code Generation Options
   ----------------------- 
   -cp <encoding>       - Generated text files will use the specified
                          character encoding. Valid encoding names include
                          "ansi" (default), "utf-8", and "utf-16".
                          The UTF encodings will add a byte order mark (BOM).
   -km                  - Generate Kernel Mode logging macros.
   -um                  - Generate User Mode logging macros.
                          Note: unless the -mof parameter is specified, the
                          only difference between -km and -um is that the
                          EventWrite macros generated with -km accept an
                          Activity ID parameter.
   -generateProjections - Generate logging interfaces projectable to
                          JavaScript.
   -generateTemplateProjections
                        - Generate logging interfaces projectable to
                          JavaScript that reduce projection cost.
   -generateTemplateStubs <file>
                        - Override the default template wrapping stubs file
                          from WinRTTemplateProviderStubs.js to <file>.js.
   -cs <namespace>      - Generate C# (managed) logging class based on the
                          .NET 3.5 Eventing class.
   -css <namespace>     - Generate static C# (managed) logging class based on
                          the .NET 3.5 Eventing class.

   -co                  - Generate EventWrite macros that invoke an
                          MCGEN_CALLOUT macro. Not supported (ignored) for C#.
   -mof                 - DEPRECATED. Generate downlevel (XP-compatible)
                          functions and macros for ETW. Generate a MOF file
                          describing the ETW events. The MOF file will be
                          generated in the location specified by the "-h"
                          switch.
   -p <prefix>          - Defines the macro name prefix applied to each
                          generated logging macro. Default is: "EventWrite"
   -P <prefix>          - Specifies text at the start of each event symbol name
                          to remove before forming the macro names.

Notes:

- The 'A' and 'mof' switches are deprecated and will be removed in the future.
- At most one .mc and one .man file can be processed per invocation of mc.exe.
- Generated files have the Archive bit cleared.
- The mofcomp and rc tools do not currently support UTF-8 input. If a UTF-8
  encoding is requested, the MOF and RC files will be generated as UTF-16LE.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mc.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/8f6403f5c28e71d9db6b0a20ec73048d8642e71c4d13fdf39cde10c5a6bea863/detection


## Possible Misuse

*The following table contains possible examples of `mc.exe` being misused. While `mc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\Mc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


