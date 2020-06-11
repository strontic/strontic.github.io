
# TRACERT.EXE 

* File Path: `C:\Windows\SysWOW64\TRACERT.EXE`
* Description: TCP/IP Traceroute Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DD140EA0EA8C9916A9B8E98FD52BFCB0`
SHA1 | `5175874A8D40CEF229D3E3B80227D31AAE4BF743`
SHA256 | `76FEB1D499DD6F349E80508FBB2C1DFC594A2B58D0563341C2EAC89B786FF3E7`
SHA384 | `F0ECCB5A7187781C314E27545ABBA057627976ED868317A5C215A71C58E92BD33F4123536794DD9BC4F7E41B3A5B1AE1`
SHA415 | `E5702E9D807F7A0C30A5F08D7FCBB624FB5CF7FA7C0765BAA30E3AC1ED5B7AB99600764AE940966B0A10B57EAAD8E2618D3F128E7440C88D6BD4A5FC06D0574D`
SSDEEP | `192:XOgC1wDmojwzWIRKWGWxe0cNI4XeTiJiA3A4WyTc1WjpSZWWhaWfgCYI:XOgKejwjKWGWdkTXAryRjpHWhaWY`

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


