
# TRACERT.EXE 

* File Path: `C:\WINDOWS\system32\TRACERT.EXE`
* Description: TCP/IP Traceroute Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2EFE82589249126CA80CC1C536FCBDDA`
SHA1 | `3B0532961A295CC66DF51ABB611AD55FD64141E5`
SHA256 | `5817A6B5D24D21E19A05A08253737B1D2842B612EC1B90F9B928D78FAD271092`
SHA384 | `A5DED7BC32B99153B8271095DF6BDE0CCFAD8D629AB128F458B1F6B7595C4AFFB1201E9C56AA391A6818805EACC35D55`
SHA415 | `A9DEA838166A4F7539E5D0144B208DB97BD82465D547F11BA19EDBE32FA4EB7E56CD1F392B77A5FC37AC3396A05DE98D1D45CB73EB905E02B5D22C7428B17794`
SSDEEP | `384:GAdLHysXU6ChInwbCZrzlrxoTlmFL1yzqWfaW:GeTCStzATQFL1Ij`

## Runtime Data

### Usage (stdout):
```Batchfile

Usage: tracert [-d] [-h maximum_hops] [-j host-list] [-w timeout] 
               [-R] [-S srcaddr] [-4] [-6] target_name

Options:
    -d                 Do not resolve addresses to hostnames.
    -h maximum_hops    Maximum number of hops to search for target.
    -j host-list       Loose source route along host-list (IPv4-only).
    -w timeout         Wait timeout milliseconds for each reply.
    -R                 Trace round-trip path (IPv6-only).
    -S srcaddr         Source address to use (IPv6-only).
    -4                 Force using IPv4.
    -6                 Force using IPv6.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tracert.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


