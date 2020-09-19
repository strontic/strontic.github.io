---
title: DfsDiag.exe | DfsDiag - Dfs Diagnostic Utility
---

# DfsDiag.exe 

* File Path: `C:\Windows\system32\DfsDiag.exe`
* Description: DfsDiag - Dfs Diagnostic Utility

## Hashes

Type | Hash
-- | --
MD5 | `9652B9332707B8E233EBCE76F284940B`
SHA1 | `715B1328181740EDB1E23D782A14271A72E75CA9`
SHA256 | `DDA4C99C581C9F499ECE3F8BE3A15889C0723435654132955A58C8131513E3DA`
SHA384 | `1F447BDE2BD2E9676831B31926D221B322CD065BC3249D62EF950899BB29921273C47AA9ED2996CA6B316E7848279D4F`
SHA512 | `3ECA44647EEB3279816C49E4C5CE1BF879F83B738A7EA1C7ADD21EE19485B6A9F04576A2F19EDCFDF175F13EF317CB70B8FA0F930E1E3C4470497B6A75F25CAB`
SSDEEP | `3072:QV/xYtjl964xsjykMZOhxH+6LrSHTl7T70mWf/8gg+42KanD6o/vwhvc5:4OygsaZOhtlLezlb0TfAthaD2v`

## Runtime Data

### Usage (stdout):
```cmhg
Error: INCORRECT SYNTAX

------ Commands supported ------

/TestDCs                          Checks domain controller configuration.

/TestSites                        Checks site associations.

/TestDFSConfig                    Checks DFS Namespace configuration.

/TestDFSIntegrity                 Checks DFS Namespace integrity.

/TestReferral                     Checks referral responses.

/?                                Displays this help.

Notes:
Use the /? parameter after any command to display help for the command.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DfsDiag.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## dfsdiag

Provides diagnostic information for DFS Namespaces.

### Syntax

```
dfsdiag /testdcs [/domain:<domain name>]
dfsdiag /testsites </machine:<server name>| /DFSPath:<namespace root or DFS folder> [/recurse]> [/full]
dfsdiag /testdfsconfig /DFSRoot:<namespace>
dfsdiag /testdfsintegrity /DFSRoot:<DFS root path> [/recurse] [/full]
dfsdiag /testreferral /DFSpath:<DFS path to get referrals> [/full]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [dfsdiag testdcs](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/dfsdiag-testdcs.md) | Checks domain controller configuration. |
| [dfsdiag testsites](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/dfsdiag-testsites.md) | Checks site associations. |
| [dfsdiag testdfsconfig](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/dfsdiag-testdfsconfig.md) | Checks DFS Namespace configuration. |
| [dfsdiag testdfsintegrity](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/dfsdiag-testdfsintegrity.md) | Checks DFS Namespace integrity. |
| [dfsdiag testreferral](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/dfsdiag-testreferral.md) | Checks referral responses. |
| /? | Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


