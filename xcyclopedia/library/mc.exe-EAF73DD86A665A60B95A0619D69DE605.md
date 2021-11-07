---
title: mc.exe | Windows Message Compiler
excerpt: What is mc.exe?
---

# mc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mc.exe`
* Description: Windows Message Compiler

## Hashes

Type | Hash
-- | --
MD5 | `EAF73DD86A665A60B95A0619D69DE605`
SHA1 | `37581A614CDFE051746FAA7812E05FE5B3D6BCD9`
SHA256 | `7EA8BD997394C33FB04F1466F667A28AE5DF62B8457B43ABF6BE106682D842D5`
SHA384 | `40A2EBF5ECAB3EBA5927C75560A1D254FBCB01C1CD12BC264533E59C93B50254797E796D4AF1DD910D12F8314F5AA184`
SHA512 | `F3DCDEC8F85E6D69C35E6C40737E95BF11F35128292609FEFD40B13EAA69F088FB2BB788DBB857B5195E68496061D9F7429F69DABA79BBB572DCCD36A3DD1DA7`
SSDEEP | `6144:xc+sURibGRGhgTD+B3KWGcf3FVR91mQ7Ee4Pkn8aQ1V2LQDK9gIc3Pbj2JjsAWn4:i+sibiZrGi3191GzhPDDIRjsAEdW`
IMP | `BC25F59ED7CBA8818E85D7E8CA742AEF`
PESHA1 | `B0CACEDFF7ACE004225DC4B7887543D9F192B624`
PE256 | `63675B3C3477365D9086871DEBD62AEA5511078528847A5531BEA60C9D528C49`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mc.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/7ea8bd997394c33fb04f1466f667a28ae5df62b8457b43abf6be106682d842d5/detection


## Possible Misuse

*The following table contains possible examples of `mc.exe` being misused. While `mc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image\|endswith: '\Mc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


