---
title: ktmutil.exe | Kernel Transaction Management Utility
---

# ktmutil.exe 

* File Path: `C:\windows\system32\ktmutil.exe`
* Description: Kernel Transaction Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `2A4D44837372411478C3A06F6A1DE064`
SHA1 | `56CB034189FCD64E4150C798BF2F7911A92CEB1B`
SHA256 | `0390A231502C8744A7AC4191D948A9126A974C08BFB890F40E8BC32E087F2429`
SHA384 | `EBEC479EA3A1D5B4CC7A7512B0BD005179706CD7361EC5EE1DCC86F9A265CE2044DABE5334B04F8B7883FDF0AF344174`
SHA512 | `5477198E309AA43D59D099595C424ED8A2193B04628F8E4CADA0F145D21E59A921CC2B4F30213A5BA92CD5352A0D3B9E7F70BB382CF342A1E7C2179CB6ACFEC1`
SSDEEP | `192:UTv/THaWftRlVtZddH8TrB85DPiMIACzpdjZdSkAI/GDGi1+CA9yTmuWRjW:S/DlftRftZkrwuNAGjP1K1jcuWRjW`

### Loaded Modules:

Path |
-- |
C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\windows\system32\ktmutil.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ktmutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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



MIT License. Copyright (c) 2020 Strontic.


