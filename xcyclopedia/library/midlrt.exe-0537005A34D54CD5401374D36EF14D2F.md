---
title: midlrt.exe | Microsoft IDL Compiler
excerpt: What is midlrt.exe?
---

# midlrt.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\midlrt.exe`
* Description: Microsoft IDL Compiler

## Hashes

Type | Hash
-- | --
MD5 | `0537005A34D54CD5401374D36EF14D2F`
SHA1 | `7345E6D979B7C8C5D1945C9B9012903790868B31`
SHA256 | `2AE7E2C93B06C1B80F2C47EEA8BFD27AA722B4F7ED7C0CA5EA91F1609CB7C17A`
SHA384 | `5D420539121F3393EB07348F581BBD9D3902BA20B0CFEE4D21136F8F01CB2E83A93E60C56E40BE1321E4F2B0B1AA236A`
SHA512 | `CBBAD503CD602B1FB3DB32C06F9CA66756D4B898FDBAE7FEB634313EBE2A90C1036A07575C393EA6BFD495B842B72851ACF6EB7A6330F0C4856D66B891F43135`
SSDEEP | `24576:Cf0xJAdVAihTardfXX2QhIXohFCcZDMzvxejXsMqqK7tPrqvHqOxcS0eUK9Vyx4f:Cf4Fistao+cZDM0XpqqtnVyx8wY`
IMP | `08C39DAF4985A0BFDCECF8E6D1D6C69E`
PESHA1 | `E283BF0DDA72A4DFD53417CB93EAE6AF6FF204D1`
PE256 | `69FB755DE5D386CD1C613AF981EA7C3B3AC1FE37524DA312A9E6BF3140EACC4D`

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
/metadata_dir      Specify one or more directories containing platform metadata files
/reference         Specify one or more WinMD files to import

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
/nomd              Suppress generation of metadata file

                               -OUTPUT FILE NAMES-
/cstub filename    Specify client stub file name
/dlldata filename  Specify dlldata file name
/h filename        Specify header file name
/header filename   Specify header file name
/iid filename      Specify interface UUID file name
/proxy filename    Specify proxy file name
/sstub filename    Specify server stub file name
/tlb filename      Specify type library file name
/winmd             Specify output metadata file name 

                               -WINDOWS RUNTIME OPTIONS-
/winrt             Enable Windows Runtime semantics
/ns_prefix         Prepend the 'ABI' namespace to all types
/enum_class        Enable use of the C++ enum class construct
/nomidl            Suppress running MIDL.EXE after processing windows runtime IDL file
/nomd              Suppress generation of metadata while processing windows runtime IDL file
/enable_true_async <true|false> Enable true async feature by default

                               -C COMPILER AND PREPROCESSOR OPTIONS-
/cpp_cmd cmd_line  Specify name of C preprocessor (default: cl.exe)
/cpp_opt options   Specify additional C preprocessor options
/cpp_level level   Specify additional C preprocessor options
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
/protocol dce      Use DCE NDR transfer syntax (default for 32b)
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
Microsoft (R) 32b/64b MIDLRT Compiler Engine Version 10.00.0229  
Copyright (c) Microsoft Corporation. All rights reserved.
midlrt : error MIDL1011 : [msg]argument(s) missing for switch [context]/h
midlrt : error MIDL1000 : [msg]missing source-file name 

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\midlrt.exe |
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

* Original Filename: midlrt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\midlrt.exe](midlrt.exe-49EF1FFAF4A83B881485F0C5CB9E112B.md) | 24




MIT License. Copyright (c) 2020 Strontic.


