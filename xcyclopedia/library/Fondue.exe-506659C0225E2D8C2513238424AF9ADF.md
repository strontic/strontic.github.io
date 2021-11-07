---
title: Fondue.exe | Windows Features on Demand UX
excerpt: What is Fondue.exe?
---

# Fondue.exe 

* File Path: `C:\windows\system32\Fondue.exe`
* Description: Windows Features on Demand UX

## Screenshot

![Fondue.exe](screenshots/Fondue.exe-79DF3567F912F45AE9BC0664A397C858.png)

## Hashes

Type | Hash
-- | --
MD5 | `506659C0225E2D8C2513238424AF9ADF`
SHA1 | `99D012FB311D00A3AB3425298DD88CBE4443AC2E`
SHA256 | `A7DD9378D44CE86FFEBC0292F59EF096595043E6114011A0CFD9295F0A6CF7A2`
SHA384 | `85205BAD74DFEFBD57C099B84A902C6B7BAB164A5E7290762C2C9C4CED672F107D873F4A24A4CA27978CB07213F144AB`
SHA512 | `90E58AC7B807FAB6C59047B935A46557AC0EB53F19FF1BCD0C6405742F6F1B4B0B14FB0AE9C7966B5C71E126D2D385DB6CDD3DF27F44D2A4D41D1E3AC4D0833D`
SSDEEP | `3072:XxbEaznWfH22ZsuX2xKwMPTnaSrIrvDb:dznWjZnXeKwMLnaqY`

## Signature

* Status: The file C:\windows\system32\Fondue.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Fondue.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Fondue.exe](Fondue.exe-237E1F3944532E26BB1EB945798DB582.md) | 88
[C:\WINDOWS\system32\Fondue.exe](Fondue.exe-79DF3567F912F45AE9BC0664A397C858.md) | 85
[C:\Windows\system32\Fondue.exe](Fondue.exe-EEE0F4A169799F00BAD87C7D0834E348.md) | 85
[C:\Windows\system32\Fondue.exe](Fondue.exe-F995D2EF9220F33C260425DB39ED05A3.md) | 88
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-9BDA0F9DCFDB837F1A5298940EC51B9A.md) | 88
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-D6CD8BEF71458804DBC33B88ACE56372.md) | 90
[C:\WINDOWS\system32\OptionalFeatures.exe](OptionalFeatures.exe-EF0418CF89AD1C48D855A11F162AA08D.md) | 88
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-F5E6A72C8DC8F430EB2C56958665EBA6.md) | 90
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-0E9BE52DB9A66E19CF012D33E10E5EA7.md) | 93
[C:\WINDOWS\SysWOW64\Fondue.exe](Fondue.exe-13C83CB32EE31E91B85EE5F499BCB13C.md) | 93
[C:\windows\SysWOW64\Fondue.exe](Fondue.exe-177C1130949E620616BA63D9D27913FE.md) | 85
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-69A312336DBCAE207F5D8C04520B9B3C.md) | 90
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-EEEA1F28FE960B2CA15A199B8EE96E5E.md) | 93


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## fondue

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables Windows optional features by downloading required files from Windows Update or another source specified by Group Policy. The manifest file for the feature must already be installed in your Windows image.

### Syntax

```
fondue.exe /enable-feature:<feature_name> [/caller-name:<program_name>] [/hide-ux:{all | rebootrequest}]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /enable-feature:`<feature_name>` | Specifies the name of the Windows optional feature you want to enable. You can only enable one feature per command line. To enable multiple features, use fondue.exe for each feature. |
| /caller-name:`<program_name>` | Specifies the program or process name when you call fondue.exe from a script or batch file. You can use this option to add the program name to the SQM report if there is an error. |
| /hide-ux:`{all | rebootrequest}` | Use **all** to hide all messages to the user including progress and permission requests to access Windows Update. If permission is required, the operation will fail.<p>Use **rebootrequest** to only hide user messages asking for permission to reboot the computer. Use this option if you have a script that controls reboot requests. |

#### Examples

To enable Microsoft .NET Framework 4.8, type:

```
fondue.exe /enable-feature:NETFX4
```

To enable Microsoft .NET Framework 4.8, add the program name to the SQM report, and not display messages to the user, type:

```
fondue.exe /enable-feature:NETFX4 /caller-name:Admin.bat /hide-ux:all
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Microsoft .NET Framework 4.8 Download](https://dotnet.microsoft.com/download/dotnet-framework/net48)

---



MIT License. Copyright (c) 2020-2021 Strontic.


