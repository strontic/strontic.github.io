---
title: dbh.exe | Microsoft Dbghelp API Example
excerpt: What is dbh.exe?
---

# dbh.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbh.exe`
* Description: Microsoft Dbghelp API Example

## Hashes

Type | Hash
-- | --
MD5 | `906FDD0B925293C493F59B8DDF1A47B7`
SHA1 | `7C8920348924F328A0584A8DE41A87BB9808607F`
SHA256 | `F18B39801BABDAE4C7508AE2303AACD44AF1DB36F11F4C0B719953B25C26CB83`
SHA384 | `E4A9FB4D206CBE74D7E8A666C2564B187024514A2F78E405ACB5F8AB688F51D2DD63192D3CE7A05269652FCAE5C3B07A`
SHA512 | `1DC317E7DBD59AA4116DCDE52EB9C05090514005D96F4ECBF98D71BA272F7C387312331BDF1C88C64768543276411182484CBE473AB9F2480636951A300140FE`
SSDEEP | `3072:VGG3awLETEZXFei81Qa3pIsg/1eiQGg8toYKsa9qeZFdXsF9XXG0/OVuwD:XsTb3pg9ltrKsqquFdXIxdmVx`
IMP | `E75B4391949C151C9B49088F94EF90E6`
PESHA1 | `FA0F859233D821A64AFDD0C2B27D779C843A7846`
PE256 | `7AC200CD5E91459FC14D3F4C8CFBC76DECF317B016F28525570C59A5FC071B31`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbh.exe |
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

* Original Filename: dbh.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\dbh.exe](dbh.exe-4AEEF0F666168340E15B252ECA837FD7.md) | 36




MIT License. Copyright (c) 2020-2021 Strontic.


