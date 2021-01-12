---
title: symstore.exe | Symbol Server Builder
excerpt: What is symstore.exe?
---

# symstore.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\symstore.exe`
* Description: Symbol Server Builder

## Hashes

Type | Hash
-- | --
MD5 | `1903CF11FA6A75A375DEF2972A62B0E4`
SHA1 | `086FE1303ADD5EE2BEE80A54B035F0F28029C769`
SHA256 | `ED986351C69C556416A950744C2209C136812F3CBB376A1FBF15FE11607C39C4`
SHA384 | `A26DB11597031580658379806B92F46C211EC9A67ADD9201CA6E1C4BE724F2EFA5B1378FDB13C05775940D7597900C1B`
SHA512 | `438B4CFDE559697ED9C2DEF809E11BFF8FE899755992050429833297AC72282A8B974BE152985CC1C8AF69560F5C42A5CA4C558B733F218167C7E667C753D750`
SSDEEP | `1536:lsJtYgBwZX/Eu6tZsbLFxDB9PL6DhL2b5c3exo06nOv8i37:latYg6Z0jsVh3tbyexZ6ni53`
IMP | `A93EF732C8E3E2DEB456943D297AEADA`
PESHA1 | `74D33C8CF04E65C5EC9384615D2A711C10EC2CDA`
PE256 | `93A1A5E448C715F363611E72DCEE56473C17E826748B98E4A270E1BD0609CA34`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
symstore add [/r] [/p] [/l] /f File /s Store /t Product [/v Version]
             [/c Comment] [/d LogFile] [/compress]
symstore add [/r] [/p] [/l] [/q] /g Share /f File /x IndexFile [/a] [/d LogFile]
symstore add /y IndexFile /g Share /s Store [/p] /t Product [/v Version]
             [/c Comment] [/d LogFile] [/compress]
symstore del /i ID /s Store [/d LogFile]
symstore query [/r] [/o] /f File /s Store

    add             Add files to server or create an index file.
    del             Delete a transaction from the server.
    query           Check if file(s) are indexed on the server.

    /3              Create index2.txt when populating a new symbol server.
    /f File         Network path of files or directories to add.
                    If the named file begins with an '@' symbol, it is treated
                    as a response file which is expected to contain a list of
                    files (path and filename, 1 entry per line) to be stored.
    /g Share        This is the server and share where the symbol files were
                    originally stored.  When used with /f, Share should be
                    identical to the beginning of the File specifier.  When
                    used with the /y, Share should be the location of the
                    original symbol files, not the index file.  This allows
                    you to later change this portion of the file path in case
                    you move the symbol files to a different server and share.
    /i ID           Transaction ID string.
    /l              Allows the file to be in a local directory rather than a
                    network path.(This option is only used with the /p option.)
    /p              Causes SymStore to store a pointer to the file, rather than
                    the file itself.
    /q              Don't quote fields in the index file.
    /r              Add files or directories recursively.
    /s Store        Root directory for the symbol store.
    /t Product      Name of the product.
    /v Version      Version of the product.
    /c Comment      Comment for the transaction.
    /d LogFile      Send output to LogFile instead of standard output.
    /x IndexFile    Causes SymStore not to store the actual symbol files in the
                    symbol store.  Instead, information is stored which will
                    allow the files to be added later.
    /y IndexFile    This reads the data from a file created with /x.
    /yi IndexFile   Append a comment with the transaction ID to the end of the
                    index file.
    /z pub | pri    Pub option will only index symbols that have had the full
                    source information stripped.  Pri will only index symbols
                    that contain the full source information.  Both options
                    will index binaries.
    /m <prefix>     Give preference to files which have <prefix> at the beginning
                    of their path when storing/updating pointers.
    /h pub | pri    Give priority to pub or pri.
    /a              Causes SymStore to append new indexing information
                    to an existing index file. (This option is only used with
                    /x option.)
    /o              Give verbose output.
    -:MSG [msg]     When storing pointers, also add the provided message to the
                    file.ptr
    -:REL           Allow file.ptr paths to be relative.  Implies '/l' also.
    -:NOREFS        Only valid during intial store creation or when used on a
                    store previously created with the -:NOREFS option. Omits the
                    creation of refs.ptr files for files and pointers stored.
                    Use of a store without refs.ptr precludes the ability to do
                    prioritization and the ability to delete transactions from the
                    store.
    -:NOFORCECOPY
    /compress       When storing files, store compressed files on the server. Ignored
                    when storing pointers.


```

### Child Processes:
csrss.exe wininit.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\symstore.exe |
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

* Original Filename: SYMSTORE.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/ed986351c69c556416a950744c2209c136812f3cbb376a1fbf15fe11607c39c4/detection





MIT License. Copyright (c) 2020 Strontic.


