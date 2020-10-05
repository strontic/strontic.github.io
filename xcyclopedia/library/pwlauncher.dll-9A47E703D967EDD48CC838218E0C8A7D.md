---
title: pwlauncher.dll | Windows To Go Launcher
excerpt: What is pwlauncher.dll?
---

# pwlauncher.dll 

* File Path: `C:\Windows\system32\pwlauncher.dll`
* Description: Windows To Go Launcher

## Hashes

Type | Hash
-- | --
MD5 | `9A47E703D967EDD48CC838218E0C8A7D`
SHA1 | `4827E775F4CAA27FD91C87BE8304967CCDB92411`
SHA256 | `5F0F9AD9391B6EFE90075BD618D14FE3E53CCE95A1B612E98139BFBD5D9697DB`
SHA384 | `0E31EED1756D85C9E78374ADFB084D8571285C1ADD72A0651A2E156B8A09F48EA2FABB9755C7F85AD1AE276A62BABD06`
SHA512 | `4C530A6F9AE38D50B5C67F730B91598E6CD543632B32CFD55318C09D308A91A3CEDBDFA8A1841957C687199145C3F74F45EF3606C42654E6D2B88E98A0A8E675`
SSDEEP | `3072:sfG7pIA8AqyrpZqGk943+5MAJbfYkicuRV3RassB+MkncTlMRk:V7pIA8AqyrpZqGBIbbicIEsSLUcTlWk`
IMP | `5FD2EC086E8894717EB2C87419CA9642`
PESHA1 | `1C81ACEF6D29FDC934BD907483B2267FDE827576`
PE256 | `BBCFFBB34C391827EA1D582D51E4A4EF1349FB657CB6C5A4DE6302718A3031FD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ProcessHibernateGroupPolicy` | 3 | Exported Function
`DllUnregisterServer` | 8 | Exported Function
`ShowPortableWorkspaceLauncherConfigurationUX` | 1 | Exported Function
`ProcessLauncherGroupPolicy` | 2 | Exported Function
`DllGetClassObject` | 5 | Exported Function
`DllCanUnloadNow` | 4 | Exported Function
`DllRegisterServer` | 7 | Exported Function
`DllInstall` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pwlauncher.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/5f0f9ad9391b6efe90075bd618d14fe3e53cce95a1b612e98139bfbd5d9697db/detection/



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


