---
title: DfsrAdmin.exe | DFS Replication Command Line
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
C:\Windows\SYSTEM32\ntdll.dll |


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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\DfsrAdmin.exe](DfsrAdmin.exe-8B37A70A2E4EACB9D9ECFD21050A5B3B.md) | 69




MIT License. Copyright (c) 2020 Strontic.


