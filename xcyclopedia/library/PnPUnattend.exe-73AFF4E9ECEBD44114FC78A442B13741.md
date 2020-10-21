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
MD5 | `73AFF4E9ECEBD44114FC78A442B13741`
SHA1 | `2CC9A0852622B32C4B152C862838EA93C654BE16`
SHA256 | `1BD75ED2ADBB32C2863B5A3B117DEC61EE2BFBDF4AA6892670CA5E23C2D9424F`
SHA384 | `D2661A67DB484D908529DF6B1DD057DF72B765D7414DD9EE0FCE70E1697EF98E47D90BEEFCE238CD9D1662EFF4C19E7A`
SHA512 | `A0081ED1E2CB734BA5B2311C6CB8942F425E69CACCE00348CB00AE23842A6DC96E4F2EC5C4CC4001C9C3DB2FE26BDC7F9256F060D6526870793F2695F0F49010`
SSDEEP | `768:hyPKrBx6AkCDTKAcrYeKRcdvQv7J3JAZVkhIjgkp5e0cVnxDQVW5RKpLdRh5VnDb:IK10XCqAcrYeitJ3siloeZ3QkS3y/a`
IMP | `43B208E7D537FA25FB5182C0A73AD298`
PESHA1 | `E7707193EE9FA537A510A23D06AD6CDAC3604B47`
PE256 | `9A9C3E979B737CB4BE00D5A86CEB00CED084E0F0218DD3DCFC0EACC9F0F1F963`

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
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dbgcore.DLL |
C:\Windows\system32\dbghelp.dll |
C:\Windows\system32\DEVRTL.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MPR.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\newdev.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\PnPUnattend.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\wdscore.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PnPUnattend.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/1bd75ed2adbb32c2863b5a3b117dec61ee2bfbdf4aa6892670ca5e23c2d9424f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PnPUnattend.exe](PnPUnattend.exe-6F312206A2461C38A9F6A1E7E525DB5D.md) | 25


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


