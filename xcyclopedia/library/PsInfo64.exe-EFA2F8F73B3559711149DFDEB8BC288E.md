---
title: PsInfo64.exe | Local and remote system information viewer
excerpt: What is PsInfo64.exe?
---

# PsInfo64.exe 

* File Path: `C:\SysinternalsSuite\PsInfo64.exe`
* Description: Local and remote system information viewer

## Hashes

Type | Hash
-- | --
MD5 | `EFA2F8F73B3559711149DFDEB8BC288E`
SHA1 | `453C70E4B12ECABE860866165AD39DE6361215FD`
SHA256 | `EF5CF80C8448BF0907C634A3251CC348B1D36BB5AD8F31F23B11D12AA7F63BCB`
SHA384 | `65C8A849396B76DE937CC1CE05AE8003C76F618B81F69B3FFABE1F318FEC01CDC4C43626598415F6F68F2E35F78C3D82`
SHA512 | `63F75A3D639A912E2E3966E9D410F8E1C52B75300518BB5083853EF2633C7E109C037EA2B66CED57BD5B319866A14BCD92254CB38AB9EC7B99465B0A8A8F5F3E`
SSDEEP | `6144:0aNJZh5a45XRueuTI52O17cNq7tncFSsTTB8YS6SBjyxgg4Lf4fC:0aFi45z2ancFn/0jlJ`
IMP | `807DBAB54231983BC1DD8E3031EBDF02`
PESHA1 | `692C54C6D34C123831D6AF01E7F6D439B9E2F1FA`
PE256 | `156397FDFCA0ECF355BB435079AA1889965FE942273C5CEC7322760D328BED97`

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

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.488_none_4238de57f6b64d28 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\PsInfo64.exe |
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

* Original Filename: Psinfo.exe
* Product Name: Sysinternals PsInfo
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.78
* Product Version: 1.78
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2016 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/ef5cf80c8448bf0907c634a3251cc348b1d36bb5ad8f31f23b11d12aa7f63bcb/detection/





MIT License. Copyright (c) 2020 Strontic.


