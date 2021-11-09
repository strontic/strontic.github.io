---
title: ktmutil.exe | Kernel Transaction Management Utility
excerpt: What is ktmutil.exe?
---

# ktmutil.exe 

* File Path: `C:\WINDOWS\system32\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `F4EFA6563E9BCE854E59E60DDAEFFBC0`
SHA1 | `70D17DE5531AC21509DC7E5E2AE5171B3A561196`
SHA256 | `7C2BB802B42AF63FCCF5D27FDD7820CCAAB372CAD102F947FC9049BF6F2C146F`
SHA384 | `E1C5D4009C8A0136B2E91352D1C78DD0626780677A8C3DFAA790E3489892D961C5997A572B03350A42CAEC6EEF1C5163`
SHA512 | `D2722C4568920C6D9837454BE2DFFFACB285BA99E1096C6262809E17B5970C04C19C3D20DDD4BE50C23CF932B6B4236C40E48B4F7A9C50E5246EDDB02CFE98A8`
SSDEEP | `384:NGFZF+Y/8BfuxndAckQoCKEfV+NQOWcjW:0FZkfRfGJs`
IMP | `AF7B616A91124C80D5AC086429B5FD63`
PESHA1 | `3FAA545C5B1EACCDB423E6E13D72B615616C5F35`
PE256 | `98BD102F5CB6461FD5CB4E2ED3AE0F13D2818CB00BFA3320F02F98D907B6001E`

## Runtime Data

### Usage (stdout):
```cmhg
--help is an invalid parameter.
---- Commands Supported ----

tx     Commands related to transactions
tm     Commands related to transaction managers

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\ktmutil.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7c2bb802b42af63fccf5d27fdd7820ccaab372cad102f947fc9049bf6f2c146f/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ktmutil

Starts the Kernel Transaction Manager utility. If used without parameters, **ktmutil** displays available subcommands.

### Syntax

```
ktmutil list tms
ktmutil list transactions [{TmGUID}]
ktmutil resolve complete {TmGUID} {RmGUID} {EnGUID}
ktmutil resolve commit {TxGUID}
ktmutil resolve rollback {TxGUID}
ktmutil force commit {GUID}
ktmutil force rollback {GUID}
ktmutil forget
```

### Examples


To force an Indoubt transaction with GUID 311a9209-03f4-11dc-918f-00188b8f707b to commit, type:

```
ktmutil force commit {311a9209-03f4-11dc-918f-00188b8f707b}
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


