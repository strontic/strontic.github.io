---
title: dfsrdiag.exe | DFS Replication Diagnostics Tool
excerpt: What is dfsrdiag.exe?
---

# dfsrdiag.exe 

* File Path: `C:\Windows\system32\dfsrdiag.exe`
* Description: DFS Replication Diagnostics Tool

## Hashes

Type | Hash
-- | --
MD5 | `F8A3CA53C9A2BDB74B031A11B7ED35E2`
SHA1 | `ABEE7CDADBD67245F7FEEAE67290B83F5460FC65`
SHA256 | `477D379C5C5F3862E6815F741C924BFA24F3A32A0709CF21BFEE45545652FC24`
SHA384 | `674815EF34E984E008186DECABB9DCDF2FA913081F27D84E2417043F24CA1C348BFF56FB0D127835E737C02F8644EB9D`
SHA512 | `95AF37ACFC6744D1E009426FCFB56410022AD276ED66B39A7DC38FADA516A63924F79789D9B76EF0A35EF9C6163135F0BB9AACFBEA99F3DA0C7DF1AEC6B1CDCB`
SSDEEP | `49152:7l5Bt5M1P5YkK0DtaVBJ10lMuEynUiuSJk/rwjR45P6mxkn:PBt5Y/KOz`

## Runtime Data

### Usage (stdout):
```cmhg
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
* File Version: 10.0.14393.2999 (rs1_release_inmarket.190520-1518)
* Product Version: 10.0.14393.2999
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


