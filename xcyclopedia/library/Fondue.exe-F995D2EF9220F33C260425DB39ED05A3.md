﻿---
title: Fondue.exe | Windows Features on Demand UX
excerpt: What is Fondue.exe?
---

# Fondue.exe 

* File Path: `C:\Windows\system32\Fondue.exe`
* Description: Windows Features on Demand UX

## Screenshot

![Fondue.exe](screenshots/Fondue.exe-79DF3567F912F45AE9BC0664A397C858.png)

## Hashes

Type | Hash
-- | --
MD5 | `F995D2EF9220F33C260425DB39ED05A3`
SHA1 | `E52B96C6263BE61D632E87861F052B6DABE392BF`
SHA256 | `29A612CAA964CE61D8FFBC2951EC2C1A401AB775C1883782AD83FDE8CFA19DE6`
SHA384 | `F6B38EB1BE00D6E4D408CDB2C25C104CB54501206FB12446487A22B7833ACE6494BAC08EC8B34DAF9098ABDFC879583A`
SHA512 | `CC630797C013E368CFAB47DB1D643D10E8590F69B09AFB4748D4A1B06F00858231AE41B6F39F81DAB17131311E136114A1E39127B1C9F17298AA7FFB9297A5C4`
SSDEEP | `3072:s4H1bKbEaznWfH22ZsuX2xKwMPTnaSrIrvDi:sobMznWjZnXeKwMLnaqY`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Fondue.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Fondue.exe](Fondue.exe-237E1F3944532E26BB1EB945798DB582.md) | 86
[C:\windows\system32\Fondue.exe](Fondue.exe-506659C0225E2D8C2513238424AF9ADF.md) | 88
[C:\WINDOWS\system32\Fondue.exe](Fondue.exe-79DF3567F912F45AE9BC0664A397C858.md) | 83
[C:\WINDOWS\system32\Fondue.exe](Fondue.exe-B2394CA80127A7BAB628DA4F5D629DA8.md) | 80
[C:\Windows\system32\Fondue.exe](Fondue.exe-EEE0F4A169799F00BAD87C7D0834E348.md) | 80
[C:\WINDOWS\system32\OptionalFeatures.exe](OptionalFeatures.exe-18FDAD8492E77DC6C6AD062F9AB7524B.md) | 82
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-9BDA0F9DCFDB837F1A5298940EC51B9A.md) | 86
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-D6CD8BEF71458804DBC33B88ACE56372.md) | 86
[C:\WINDOWS\system32\OptionalFeatures.exe](OptionalFeatures.exe-EF0418CF89AD1C48D855A11F162AA08D.md) | 86
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-F5E6A72C8DC8F430EB2C56958665EBA6.md) | 88
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-0E9BE52DB9A66E19CF012D33E10E5EA7.md) | 91
[C:\WINDOWS\SysWOW64\Fondue.exe](Fondue.exe-13C83CB32EE31E91B85EE5F499BCB13C.md) | 91
[C:\windows\SysWOW64\Fondue.exe](Fondue.exe-177C1130949E620616BA63D9D27913FE.md) | 80
[C:\WINDOWS\SysWOW64\Fondue.exe](Fondue.exe-1A274BFE1306A75C215A832F274F4E44.md) | 82
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-69A312336DBCAE207F5D8C04520B9B3C.md) | 86
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-EEEA1F28FE960B2CA15A199B8EE96E5E.md) | 88


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


