---
title: pwlauncher.exe | Windows To Go Startup Options Command Line Tool
---

# pwlauncher.exe 

* File Path: `C:\Windows\system32\pwlauncher.exe`
* Description: Windows To Go Startup Options Command Line Tool

## Hashes

Type | Hash
-- | --
MD5 | `35972260DC0F61664C0945A3EC9AD701`
SHA1 | `F1B996C26273F29DA8C6CBCCA3E1EF020F2D3E31`
SHA256 | `C329F508D87B5BC8C791C2A9B6E261BFFEB49EEB3FA56821CD655926D01D2E5F`
SHA384 | `5DDE29C3801E3660566B787731A24FB4170ADC8ECC615F73816AFA1C6FC28F985C1CD9CE8A3FA38ED1011EE2BDDF6ED3`
SHA512 | `2F08280642493B9C06F3187CF8EB277CEFCE690AFFF6EABE7D3D246D0B7CF8C765C5C21F7FCEE9D1588BB33938483513D4149A5A9B1F9EA3C3B5DFD7E818D9CA`
SSDEEP | `768:w6xmObnETr16IoSdeLPSrznXkVKWh4ok+fL:XVEkIoSdQcznXkIWmok+fL`

## Runtime Data

### Usage (stdout):
```Batchfile
pwlauncher.exe - Windows To Go startup options command-line tool.

The pwlauncher.exe command-line tool is used to query or change your Windows To
Go startup options.

pwlauncher [/enable | /disable]

    <<no parameter>>    Display the current state.

    /enable             Enable the startup option.

    /disable            Disable the startup option.

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pwlauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


