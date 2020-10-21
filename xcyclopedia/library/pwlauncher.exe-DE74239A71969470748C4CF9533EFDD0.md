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
MD5 | `DE74239A71969470748C4CF9533EFDD0`
SHA1 | `5E6C3E0FBA13176D3D88896E81317D9B78C00508`
SHA256 | `1C8227150762B47731DD6B99304D3E5647824F9C1B4D7FB8CD755B29F00BC93B`
SHA384 | `46A8F73B6C84A69E78BFB48EBAD8ED43BB0E82D509B4EFF3CEC9298514587A3D8556D590C10E5AFF83E0629DB8DD08BA`
SHA512 | `1449119C19C96DB045A3A0DBA69A79CF74DAB6B98E66927D16D4EECF957CE99CCA743D963CCB80E950B2781F6F051A2C8CF6F4ABD9B96415CD039F0D0D66411C`
SSDEEP | `768:74VleU0Q2RiX8nuVGqQd2Ej2FNkY4EABbnLM8mWP/:UV2wCiEaFNkYU5nLNmWH`
IMP | `10E2E3C83FAD470F2219B3E8C8A1881E`
PESHA1 | `9790A47BE9FE62EEB32B14B0F7CA115CCD933622`
PE256 | `72580C513B1637AF431B34D2F91A3894DF9D444815B54F4402514B4B45B7E55D`

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
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\system32\pwlauncher.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pwlauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1c8227150762b47731dd6b99304d3e5647824f9c1b4d7fb8cd755b29f00bc93b/detection/



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


