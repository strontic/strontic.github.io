---
title: dispdiag.exe | Display Diagnostics
---

# dispdiag.exe 

* File Path: `C:\windows\system32\dispdiag.exe`
* Description: Display Diagnostics

## Hashes

Type | Hash
-- | --
MD5 | `0192A141A2F8BF6B8721C337488CE2D2`
SHA1 | `DEF2B5C35C65360EAE96B3930C9E3D1F4FC41B5F`
SHA256 | `DC0DDE1B7FEED4184A181C2CE437A1B2F1B67DA052105392E852654710DA2132`
SHA384 | `B80DA956BD521199061AC411E21AAF709661D5604B5E7F1663E1FA72027BACE6A5E83F33C36D48B873881A0EB12AADCC`
SHA512 | `937898C8011B74DC81D4CF2331FF72F686F5A3DF5CD6493053609147AE887B389A43278AB609F30F4E997704A8E1440E433E50934357CE5EBB881FDF55F673E4`
SSDEEP | `1536:zDaiegJuR5dpMF4B7Li8wJ7fAZWFWF452RS9r7fJQx/xRPnCylP0:XaJrMFK722ZWFW+KyXMxIylM`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\Dism\DismHost.exe |


## Signature

* Status: The file C:\windows\system32\dispdiag.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: dispdiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## dispdiag

Logs display information to a file.

### Syntax

```
dispdiag [-testacpi] [-d] [-delay <seconds>] [-out <filepath>]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| - testacpi | Runs hotkey diagnostics test. Displays the key name, code and scan code for any key pressed during the test. |
| -d | Generates a dump file with test results. |
| -delay `<seconds>` | Delays the collection of data by specified time in *seconds*. |
| -out `<filepath>`  | Specifies path and filename to save collected data. This must be the last parameter. |
| -? | Displays available command parameters and provides help for using them. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


