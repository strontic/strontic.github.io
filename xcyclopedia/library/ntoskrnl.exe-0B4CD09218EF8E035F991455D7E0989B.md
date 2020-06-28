---
title: ntoskrnl.exe | NT Kernel & System
---

# ntoskrnl.exe 

* File Path: `C:\Windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0B4CD09218EF8E035F991455D7E0989B`
SHA1 | `8917EBFB3467C5E6E56A26E20BC9BA49CA43586D`
SHA256 | `9923B54ED79B57E1FD609B8226BAC634D5167A1AFCD0EB06BC79D1F1C274D496`
SHA384 | `B4F0ED027A820AAD2A3998ED455DC230C2102463FDD10F73974D9CEFF96BADF76E2635310F2C304540043841A0746362`
SHA512 | `641E1BC2BE9A2A13350DA940DA8E0982E627B051454F556E4741DD363B73A588C02F7095B43CA96CCF5D934BE4B515DAE221A067E2CE3006B371417DC06E315E`
SSDEEP | `196608:FCGwqJdBrbJ0Tt1rZFf3FCZUtGDi7eHnRGKCMIo035a/:FCGwq75It1rZFtCZUtGO7eHRMMIo04`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: ntkrnlmp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | <blockquote>Adversaries may interact with the native Windows application programming interface (API) to execute behaviors. Similar to the system call interface on UNIX systems, the Windows native API provides a controlled means to calling low-level OS services within the kernel, such as those involving hardware/devices, memory, and processes. The native API is leveraged by the OS during system boot (when other system components are not yet initialized) but is also exposed to user-mode applications via ntdll.dll and ntoskrnl.exe.(Citation: Microsoft NativeAPI) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


