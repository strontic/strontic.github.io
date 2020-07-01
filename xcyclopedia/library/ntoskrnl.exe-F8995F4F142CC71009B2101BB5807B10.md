---
title: ntoskrnl.exe | NT Kernel & System
---

# ntoskrnl.exe 

* File Path: `C:\windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F8995F4F142CC71009B2101BB5807B10`
SHA1 | `5E1BBFBABE25F97E95F9B83E4C98A79C217422F0`
SHA256 | `474A3FBA47AA1505036D12C329787D85C175E5CB53A90FFD06C0DB4B1864EE17`
SHA384 | `BBC699235B545B9466283406EA0FDB1E0360C4A7232E01F621431745B88796DE86A6EC7F9143D13FABE98494F8973DFB`
SHA512 | `1AE138398B74191ABA738DC082147E1AC9E2BE38791B6F6E46E68A103418AF059254526CC5E5CF2E84CB87193338BCC04D90BB6043B356E9F1976E34740C687F`
SSDEEP | `98304:USxYBKmf+iRsG552utpOBtCD4ZBF/Ez6/MQYzMz4Y6KXq:wVqGKkQO4ZBF/Ez6/Du+2`

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
* File Version: 6.3.9600.19724 (winblue_ltsb_escrow.200519-1914)
* Product Version: 6.3.9600.19724
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | <blockquote>Adversaries may interact with the native Windows application programming interface (API) to execute behaviors. Similar to the system call interface on UNIX systems, the Windows native API provides a controlled means to calling low-level OS services within the kernel, such as those involving hardware/devices, memory, and processes. The native API is leveraged by the OS during system boot (when other system components are not yet initialized) but is also exposed to user-mode applications via ntdll.dll and ntoskrnl.exe.(Citation: Microsoft NativeAPI) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


