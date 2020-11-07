---
title: pwlauncher.exe | Windows To Go Startup Options Command Line Tool
excerpt: What is pwlauncher.exe?
---

# pwlauncher.exe 

* File Path: `C:\Windows\system32\pwlauncher.exe`
* Description: Windows To Go Startup Options Command Line Tool

## Hashes

Type | Hash
-- | --
MD5 | `0B80CF2D0B14393D604E1B3F45B533D3`
SHA1 | `5989C4F77687AB0D412C3B732E018E6B72D4EF94`
SHA256 | `20BD575E31804C52D7EDC3A6298ABA504878D31DF549D3FC82FE7A99EE9A966E`
SHA384 | `F540532EE9BD6E0377C2DFB6AF60441F890D2CCBDB62FB8AE25FD658D58A7FFBDA8D093A1C8721CEA695F8AE6913FF7F`
SHA512 | `DA277637BDE52D14B6E37BD3B2C9C9B90C774CA7F9D08561249B3F1651CB670446759111015BF9D8AEA5D41B013D2B440C703AC83F309888AB7DE1BE3634A0A7`
SSDEEP | `768:3tosHsyociq2KK0Mqqvgz1QoL7JTHcs7z9JGBphb7idM8UOa5:dosHr3f7g+QoHx8s7z94Bzb7yNUO6`
IMP | `10E2E3C83FAD470F2219B3E8C8A1881E`
PESHA1 | `4107D3F04AD8247594DC1696582A19DE23D283C4`
PE256 | `7B5823CCE9EDE541ADA4A1881153D454CF6A0D45BD56C62F212B51CB88E53DCD`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\pwlauncher.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pwlauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/20bd575e31804c52d7edc3a6298aba504878d31df549d3fc82fe7a99ee9a966e/detection



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



MIT License. Copyright (c) 2020 Strontic.


