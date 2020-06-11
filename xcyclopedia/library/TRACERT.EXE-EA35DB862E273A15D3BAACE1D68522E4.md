
# TRACERT.EXE 

* File Path: `C:\WINDOWS\SysWOW64\TRACERT.EXE`
* Description: TCP/IP Traceroute Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EA35DB862E273A15D3BAACE1D68522E4`
SHA1 | `EBBF1E4C58912F7CE21C6EA81378956FD781AD3B`
SHA256 | `618B29888378DAD8E326059DEB324D34A9B51C7C00BD0AFB2270BB37FDC428BC`
SHA384 | `D5DA4E6636C28F7C3EAEBE29E8523091079CEE69B7C909084540862AC8D7DF47016C67EFAE11CDA950EFB3DEA1590192`
SHA415 | `95408536C2E74234E213FCC330C8E0BCE27E4D0003CC97A36D1DB95F09D094DEF7C2864DA16CF5CF609FAD56D93258FB40BD82AFD727CCE89A50A25405C2A0BF`
SSDEEP | `384:ySQTBs+gdwrTE4g1veQKBrmEL1bCWfaW:7L8I4g1SBaEL1X`

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

* Original Filename: tracert.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


