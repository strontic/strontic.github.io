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
MD5 | `6F312206A2461C38A9F6A1E7E525DB5D`
SHA1 | `FAC45AF43F5B987AFF0029554DB87021A1E6D71B`
SHA256 | `203CAC6B3B737623FF0A3FFB755A9CC9955090DA74A2EB799245F329BA38728F`
SHA384 | `0652144E71B455186340BBBB73EA3C67DEC127AC2B9D670951C39616AA57476F17368EF7D757965CCCC21BB10EC61064`
SHA512 | `8F947FED2B08885A2DB12636F4C12C2301F19AD6B7E222EAD0BF9522442760B5B0580B3F73776825D37A2BA6F828D56DF6AE5775DE9AF971B52391DFF0D34082`
SSDEEP | `768:dyWVS6RNl4eRgEhe4vORPimz25rIeuAKS0Zj7Wl8Jry2KjZl7nxDQVW5RQGtGtvg:fVD15hgRPYmS01V+LNQkQFBjY8BO`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PnPUnattend.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PnPUnattend.exe](PnPUnattend.exe-73AFF4E9ECEBD44114FC78A442B13741.md) | 25


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


