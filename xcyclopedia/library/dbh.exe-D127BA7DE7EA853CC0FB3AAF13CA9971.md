---
title: dbh.exe | Microsoft Dbghelp API Example
excerpt: What is dbh.exe?
---

# dbh.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbh.exe`
* Description: Microsoft Dbghelp API Example

## Hashes

Type | Hash
-- | --
MD5 | `D127BA7DE7EA853CC0FB3AAF13CA9971`
SHA1 | `91976A6B81BFA594E493A40200F937407745C622`
SHA256 | `DC5ABBEE12193A7172A2660082456C184C5B41AAEB6AB4A11B32EFBC13603628`
SHA384 | `CB441A5C2157514AB8309F7A89D4905EC24B213EFD995E059804E36FAD3D4479615D3022D06A8A717AC8E1AFBA953073`
SHA512 | `1721590655B7418B70342D62A4068B6782E054C70CA78FBCA158CE509C587BB43DE9E6114CF4F561B912449EB7EADC877F5BE21181A23ED626B7A5C95FE2968A`
SSDEEP | `3072:Ivoi9MRxo+pHpvFWUblrbe15Nlca71UmSMfuCDyRwG3KgbED0ZXWelzUMnj:Ko0MRxo+pHpvPb5bKPp71hS0xedD1j`
IMP | `D807241920AE683668495947DA3CEC29`
PESHA1 | `557B61BE8633CCAFAFA2F69D26B3A5FB246AF516`
PE256 | `B758D04D907E1FCB8EEAE6E7587248A3472B1B59E3E7119E866FC9B9BE797055`

## Runtime Data

### Usage (stdout):
```cmhg

          dbh commands :
?                 help : prints this message
q                 quit : quits this program
v     verbose <on/off> : controls debug spew
        load <modname> : loads the requested module
u               unload : unloads the current module
x          enum <mask> : enumerates all matching symbols
n       name <symname> : finds a symbol by it's name
a          addr <addr> : finds a symbol by it's hex address
m      enumaddr <addr> : lists all symbols with a certain hex address
b       base <address> : sets the new default base address
s       next <add/nam> : finds the symbol after the passed sym
p       prev <add/nam> : finds the symbol before the passed sym
l      line <file#num> : finds the matching line number
       laddr <address> : finds a source line by it's corresponding hex address
j             linenext : goes to the next line after the current
k             lineprev : goes to the line previous to the current
srchtree <path> <file> : finds file in path
         ffpath <file> : finds file in symbol path
r           src <mask> : lists source files
+ add <name addr> <sz> : adds symbols with passed name, address, & size
-      del <name/addr> : deletes symbols with passed name or address
z locals <func> <mask> : finds all locals a function
          multi <name> : loads the requested module 1000 times
t          type <name> : lists the type information for the symbol
i                 info : displays information about the loaded module
o           obj <mask> : displays object files in the loaded module
e    elines <src> <obj>: enumerates lines with optional src mask and obj mask
     srch <parameters> : enumerates all symbols - use 'srch ?' for help
                  dtag : displays all the symtag values
          undec <name> : undecorates a given symbol name
 findexe <name> <path> : locates an image in the symbol path
 finddbg <name> <path> : locates an dbg file in the symbol path
        sympath <path> : sets or displays the symbol search path
    dir <fname> <path> : calls EnumDirTree to find filename on path
           index <val> : finds symbol with matching index value
       scope <add/nam> : finds the parent of a symbol
                etypes : enumerates all types
               enummod : enumerates all modules
 sup <pth> <fil> <fil> : finds the symbol server supplement to store
         srvind <file> : finds the symbol server index for store
        srvpath <path> : tests if path is to a symbol store
storeadd <fil> <store> : adds a file to a symbol store
    getsym <img> <sym> : finds the matching symbol for and image
 getfile <name> <idx>> : finds a file based on the symbol server index
srclines <file> <line> : finds matching source lines
            mod <base> : changes default module
               refresh : refreshes the module list
           home <path> : sets the home directory
                  omap : dumps the module omaps
                setret : toggle the return value of enum procs
     symopt <+/-><opt> : sets or displays the current symbol options
    epmod <process id> : enumerate the modules loaded for a given process
                  dump : dumps all function symbols
          uw <address> : gets the unwind info for a function
            fii <file> : dumps the symsrv indexes for a binary and assciated files

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbh.exe |
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

* Original Filename: dbh.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/dc5abbee12193a7172a2660082456c184c5b41aaeb6ab4a11b32efbc13603628/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\dbh.exe](dbh.exe-32312E5171CEE57FE59E611BF0D0D5E6.md) | 32




MIT License. Copyright (c) 2020 Strontic.


