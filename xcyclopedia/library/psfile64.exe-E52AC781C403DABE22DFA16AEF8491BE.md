---
title: psfile64.exe | Lists files and directories opened remotely
excerpt: What is psfile64.exe?
---

# psfile64.exe 

* File Path: `C:\SysinternalsSuite\psfile64.exe`
* Description: Lists files and directories opened remotely

## Hashes

Type | Hash
-- | --
MD5 | `E52AC781C403DABE22DFA16AEF8491BE`
SHA1 | `9A0FDFB801AB76EEDBBD0E18430AF72556A28D0D`
SHA256 | `033B81744E0BD4219A4D698894B8403BB67B525C96049CBFEF34677D4D6FC85C`
SHA384 | `30DA45B7D5240F9F07B469720C5FFA1FDADCBFF1C1F2EF3D1FE85059E78D8BC34259B0EB18B9C0F8D52234D3CADD3D4A`
SHA512 | `F461BF35685852FE0FB75FDA02F5F34EADF93717DDA78C9620677F91D0F6CB791FAF59C565DE04A7E97445A6CDDEAB4335CD65AC6002B2B0F2A1DAD26E074B8E`
SSDEEP | `3072:Zs4psDEHzFIE3nWTeZc2FNIJiGd3nO5UFzrUewyPsx+SUuYVIMWxEJr:C4psoFIEmTYvzIJiGVjzrSnWMur`
IMP | `012373288A4A55BF933694E80D94BDB7`
PESHA1 | `ABC14215864FE9CD2DEBF80B4AACD5F1D4B6D634`
PE256 | `BB9AF688C15120F97BDB3B0810B307607FED29FC5CE0395A636E4AF88880F99D`

## Runtime Data

### Usage (stdout):
```cmhg

PsFile v1.03 - Lists files and directories opened remotely
Copyright (C) 2001-2016 Mark Russinovich
Sysinternals

PsFile lists or closes files opened remotely.

Usage: C:\SysinternalsSuite\psfile64.exe [\\RemoteComputer [-u Username [-p Password]]] [[Id | path] [-c]]
     -u        Specifies optional user name for login to
               remote computer.
     -p        Specifies password for user name.
     Id        Id of file to print information for or close.
     Path      Full or partial path of files to match.
     -c        Closes file identified by file Id.
     -nobanner Do not display the startup banner and copyright message.
Omitting a file identifier has PsFile list all files opened remotely.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\psfile64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psfile.exe
* Product Name: Sysinternals PsFile
* Company Name: Sysinternals
* File Version: 1.03
* Product Version: 1.03
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2016 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/033b81744e0bd4219a4d698894b8403bb67b525c96049cbfef34677d4d6fc85c/detection/





MIT License. Copyright (c) 2020 Strontic.


