---
title: dfscmd.exe | Dfs Command-Line Scripting Application
---

# dfscmd.exe 

* File Path: `C:\Windows\system32\dfscmd.exe`
* Description: Dfs Command-Line Scripting Application

## Hashes

Type | Hash
-- | --
MD5 | `D776A2E73CFD8B3787A3DB84A3020952`
SHA1 | `65FD0693076333E7C49C4971D434B99B61C57335`
SHA256 | `0D39EA5F3DA2348538F57719537BE30EAE1217B2DF318497BA53264EB175F9B5`
SHA384 | `5276C2B92B937DC2729FC4BCCA2B516796D2D10DA652D9F0978535ABF17CB4EE0A8013CA07BEC11E5E7286F43F12347A`
SHA512 | `066702B21D829F3F4BCB782F049A809B611EC145F1580037EB76A410E2B994444B81C8BA6A7ADF3C75213104F45168DB02FD40D91F5F189B11EF6C7C65749BCC`
SSDEEP | `384:TNDKvryYsqXo+YeLvE6nz5awUXOY6q+WbM1kW/:h0G0nLstV6q7M1Z`

## Runtime Data

### Usage (stdout):
```Batchfile
The syntax of this command is:

DFSCMD [options]

DFSCMD configures a Dfs tree.

[options] can be:

/help
        Display this message.
/map \\dfsname\dfsshare\path \\server\share\path [comment] [/restore]
        Create a Dfs volume; map a Dfs path to a server path. With /restore,
        do no checks of destination server.
/unmap \\dfsname\dfsshare\path
        Delete a Dfs volume; remove all its replicas.
/add \\dfsname\dfsshare\path \\server\share\path [/restore]
        Add a replica to a Dfs volume.  With /restore, do no checks of
        destination server.
/remove \\dfsname\dfsshare\path \\server\share\path
        Remove a replica from a Dfs volume.
/view \\dfsname\dfsshare [/partial | /full | /batch || /batchrestore]
        View all the volumes in the Dfs. Without arguments, view just
        the volume names. With /partial, view comment also.  With /full,
        display a list of all the servers for a volume. With /batch,
        output a batch file to recreate the dfs.  With /batchrestore,
        output a batch file to recreate the dfs using the /restore switch.
/move \\dfsname\dfsshare\path1 \\dfsname\dfsshare\path2 [/force]
        Move a folder that is in the Dfs to a different logical path.
        If /force is supplied, replace links that exist if necessary.

Note that paths or comments with spaces should be enclosed in quotes.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\dfscmd.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dfscmd.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


