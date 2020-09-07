---
title: bcdboot.exe | Bcdboot utility
---

# bcdboot.exe 

* File Path: `C:\windows\system32\bcdboot.exe`
* Description: Bcdboot utility

## Hashes

Type | Hash
-- | --
MD5 | `2BC3C46D9FF5DEACE62D581E905B60FC`
SHA1 | `399A675F69CE5F3D17EAFA07306FFFA56678888D`
SHA256 | `606923EB7A078BC6B038AC4D51C6647D50982203F9533886E5ABD2763209D526`
SHA384 | `8C6C327BC7E31D629258B66E5885EB98643D83D4F81205E9543DAD55A5F8A8BC22B6D3C3E7115974997F793436CCACAF`
SHA512 | `8B712B8D9319E5A259AA4063C243CCB3190B3B8F8F2F6A6BBAE4B4437CF571EF79A7BA27A0EAB137BB76BA91AAC3FFEAC94AC2FF1E96DB14C0B6D53B63DA1887`
SSDEEP | `3072:xe1cMf+gIkvIemGyVNZTssC+9VyhXJhACmMMV2:qdf+gIkQbbN1sr+rEq`

## Signature

* Status: The file C:\windows\system32\bcdboot.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: bcdboot.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## bcdboot

Enables you to quickly set up a system partition, or to repair the boot environment located on the system partition. The system partition is set up by copying a simple set of Boot Configuration Data (BCD) files to an existing empty partition.

### Syntax

```
bcdboot <source> [/l] [/s]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| source | Specifies the location of the Windows directory to use as the source for copying boot environment files. |
| /l | Specifies the locale. The default locale is US English. |
| /s | Specifies the volume letter of the system partition. The default is the system partition identified by the firmware. |

### Examples

For information about where to find BCDboot and examples of how to use this command, see the [BCDboot Command-Line Options](/previous-versions/windows/it-pro/windows-8.1-and-8/hh824874(v=win.10)) topic.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


