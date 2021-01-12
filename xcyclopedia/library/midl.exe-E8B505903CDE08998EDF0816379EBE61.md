---
title: midl.exe | Microsoft IDL Compiler Driver
excerpt: What is midl.exe?
---

# midl.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\midl.exe`
* Description: Microsoft IDL Compiler Driver

## Hashes

Type | Hash
-- | --
MD5 | `E8B505903CDE08998EDF0816379EBE61`
SHA1 | `5E6D641B6E1CCA66012EA0131BB52A4212084A95`
SHA256 | `32589A45054267E6D53CABFBDE27A0C50110EECD0B34E209857607B3E65DFF07`
SHA384 | `32B4B00EBE2C669159C07BBFB5929203090E462E1057ECD35E6AA634CD9FDC00A5FA55D23008304BB731A0E8137F9A10`
SHA512 | `A97F2A726395DED52940B487BC1717F3F8A7FCE692EB89A7C7069078B7C81AE5D8068797833753821D942F895ACF24C1055F54D78644A7A21E35A57A90C0AB2E`
SSDEEP | `3072:oLATrd1O/60Dg7gYBLyyOHZQJGZpMkY7yQsoz0gj5bzVo4qFYV2p3:/TR1UXXYxHNj5XVo`
IMP | `32314B0749D6E242A4D9B55C6738DAD5`
PESHA1 | `7F9A2142A5BCAB6AB1D10393632486B5ED196B09`
PE256 | `6533EB1A5D3096CB04E7B6100C815EF862F11EC41947045AC7D8EAE80677A87F`

## Runtime Data

### Usage (stdout):
```cmhg
                       -MIDL COMPILER OPTIONS-
                                -MODE-
/ms_ext            Microsoft extensions to the IDL language (default)
/c_ext             Allow Microsoft C extensions in the IDL file (default)
/osf               OSF mode - disables /ms_ext and /c_ext options
/app_config        Allow selected ACF attributes in the IDL file
/mktyplib203       MKTYPLIB Version 2.03 compatiblity mode

                               -INPUT-
/acf filename      Specify the attribute configuration file
/I directory-list  Specify one or more directories for include path
/no_def_idir       Ignore the current and the INCLUDE directories

                       -OUTPUT FILE GENERATION-
/client none       Do not generate client files
/client stub       Generate client stub file only
/out directory     Specify destination directory for output files
/server none       Generate no server files
/server stub       Generate server stub file only
/syntax_check      Check syntax only; do not generate output files
/Zs                Check syntax only; do not generate output files
/oldtlb            Generate old format type libraries
/newtlb            Generate new format type libraries (default)
/notlb             Don't generate the tlb file
/define_guids      Define COM guids in the stub header as well as in dlldata

                         -OUTPUT FILE NAMES-
/cstub filename    Specify client stub file name
/dlldata filename  Specify dlldata file name
/h filename        Specify header file name
/header filename   Specify header file name
/iid filename      Specify interface UUID file name
/proxy filename    Specify proxy file name
/sstub filename    Specify server stub file name
/tlb filename      Specify type library file name

                -C COMPILER AND PREPROCESSOR OPTIONS-
/cpp_cmd cmd_line  Specify name of C preprocessor (default: cl.exe)
/cpp_opt options   Specify additional C preprocessor options
/D name[=def]      Pass #define name, optional value to C preprocessor
/no_cpp            Turn off the C preprocessing option
/nocpp             Turn off the C preprocessing option
/U name            Remove any previous definition (undefine)
/msc_ver <nnnn>    Microsoft C/C++ compiler version
/savePP            Save the preprocessed temporary file(s)

                            -ENVIRONMENT-
/char signed       C compiler default char type is signed
/char unsigned     C compiler default char type is unsigned
/char ascii7       Char values limited to 0-127
/env win32         Target environment is Microsoft Windows 32-bit (NT)
/env ia64          Target environment is Microsoft Windows 64-bit (NT) for IA64
/env x64           Target environment is Microsoft Windows for 64-Bit 
                   Extended Systems
/env arm32         Target environment is Microsoft Windows for 32-bit ARM
                   Systems
/env arm64         Target environment is Microsoft Windows for 64-bit ARM
                   Systems
/lcid              Locale id for international locales
/ms_union          Use Midl 1.0 non-DCE wire layout for non-encapsulated unions
/oldnames          Do not mangle version number into names
/rpcss             Automatically activate rpc_sm_enable_allocate
/use_epv           Generate server side application calls via entry-pt vector
/no_default_epv    Do not generate a default entry-point vector
/prefix client str Add "str" prefix to client-side entry points
/prefix server str Add "str" prefix to server-side manager routines
/prefix switch str Add "str" prefix to switch routine prototypes
/prefix all str    Add "str" prefix to all routines
/win32             Target environment is Microsoft Windows 32-bit (NT)
/ia64              Target environment is Microsoft Windows 64-bit (NT) for IA64
/x64               Target environment is Microsoft Windows for 64-Bit 
                   Extended Systems
/arm32             Target environment is Microsoft Windows for 32-bit ARM
                   Systems
/arm64             Target environment is Microsoft Windows for 64-bit ARM
                   Systems
/protocol dce      Use DCE NDR transfer syntax (default for 32-bit)
/protocol all      Use all supported transfer syntaxes
/protocol ndr64    Use Microsoft extension NDR64 transfer syntax
/target {system}   Set the minimum target system

                     -RUNTIME ERROR CHECKING BY STUBS-
/error all         Turn on all the error checking options, the best flavor
/error none        Turn off all the error checking options
/error allocation  Check for out of memory errors
/error bounds_check   Check size vs transmission length specification
/error enum        Check enum values to be in allowable range
/error ref         Check ref pointers to be non-null
/error stub_data   Emit additional check for server side stub data validity
                      All the /error checking above are replaced by /robust
/robust            Generate additonal information to validate parameters. 
                   Requires Windows 2000 and after (default)
/no_robust         turn off /robust feature. not applicable for 64-bit Windows

                            -OPTIMIZATION-
/align {N}         Designate packing level of structures
/pack {N}          Designate packing level of structures
/Zp {N}            Designate packing level of structures
/no_format_opt     Skip format string reusage optimization
/Oi                Generate fully interpreted stubs, old style
                   -Oicf is usually better
/Oic               Generate fully interpreted stubs for standard interfaces and
                   stubless proxies for object interfaces as of NT 3.51 release
                   using -Oicf instead is usually better
/Oicf              Generate fully interpreted stubs with extensions and stubless
                   proxies for object interfaces as of NT 4.0 release (default)
/Oif               Same as -Oicf
/Os                Generate inline stubs

                           -MISCELLANEOUS-
@response_file     Accept input from a response file
/?                 Display a list of MIDL compiler switches
/confirm           Display options without compiling MIDL source
/help              Display a list of MIDL compiler switches
/nologo            Supress displaying of the banner lines
/o filename        Redirects output from screen to a file
/W{0|1|2|3|4}      Specify warning level 0-4 (default = 1)
/WX                Report warnings at specified /W level as errors
/no_warn           Suppress compiler warning messages

```

### Usage (stderr):
```cmhg
Microsoft (R) 32b/64b MIDL Compiler Version 8.01.0622 
Copyright (c) Microsoft Corporation. All rights reserved.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\midl.exe |
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

* Original Filename: midl.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/32589a45054267e6d53cabfbde27a0c50110eecd0b34e209857607b3e65dff07/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\midl.exe](midl.exe-C91E698C847466BBE55A92A0FE3D4633.md) | 68




MIT License. Copyright (c) 2020 Strontic.


