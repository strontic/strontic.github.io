---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\windows\SysWOW64\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `26E60BA376F020E4357DCB3EFCF78F42`
SHA1 | `0E794CF269EE3AD14D9C04EFFAF479747AC8E015`
SHA256 | `50B933A5B3EC2C3CBF95EFD1E1F5B4FE664B06F55EB2B7277B14EF8D07CD5820`
SHA384 | `D4FA1FCBF82FEACC53C017E70A41749C46763CAF0B0DA862528722C143A86EE84782777AC5A6E3F6E3A1025EBFA7739C`
SHA512 | `FD557524E6A27CF8C0EBD6F02EEE35E952EDDB3B09A7049BFAF065A095FF6C8AE98A700FFE8E3B16802DACDE87EA881DD13776A310D848E43291EC84F733ABE0`
SSDEEP | `24576:NR7C+uj9Pf6G5EhDvjoz3MhtNKWUexvRvD:Po9PyG50vjoz3MhtNKW5lFD`

## Signature

* Status: The file C:\windows\SysWOW64\autoconv.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


