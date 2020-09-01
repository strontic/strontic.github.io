---
title: tzsync.exe | TimeZone Sync Task
---

# tzsync.exe 

* File Path: `C:\WINDOWS\system32\tzsync.exe`
* Description: TimeZone Sync Task

## Hashes

Type | Hash
-- | --
MD5 | `F739247404C7C70C5B4DBCCEC91CF733`
SHA1 | `240314E251E76BE7B1520E6937BCE372A6C99794`
SHA256 | `CC2A37EEF0D031A87BAD220A6E9615E5F68B13E2311DD54560A9BF94BD0DCCCC`
SHA384 | `D409EF4F0D23DADE70EB688C3A58CD0A93A592DE7B55B7A7BB042858619821F89BD5226893C146E79ACB743A5ED1A17F`
SHA512 | `5734A7A93CF182E383A2D147D1FE23FC35B6684B22C2EE058528E5BC181D81309F47D1B44A159DEEDF8C003E7DB54A70E470CBFEC75E12364B9AFE0D6C0E683B`
SSDEEP | `768:gMO5WXdGYTNKWJDGYyXb0cDrQoNWt7G/XQYyKC7MGMEf9jZpAXDRXWfjP6:bGKNl9GDXbVDUoY7G/gYyKf19`

## Runtime Data

### Usage (stderr):
```Batchfile

Unhandled Exception: System.Security.SecurityException: Requested registry access is not allowed.
   at System.ThrowHelper.ThrowSecurityException(ExceptionResource resource)
   at Microsoft.Win32.RegistryKey.OpenSubKey(String name, Boolean writable)
   at TimeZoneSyncTask.TimeZoneSync.Sync()
   at TimeZoneSyncTask.Program.Main(String[] args)

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tzsync.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tzsync.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\tzsync.exe](tzsync.exe-5BB8DEB569B92CAE95617286BD25ED99.md) | 54




MIT License. Copyright (c) 2020 Strontic.


