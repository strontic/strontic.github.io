---
title: ServerWerOptin.exe | Windows Error Reporting opt-in command-line tool
excerpt: What is ServerWerOptin.exe?
---

# ServerWerOptin.exe 

* File Path: `C:\windows\system32\ServerWerOptin.exe`
* Description: Windows Error Reporting opt-in command-line tool

## Hashes

Type | Hash
-- | --
MD5 | `A49912203F882DE98FDD9B8E0A1B84F5`
SHA1 | `C141374CDAF23B252FC80C19FB0F21AA246EDECD`
SHA256 | `3E808C7D0D1728D81D1754E068DFBBFC76D162A404D3820080BCF86D597D22BA`
SHA384 | `C0E1FBBD15017FC0920A09EA343382FBCA934267337B87663B7BA5E81DE132CC0191BD644BCFACA27F66C454A581E8CE`
SHA512 | `E4C35A72D1C4A7CA0F180CBC13C89E56890145A419BB75E3042DDAE096915DC649A670C63068C7D19D93CEE23356C2FAD83F8C0365976711860DD59069EC0C2F`
SSDEEP | `192:NVwRbUvE4HgHTe2Vbah/PBG2JpP27mifRiuP9eAFZUOWLUv0Wa:rwGTgHTe2VbuY2fwXRJP9egJWLc0Wa`

## Signature

* Status: The file C:\windows\system32\ServerWerOptin.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ServerWerOptin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\ServerCeipOptin.exe](ServerCeipOptin.exe-FF5F815F2A131A8F0C81D4996940F462.md) | 38


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## serverweroptin

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Allows you to turn on error reporting.

### Syntax

```
serverweroptin [/query] [/detailed] [/summary]
```

#### Parameters

| Parameter | Description |
|--|--|
| /query | Verifies your current setting. |
| /detailed | Specifies to send detailed reports automatically. |
| /summary | Specifies to send summary reports automatically. |
| /? | Displays help at the command prompt. |

### Examples

To verify the current setting, type:

```
serverweroptin /query
```

To automatically send detailed reports, type:

```
serverweroptin /detailed
```

To automatically send summary reports, type:

```
serverweroptin /summary
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


