---
title: PnPUnattend.exe | PnP unattend action
excerpt: What is PnPUnattend.exe?
---

# PnPUnattend.exe 

* File Path: `C:\Windows\system32\PnPUnattend.exe`
* Description: PnP unattend action

## Hashes

Type | Hash
-- | --
MD5 | `036FADF41AAD27390DC0C7C141F09F0C`
SHA1 | `833CD4B5934B41EE815DD4486386564C1294BE71`
SHA256 | `DAAA6F8DFAFFDA95DCD17C30BEBD41A9C6F1B913EC37B34E0F137E35D5BA33A6`
SHA384 | `E3C8B1E40B11FE4267062EE81EDC28669C5DA5B965D6F8D9F8C169A0C10A4040050526C86A8DBB829127E7ADD4A27562`
SHA512 | `C9FF688BCD4CA21E3E577781CF21BF50201B5F0C455F9EFDF6413AB1B9788A956EB99DE8B44EBD5479315D20806D8600B31ED7A34B55EB5E054F9F853A908EBA`
SSDEEP | `1536:IrZgZdA+8KYh+uMeJVSPiDYd3Qk94nA5lA:9dq/h+PeJlkdp9E/`
IMP | `C932EE34DAB949E336FC1EEE748E7A12`
PESHA1 | `99C87C3F89A1B4EAB15FA509BBE8D0F0880A31D7`
PE256 | `926B080B05F204B72372580F95E5A03C7CC37CEA0A4FC3DE27ADAEA3950A7F43`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\PnPUnattend.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PnPUnattend.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/daaa6f8dfaffda95dcd17c30bebd41a9c6f1b913ec37b34e0f137e35d5ba33a6/detection



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


