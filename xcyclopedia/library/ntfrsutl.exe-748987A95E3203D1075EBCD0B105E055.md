---
title: ntfrsutl.exe | Utility to dump dynamic state of File Replication Service.
excerpt: What is ntfrsutl.exe?
---

# ntfrsutl.exe 

* File Path: `C:\Windows\system32\ntfrsutl.exe`
* Description: Utility to dump dynamic state of File Replication Service.

## Hashes

Type | Hash
-- | --
MD5 | `748987A95E3203D1075EBCD0B105E055`
SHA1 | `9C448FE1E5A9A6EE0011275C3F790C17EE3FDD66`
SHA256 | `D81D35C974EC1ACA1B1ECC2741D3BA2090BBE9EF8A6FE18A6AEAD643C66E5F34`
SHA384 | `0AFAAAE96454736E5A9CBEB6A6E9402668E03A40CC4C4411672184B0EBA6A248F750457C09BF17A776C5F84004C79365`
SHA512 | `DCA16739A07FA80799E64EC35393F863547B0CB9B6E1DBB8CA35F23947F30A58FFEB5929DD56F6C93AF58ADA39674894CD911171EA1201D76EE1342D58822660`
SSDEEP | `384:QQBZ6O+VOF5Bodhlqaaels5P4VOeOaRqr6RfUcsLWgNW:QQvzwOF5a/qahOpaRTRfUbX`

## Runtime Data

### Usage (stdout):
```cmhg
Ntfrsutl dumps the internal tables, thread and memory information
for the ntfrs service.It runs against local as well as remote server.

Note : To access the internal information, the logged in user should
       have the required access on the following registry keys on the
       target server.

       HKLM\System\CCS\Services\Ntfrs\Parameters\Access Checks\
            Get Internal Information : Full control
            Get Ds Polling Interval  : Read
            Set Ds Polling Interval  : Full Control

ntfrsutl [idtable | configtable | inlog | outlog] [computer]
	          = enumerate the service's idtable/configtable/inlog/outlog 
	computer  = talk to the NtFrs service on this machine.

ntfrsutl [memory|threads|stage] [computer]
	          = list the service's memory usage
	computer  = talk to the NtFrs service on this machine.

ntfrsutl ds [computer]
	          = list the service's view of the DS
	computer  = talk to the NtFrs service on this machine.

ntfrsutl sets [computer]
	          = list the active replica sets
	computer  = talk to the NtFrs service on this machine.

ntfrsutl version [computer]
	          = list the api and service versions
	computer  = talk to the NtFrs service on this machine.

ntfrsutl forcerepl [computer] /r SetName /p DnsName
	          = Force FRS to start a replication cycle ignoring the schedule.
	          = Specify the SetName and DnsName.
	computer  = talk to the NtFrs service on this machine.
	SetName   = Name of the replica set.
	DnsName   = DNS name of the inbound partner to force repl from.

ntfrsutl poll [/quickly[=[N]]] [/slowly[=[N]]] [/now] [computer]
	          = list the current polling intervals.
	now       = Poll now.
	quickly   = Poll quickly until stable configuration retrieved.
	quickly=  = Poll quickly every default minutes.
	quickly=N = Poll quickly every N minutes.
	slowly    = Poll slowly until stable configuration retrieved.
	slowly=   = Poll slowly every default minutes.
	slowly=N  = Poll slowly every N minutes.
	computer  = talk to the NtFrs service on this machine.


```

### Usage (stderr):
```cmhg
Don't understand --help

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\ntfrsutl.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NTFRSUTL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ntfrsutl

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Dumps the internal tables, thread, and memory information for the NT File Replication Service (NTFRS) from both the local and remote servers. The recovery setting for NTFRS in Service Control Manager (SCM) can be critical to locating and keeping important log events on the computer. This tool provides a convenient method of reviewing those settings.

### Syntax

```
ntfrsutl[idtable|configtable|inlog|outlog][<computer>]
ntfrsutl[memory|threads|stage][<computer>]
ntfrsutl ds[<computer>]
ntfrsutl [sets][<computer>]
ntfrsutl [version][<computer>]
ntfrsutl poll[/quickly[=[<n>]]][/slowly[=[<n>]]][/now][<computer>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| idtable | Specifies the ID table. |
| configtable | Specifies the FRS configuration table. |
| inlog | Specifies the inbound log. |
| outlog | Specifies the outbound log. |
| `<computer>` | Specifies the computer. |
| memory | Specifies the memory usage. |
| threads | Specifies the memory usage. |
| stage | Specifies the memory usage. |
| ds | Lists the NTFRS service's view of the DS. |
| sets | Specifies the active replica sets. |
| version | Specifies the API and NTFRS service versions. |
| poll | Specifies the current polling intervals.<ul><li>`/quickly` - Polls quickly until it retrieves a stable configuration.</li><li>`/quickly=` - Polls quickly every default number of minutes.</li><li>`/quickly=<n>` - Polls quickly every *n* minutes.</li><li>`/slowly` - Polls slowly until it retrieves a stable configuration.</li><li>`/slowly=` - Polls slowly every default number of minutes.</li><li>`/slowly=<n>` - Polls slowly every *n* minutes.</li><li>`/now` - Polls now.</li></ul>|
| /? | Displays help at the command prompt. |

#### Examples

To determine the polling interval for file replication, type:

```
C:\Program Files\SupportTools>ntfrsutl poll wrkstn-1
```

To determine the current NTFRS application program interface (API) version, type:

```
C:\Program Files\SupportTools>ntfrsutl version
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


