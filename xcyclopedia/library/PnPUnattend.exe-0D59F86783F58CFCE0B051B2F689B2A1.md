---
title: PnPUnattend.exe | PnP unattend action
---

# PnPUnattend.exe 

* File Path: `C:\WINDOWS\system32\PnPUnattend.exe`
* Description: PnP unattend action

## Hashes

Type | Hash
-- | --
MD5 | `0D59F86783F58CFCE0B051B2F689B2A1`
SHA1 | `2FFC4AF7B748E7415E92F56F009F870AB4796E23`
SHA256 | `AF11D70BE2DA461C4C4DFCC085B2EAC0A736E630F6E84FB508661FB904D71730`
SHA384 | `432A728C38B92BD3C475927CDF21F4565F242CAD94786A210FDB9FEE3944A3BF0D23C43D2EB7518C680D5709B43502A0`
SHA512 | `9E84E33DD696F86520208289874DDC8AE007D25F1995E980C2AE9ADDDF81F2AD9B582F5C6B3556B70A8A4D340FA5E64237EDF4BB50DC0DBE3F4891A573CF6354`
SSDEEP | `1536:fIRknmzWcT7uJOL5SF1w8MnN3QkqlMIE:6gmWJaD8MNpUM5`

## Runtime Data

### Usage (stdout):
```cmhg
DESCRIPTION:
AuditSystem, Unattend online driver install 

USAGE:
   PnPUnattend.exe [auditSystem | /help /? /h] [/s] [/L]
       auditSystem   Online driver install.
       /help /? /h    This help.
       /s             Search without installing.
       /L             Print Logging information to the command line.


```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PnPUnattend.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## pnpunattend

Audits a computer for device drivers, and perform unattended driver installations, or search for drivers without installing and, optionally, report the results to the command line. Use this command to specify the installation of specific drivers for specific hardware devices.

### Prerequisites

Preliminary preparation is required for older versions of the Windows operating system. Prior to using this command, you must complete the following tasks:

1. Create a directory for the drivers you want to install. For example, create a folder at **C:\Drivers\Video** for video adapter drivers.

2. Download and extract the driver package for your device. Copy the contents of the subfolder that contains the INF file for your version of the operating system and any subfolders to the video folder that you created. For example, copy the video driver files to **C:\Drivers\Video**.

3. Add a system environment path variable to the folder you created in step 1.For example, **C:\Drivers\Video**.

4. Create the following registry key, and then for the **DriverPaths** key you create, set the **Value Data** to **1**.

5. For WindowsÂ® 7 navigate the registry path: **HKEY_LOCAL_Machine\Software\Microsoft\Windows NT\CurrentVersion\\**, and then create the keys: **UnattendSettings\PnPUnattend\DriverPaths\\**

### Syntax

```
PnPUnattend.exe auditsystem [/help] [/?] [/h] [/s] [/l]
```

#### Parameters

| Parameter | Description |
|--|--|
| auditsystem | Specifies online driver install.<p>Required, except when this command is run with either the **/help** or **/?** parameters. |
| /s | Optional. Specifies to search for drivers without installing. |
| /l | Optional. Specifies to display the log information for this command in the command prompt. |
| `/? | /help` | Optional. Displays help for this command at the command prompt. |

#### Examples

To command shows how to use the **PNPUnattend.exe** to audit a computer for possible driver updates, and then report the findings to the command prompt, type:

```
pnpunattend auditsystem /s /l
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


