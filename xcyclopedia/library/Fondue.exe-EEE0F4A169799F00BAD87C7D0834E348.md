---
title: Fondue.exe | Windows Features on Demand UX
---

# Fondue.exe 

* File Path: `C:\Windows\system32\Fondue.exe`
* Description: Windows Features on Demand UX
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EEE0F4A169799F00BAD87C7D0834E348`
SHA1 | `32739C7A48F6EC534BD4A371D1838246BCCCA114`
SHA256 | `E86B8997664E14FB6D0972D1E9D394A99AFE9E877A7911CBE7A0E575EF04791E`
SHA384 | `E3FC368FAB4C8648530E0272D4B3D8040394DED57674CF5ADEA18147B2E61016C790AB6092F3B0D921A962B7B34D9625`
SHA512 | `691923223EE63DFE76E42342EC02FA385D358E328A53964FEC60BFE6B6CB4C1175BFF2AAE3FBDD66C82F0C3B77965C368E0258AB56FE73692A5C77AF73F29EA1`
SSDEEP | `3072:SyQQtGibEaznWfH22ZsuX2xKwMPTnaSrIrvD2:SyHG0znWjZnXeKwMLnaqY`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Fondue.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Fondue.exe](Fondue.exe-237E1F3944532E26BB1EB945798DB582.md) | 85
[C:\WINDOWS\system32\Fondue.exe](Fondue.exe-79DF3567F912F45AE9BC0664A397C858.md) | 86
[C:\Windows\system32\Fondue.exe](Fondue.exe-F995D2EF9220F33C260425DB39ED05A3.md) | 80
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-9BDA0F9DCFDB837F1A5298940EC51B9A.md) | 85
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-D6CD8BEF71458804DBC33B88ACE56372.md) | 83
[C:\WINDOWS\system32\OptionalFeatures.exe](OptionalFeatures.exe-EF0418CF89AD1C48D855A11F162AA08D.md) | 85
[C:\Windows\system32\OptionalFeatures.exe](OptionalFeatures.exe-F5E6A72C8DC8F430EB2C56958665EBA6.md) | 82
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-0E9BE52DB9A66E19CF012D33E10E5EA7.md) | 86
[C:\WINDOWS\SysWOW64\Fondue.exe](Fondue.exe-13C83CB32EE31E91B85EE5F499BCB13C.md) | 85
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-69A312336DBCAE207F5D8C04520B9B3C.md) | 85
[C:\Windows\SysWOW64\Fondue.exe](Fondue.exe-EEEA1F28FE960B2CA15A199B8EE96E5E.md) | 83


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


