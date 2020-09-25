---
title: PsInfo.exe | Local and remote system information viewer
excerpt: What is PsInfo.exe?
---

# PsInfo.exe 

* File Path: `C:\SysinternalsSuite\PsInfo.exe`
* Description: Local and remote system information viewer

## Hashes

Type | Hash
-- | --
MD5 | `624ADB0F45CBB9CADAD83C264DF98891`
SHA1 | `E839CE1E0446D8DA889935F411F0FB7AD54D4B3E`
SHA256 | `8F401DC021E20FF3ABC64A2D346EF6A792A5643CA04FFD1F297E417532ACAA06`
SHA384 | `0FA2DEE3BDB319D0D4DCF0652A5FCCA747EC509692A1A7F62C1E0AEB6AAFFBFB9DA23960CF7E64C8E12FB4CAE618D038`
SHA512 | `B29B3A72CD32EE34EC6CE357818658B8A89C399E2F8439A7F49FB1A506ED912F41AFA19BC5C142C9A4539ACC5966A29C6A6637C23DE0DC3E5F2D85264620BDBA`
SSDEEP | `3072:wGicIgBsA+8vctYpleMKZUFEd0iVcxWHYGsDJXU+l9koZUFvEjqcVtb5BR+pEz2D:rl0eXEdB4FdjSvYqWdM4hM`
IMP | `4F91D3B940BE88C33827931A94B9BB0F`
PESHA1 | `5BC0B0EBAAC518C54ECB3386CA99BC831666EC00`
PE256 | `8EF807FBC626DCBECAC7A77BE8FE09646D83A0EA3492DEB2464E739237F627D6`

## Runtime Data

### Usage (stdout):
```cmhg

PsInfo v1.78 - Local and remote system information viewer
Copyright (C) 2001-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

PsInfo returns information about a local or remote Windows NT/2000/XP system.

Usage: psinfo [-h] [-s] [-d] [-c [-t delimiter]] [filter] [\\computer[,computer[,..]]|@file [-u Username [-p Password]]]
     -u        Specifies optional user name for login to
               remote computer.
     -p        Specifies password for user name.
     -h        Show installed hotfixes.
     -s        Show installed software.
     -d        Show disk volume information.
     -c        Print in CSV format
     -t        The default delimiter for the -c option is a comma,
               but can be overriden with the specified character. Use
               "\t" to specify tab.
     filter    Psinfo will only show data for the field matching the filter.
               e.g. "psinfo service" lists only the service pack field.
     computer  Direct PsInfo to perform the command on the remote
               computer or computers specified. If you omit the computer
               name PsInfo runs the command on the local system, 
               and if you specify a wildcard (\\*), PsInfo runs the
               command on all computers in the current domain.
     @file     PsInfo will run against the computers listed in the file
               specified.
     -nobanner Do not display the startup banner and copyright message.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\PsInfo.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Psinfo.exe
* Product Name: Sysinternals PsInfo
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.78
* Product Version: 1.78
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/8f401dc021e20ff3abc64a2d346ef6a792a5643ca04ffd1f297e417532acaa06/detection/





MIT License. Copyright (c) 2020 Strontic.


