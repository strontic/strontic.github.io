---
title: dbgsrv.exe | Microsoft User-Mode Debugger Process Server
excerpt: What is dbgsrv.exe?
---

# dbgsrv.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgsrv.exe`
* Description: Microsoft User-Mode Debugger Process Server

## Hashes

Type | Hash
-- | --
MD5 | `2D7B08246EE468ECE6B155E9D45277E7`
SHA1 | `11E071B8C75A4E5F0D4509F690292DDE74713873`
SHA256 | `2F6D63D7AD166230CFB4565EFAC54275D263BF0DEE504BAD412DA6013DE1A0EE`
SHA384 | `68FAF13B9F74CE25153519C655200A7C0B3D4847BC17E20D63496BA45AB48ECFF86917F154F9490AF90704B1CDC0CB49`
SHA512 | `B143785981C9399B0852867F209EC2EAE416C06268B751B2CD4C3F5B7A80E81377BB6798CBA3BBFDEAC5EDB0649B533807650A09AD9CECE1EB1042C3653FC750`
SSDEEP | `768:AKwPwV3VS4EmpYQfWTeKsFHh/YOWP5DUdLy+y8Z:nwPuVSrmpATeKihwOS5QwZ8`
IMP | `4EA6300403930A924A2CE2F955CE6984`
PESHA1 | `8F1DB10518C1D6BFC59E05E40EB37F82ED9E55FD`
PE256 | `F7A3E092419F601AD27E93548EB458D2CE21836145800D45B15DB3F16EF2C382`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid Command Line: Usage: dbgsrv -t <transport> [-sifeo <image.ext>] [-x] [-c[s] <args...>] [-pc <args...>]
       transport: tcp | npipe | ssl | spipe | 1394 | com | hyperv 
           for tcp use: port=<socket port #>
           for npipe use: pipe=<name of pipe>
           for 1394 use: channel=<channel #>
           for com use: port=<COM port>,baud=<baud rate>,
                        channel=<channel #>
           for hyperv use: vmid=<vm id GUID>,serviceid=<service id GUID>
           for ssl and spipe see the documentation

Example: dbgsrv -t npipe:pipe=foobar

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgeng.dll |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbghelp.dll |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgmodel.dll |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgsrv.exe |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\XmlLite.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dbgsrv.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/2f6d63d7ad166230cfb4565efac54275d263bf0dee504bad412da6013de1a0ee/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\dbgsrv.exe](dbgsrv.exe-06F490C967134305A0532C135ACE5BD0.md) | 36




MIT License. Copyright (c) 2020 Strontic.


