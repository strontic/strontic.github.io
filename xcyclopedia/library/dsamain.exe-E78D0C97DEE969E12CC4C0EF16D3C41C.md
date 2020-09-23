---
title: dsamain.exe | Active Directory Lightweight Directory Services
excerpt: What is dsamain.exe?
---

# dsamain.exe 

* File Path: `C:\Windows\system32\dsamain.exe`
* Description: Active Directory Lightweight Directory Services

## Hashes

Type | Hash
-- | --
MD5 | `E78D0C97DEE969E12CC4C0EF16D3C41C`
SHA1 | `2B51C336F237391D7631130D6D1D25311F78B4A9`
SHA256 | `E676C24874C8AA1225CFAB35EA78BC79EAB8A9D9B4D283559F21722CE8B1E9DB`
SHA384 | `D3F63642EBD791B876A211B0E4990793C116259CEA430B5BD969AC0B91CAD05A4A14B7D73873FFAB3CDC1B15801E283A`
SHA512 | `73D0598C043BA1886539020B673776FE245636D1DACCD1E95853C943986EA213DB01E915624638F5AC81A12057A2E25BE7332833C17FB98C7E01A9043539FE4C`
SSDEEP | `192:VjAyf6WCHBJuIR42MREUoSZeVujtmMYGeEXkfWlZmjuKWDgW:VjAymAcKEHTdMYRfWmBWDgW`

## Runtime Data

### Usage (stdout):
```cmhg
EVENTLOG (Error): NTDS General / Initialization/Termination : 2874

AD/DS/LDS offline data browser.

Usage:
C:\Windows\system32\dsamain.exe options
Options:

  -dbpath filepath       (required) Filepath must point to the DIT file on the
                         local server, which could be on read-only media (such
                         as a snapshot). The DIT must be in a consistent state,
                         that is, the ESE logs must be replayed.

  -logpath path          (optional) The path should point to a writeable folder
                         on the local server, where ESE log files will be
                         created. If not specified, then temp folder will be
                         used.

  -adlds                 (optional) open AD/LDS DIT.

  -ldapPort number       (required) LDAP port value.
  -sslPort number        (optional) SSL port value. Default: LDAP port+1
  -gcPort number         (optional) GC port number. Default: LDAP port+2
  -gcSslPort number      (optional) GC SSL port number. Default: LDAP port+3

  -allowUpgrade          (optional) Allow to upgrade the DIT file. This is
                         useful for opening downlevel DITs/snapshots. The
                         file needs to be on writable media.

  -allowNonAdminAccess   (optional) Allow non-administrators to access data
                         in the directory. If not specified, then only Domain
                         Admins and Enterprise Admins from the target domain
                         will be able to access the data.



```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\dsamain.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsamain.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


