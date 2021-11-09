---
title: PnPUnattend.exe | PnP unattend action
excerpt: What is PnPUnattend.exe?
---

# PnPUnattend.exe 

* File Path: `C:\WINDOWS\system32\PnPUnattend.exe`
* Description: PnP unattend action

## Hashes

Type | Hash
-- | --
MD5 | `7B40C5EC883B04A526B482AC6FB9670B`
SHA1 | `F4EA64E67597A231A27D0DEFA26083DDDEDFDA8A`
SHA256 | `342711B8AF90B020C4226EE1AF7DA5CF444BB373CA4497CE6DDDF16A20C6B635`
SHA384 | `A5AB1029F45164572CF7ED8F8D4966002B432D5382A18880EB07E6637D66CA757653A8D745CCCDC493946A3D95E3928C`
SHA512 | `F43D40685553CC206E649FE783EBD95116C4689B51E3AFF7C3BDF116006FA770F33219E3D7A334DB557E6B66EDBE4A08FDFF42B08B7E82C2D49768207FCCC5C2`
SSDEEP | `1536:Sn8VUllL92GaNqIP7/D3VtmIj1M3Qk4UbQV2:S/wNqIj/RtmIj1MpRbQA`
IMP | `B785FC9FECA50ACB62B3378712B6BDA0`
PESHA1 | `F266DBD3E435DBEFA574D6D692F173F903C253DC`
PE256 | `570417704A2250E15126A3A11A3C61925B32D6BEB31BEE3FEB9224BBED95EE19`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\PnPUnattend.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PnPUnattend.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/342711b8af90b020c4226ee1af7da5cf444bb373ca4497ce6dddf16a20c6b635/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


