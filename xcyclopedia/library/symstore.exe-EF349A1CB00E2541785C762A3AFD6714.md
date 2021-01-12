---
title: symstore.exe | Symbol Server Builder
excerpt: What is symstore.exe?
---

# symstore.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\symstore.exe`
* Description: Symbol Server Builder

## Hashes

Type | Hash
-- | --
MD5 | `EF349A1CB00E2541785C762A3AFD6714`
SHA1 | `F8A445AD634D161AEDA98EC80048C2D02F03CE24`
SHA256 | `F08332D60604F0020682BC613072E9628FA4BF21BC61A73EFF9ECFB5AD683A7E`
SHA384 | `386336B0D75AC8833FEF42E3422658A3CEED488BB28A0BF17EBAB8F6A9EB161630684D2F39803A1A26BE31B3FE888906`
SHA512 | `DCADF11D293491A890A5320D21A3D95429793535E9978309AFDC3840F7F426F7FA5090820022C85C0CCE6E5E91AD93BBC7F4AE829FAECD34DEA28CA76AD5D2BE`
SSDEEP | `1536:wn+u06nuB4+OlSIETjE7bpepwtqNkIK6+bVLI6fvGd65vAtv:k+L6nuBWMjE7bpe1NkIubVLrfO85vAR`
IMP | `872FAEF6567331FE9C59F136B91B548C`
PESHA1 | `DAFD833EF9A0CD77B084FF6FF3202A001EB013EB`
PE256 | `624F0A8DADA356D7536288BAD032C7417B9D2972A14803D712A8624F5FE77EDF`

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

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\symstore.exe |
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

* Original Filename: SYMSTORE.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


