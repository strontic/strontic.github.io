---
title: Fondue.exe | Windows Features on Demand UX
---

# Fondue.exe 

* File Path: `C:\Windows\SysWOW64\Fondue.exe`
* Description: Windows Features on Demand UX
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `69A312336DBCAE207F5D8C04520B9B3C`
SHA1 | `F0B1B23EB18C0818897CB36E2B16E01F2E7C63ED`
SHA256 | `8F4758F2B671E901CFC743FB7F3BD7B63094D84D55B4D8F7EB0722BA1205A6D2`
SHA384 | `DF19C94A6C044779BEE023A238A9620004DA04D1673E8DA31E3325ECF0CDE9F18172A4508B477B082F5C7BF6AFF57437`
SHA512 | `88F4BEBE4973F5F29B640792D21227D99AE234A834FAAB6C0BF07DF0BB0DCAF5D020B244E8CF752E4C1BAD3D0046313455598373A64947B65E690CAD64F600B8`
SSDEEP | `3072:2zslQbEaznWfH22ZsuX2xKwMPTnaSrIrvDJ:aQuznWjZnXeKwMLnaqY`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
Fondue.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Fondue.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Fondue.exe](Fondue.exe-237E1F3944532E26BB1EB945798DB582.md) | 85
[C:\windows\system32\Fondue.exe](Fondue.exe-506659C0225E2D8C2513238424AF9ADF.md) | 90
[C:\WINDOWS\system32\Fondue.exe](Fondue.exe-79DF3567F912F45AE9BC0664A397C858.md) | 85
[C:\Windows\system32\Fondue.exe](Fondue.exe-EEE0F4A169799F00BAD87C7D0834E348.md) | 85
[C:\Windows\system32\Fondue.exe](Fondue.exe-F995D2EF9220F33C260425DB39ED05A3.md) | 86
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-9BDA0F9DCFDB837F1A5298940EC51B9A.md) | 85
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-D6CD8BEF71458804DBC33B88ACE56372.md) | 85
[C:\WINDOWS\system32\OptionalFeatures.exe](OptionalFeatures.exe-EF0418CF89AD1C48D855A11F162AA08D.md) | 85
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-F5E6A72C8DC8F430EB2C56958665EBA6.md) | 85
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-0E9BE52DB9A66E19CF012D33E10E5EA7.md) | 88
[C:\WINDOWS\SysWOW64\Fondue.exe](Fondue.exe-13C83CB32EE31E91B85EE5F499BCB13C.md) | 90
[C:\windows\SysWOW64\Fondue.exe](Fondue.exe-177C1130949E620616BA63D9D27913FE.md) | 85
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-EEEA1F28FE960B2CA15A199B8EE96E5E.md) | 88


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## fondue

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


