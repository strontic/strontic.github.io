---
title: dfsrdiag.exe | DFS Replication Diagnostics Tool
---

# dfsrdiag.exe 

* File Path: `C:\Windows\system32\dfsrdiag.exe`
* Description: DFS Replication Diagnostics Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1B372DB4C30EF438EA4BF06C2794744A`
SHA1 | `8C8FFE4A18CF268C4BDB9918F329BF9B8108F5E0`
SHA256 | `1C5B4D77AC17CE224FDB1354B75ADFBB411A8BDDD2F3FB5174CC5341128BAD1E`
SHA384 | `E11623ED788B7C5DE5EFE4D831E74B11132C982A000B4931E6E6F4618D0A67379D56D0EE22228AE94F008D6990A2B728`
SHA512 | `3B9701FF13DBEDE274833FB81A599E4548B600706DE408849FE0A3DBA54829823CD48773B23602533F42BD1E8C308F1699D770CE7540AFB8744B07A270597360`
SSDEEP | `49152:mEvW2r8faYvZ7OMM0ZHuBVCc4MsuW4O3hm1cxarJ3YK/5TRE5PX:mEvW2r8faYvZ7OMM0RyUIjY`

## Runtime Data

### Usage (stdout):
```Batchfile
[ERROR] Unknown Command <-help>


DFSRDIAG - DFS Replication operational and diagnostics command line utility
  SyncNow           - Forces replication over a given connection; ignore
                      schedule for n minutes
  StopNow           - Stop replication over a given connection; ignore
                      schedule for n minutes
  PollAD            - Trigger a sync with the global information store in
                      Active Directory Domain Services
  DumpAdCfg         - Dump AD configuration settings pertaining to a certain
                      member
  DumpMachineCfg    - Dump service-wide configuration of a given server
                      hosting the DFS Replication service
  StaticRPC         - Set static RPC port for DFS Replication
  Backlog           - Display the backlog of replication data to send from
                      one replication group member to another replication
                      group member
  GUID2NAME         - Translate GUIDs to user friendly names
  PropagationTest   - Test replication progress by dropping a test file under
                      replicated folder
  PropagationReport - Generate a tracking report for the replication progress
                      of the propagation test file
  FileHash          - Displays a hash value identical to that computed by the
                      DFS Replication service for the specified file or
                      folder
  IDRecord          - Displays the contents of a replicated file's ID record
  ReplicationState  - Displays the updates that are currently being
                      transferred on inbound and outbound connections


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dfsrdiag.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.529 (WinBuild.160101.0800)
* Product Version: 10.0.17763.529
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


