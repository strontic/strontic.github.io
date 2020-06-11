
# TRACERT.EXE 

* File Path: `C:\Windows\system32\TRACERT.EXE`
* Description: TCP/IP Traceroute Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `06B4F2EA25F920C6A948B81AA6465D83`
SHA1 | `31F9E9185786603CDA592D30CC3D7A92AFBF92E4`
SHA256 | `A2B9965CE3C54E3F5F8CDCD57D955D320CF41F06ED6D62BE5D1D64A0EB19267E`
SHA384 | `1DAAC8FB091B033E9B347A709C9A7DD218E5175FAD2F281A86A88AF8A35DCC231D9D08A3D5766ECBAC72B0453B430955`
SHA415 | `53CF4F8FD4E8B2E1D6B67B7BCBD839A87F90653E7268D708AF020B496DFEDC4220362AADA5E19B9AE2ADB7DC59063F80EB41B20FF1CBF62F9F44ABA690ACA19D`
SSDEEP | `384:hC/5fI3JWxX3I9NCT6hfPyTDr8QTZm43jo0qSWhaW:hCVkUp+Pt0ZmajlqF`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tracert.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


