---
title: pwlauncher.exe | Windows To Go Startup Options Command Line Tool
excerpt: What is pwlauncher.exe?
---

# pwlauncher.exe 

* File Path: `C:\WINDOWS\system32\pwlauncher.exe`
* Description: Windows To Go Startup Options Command Line Tool

## Hashes

Type | Hash
-- | --
MD5 | `CCC659C828468FE157FF0112706F8829`
SHA1 | `1F506D9AFD9F5B86BE2F3EEA9E43B56587519E65`
SHA256 | `96119C55A9552B815C826492F2A1F8A7840EA16B31BE6A1D12849349A8091393`
SHA384 | `C64E68EC68F2F9C8BB07BA6662482BAEE49EE5F53B7D3847C029F10673B29B0525080ED70CC3B8767BC7A3029CE630A4`
SHA512 | `D7B7B801385B13979F9AC773FC5B5BC0D1B3747661FA315343395EA0DE93C569738FB03A25DB46F43A86EA7298F2D53CB29D32FF63CC701C8620B8A1F825DF67`
SSDEEP | `768:3ZOwoLXUJwgFeYh3xbMK8Eq35EiZhJtB+wFX0PjfixO+zs+pi:3ZOwoLXgVd3b8T7N0fiY+vpi`
IMP | `83C9DF9631980ADBA74EDD944AB6F667`
PESHA1 | `6E1161E37809514AE00E6EEABB9EB6C3EB1004AD`
PE256 | `F1385F38AB0421D3EAF26484E38093A679A74C279700EBB58B1DCB04D155A998`

## Runtime Data

### Usage (stdout):
```cmhg
pwlauncher.exe - Windows To Go startup options command-line tool.

The pwlauncher.exe command-line tool is used to query or change your Windows To
Go startup options.

pwlauncher [/enable | /disable]

    <<no parameter>>    Display the current state.

    /enable             Enable the startup option.

    /disable            Disable the startup option.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\pwlauncher.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pwlauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/96119c55a9552b815c826492f2a1f8a7840ea16b31be6a1d12849349a8091393/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## pwlauncher

Enables or disables the Windows To Go Startup Options (pwlauncher). The **pwlauncher** command-line tool allows you to configure the computer to boot into a Windows To Go workspace automatically (assuming one is present), without requiring you to enter your firmware or change your startup options.

Windows To Go Startup Options allow a user to configure their computer to boot from USB from within Windows-without ever entering their firmware, as long as their firmware supports booting from USB. Enabling a system to always boot from USB first has implications that you should consider. For example, a USB device that includes malware could be booted inadvertently to compromise the system, or multiple USB drives could be plugged in to cause a boot conflict. For this reason, the default configuration has the Windows To Go Startup Options disabled by default. In addition, administrator privileges are required to configure Windows To Go Startup Options. If you enable the Windows To Go startup options using the pwlauncher command-line tool or the **Change Windows To Go Startup Options** app the computer will attempt to boot from any USB device that is inserted into the computer before it is started.

### Syntax

```
pwlauncher {/enable | /disable}
```

#### Parameters

| Parameter | Description |
|--|--|
| /enable | Enables Windows To Go startup options, so the computer will automatically boot from a USB device when present. |
| /disable | Disables Windows To Go startup options, so the computer can't be booted from a USB device unless configured manually in the firmware. |
| /? | Displays help at the command prompt. |

#### Examples

To enable boot from USB:

```
pwlauncher /enable
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


