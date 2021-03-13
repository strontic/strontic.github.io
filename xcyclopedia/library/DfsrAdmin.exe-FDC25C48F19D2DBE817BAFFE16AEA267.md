---
title: DfsrAdmin.exe | DFS Replication Command Line
excerpt: What is DfsrAdmin.exe?
---

# DfsrAdmin.exe 

* File Path: `C:\Windows\DfsrAdmin.exe`
* Description: DFS Replication Command Line

## Hashes

Type | Hash
-- | --
MD5 | `FDC25C48F19D2DBE817BAFFE16AEA267`
SHA1 | `6EB31915C6BA671C1C92247E6AA7B0B4A2D92581`
SHA256 | `8AE6BDA2A754ADDD2F6F363F3597209DB39A75FE8461ED0B482DB33874C8D78F`
SHA384 | `8662A68BEC653EEF084D4AB8734D49ED6CE9E780506834A67D4DDB0E16FD6A4D70EBBF59923853F996D3C366A77E3CB2`
SHA512 | `AD88372CB73B533F960E9867E8873109C7EB20D55EAB280B851D00671CC39587DED388F22D236BDF5C37CD6D2D39339961BDB45A88AEE2FFED64150897CD560F`
SSDEEP | `3072:mDmwOBqkFplW0QBgXnCBfzBdYPZ23VDTGNpSVwICI+b:qvXkFpsxCgdYPZ23VDwICI`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `FAB3F6265A0CFF8D07475EC8C47891976B02FC25`
PE256 | `8572A6BF39C0E0B707120FA6E346BFC66A4A408C262A4AF202143FEA714AF01A`

## Runtime Data

### Usage (stdout):
```cmhg

Help: 
=== Supported Objects ===
You can perform actions on the following objects:


Bulk          Perform several actions by using a single input
              file              
 
Conn          Perform actions on connections between members of a replication 
              group

Health        Generate a health report for one or more members of a 
              replication group
 
Mem           Perform actions on a member of a replication group

Membership    Perform actions related to a member's participation in a 
              replicated folder

PropRep       Generate propagation report for one or more propagation
              test files
              
PropTest      Generate and drop a propagation test file on a membership, 
              used for testing replication

RF            Perform actions on a folder that is replicated between members
              of a replication group
 
RG    	      Perform actions on a group of computers that participates in
              replication

Sub           Perform actions related to a member's subscription in 
              replication groups

Type "DfsrAdmin <Object> /?" for detailed help.

Usage: DfsrAdmin <Object> <Action> [<SubObject>] [<SubAction>]
       </Parameter:Value> ... [</Optional-Parameter:Value> ...]
       [/Domain:<value>] [/DC:<value>] [/CSV] [/Force]

=== Optional Parameters Supported For All Commands ===
/Domain: Specify the domain for the replication group
/DC:     Specify the domain controller to connect to in the replication 
         group's domain
/Force:  Specify that a failed operation is skipped when an action causes a 
         series of operations to be performed

=== Optional Parameter Supported For All List Commands ===
/CSV:    Dumps the list output in CSV format

```

### Usage (stderr):
```cmhg

Failed: 
The object --help is not a valid object.

```

### Loaded Modules:

Path |
-- |
C:\Windows\DfsrAdmin.exe |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DfsrAdmin.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.529
* Product Version: 10.0.17763.529
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/8ae6bda2a754addd2f6f363f3597209db39a75fe8461ed0b482db33874c8d78f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\DfsrAdmin.exe](DfsrAdmin.exe-8B37A70A2E4EACB9D9ECFD21050A5B3B.md) | 69




MIT License. Copyright (c) 2020-2021 Strontic.


