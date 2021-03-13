---
title: pnputil.exe | Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.
excerpt: What is pnputil.exe?
---

# pnputil.exe 

* File Path: `C:\WINDOWS\system32\pnputil.exe`
* Description: Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.

## Hashes

Type | Hash
-- | --
MD5 | `B2DBA298A747802266E7DC6D1EA262E6`
SHA1 | `B2A0AE0404C964680EAD364E8B7C96D3802A3A0E`
SHA256 | `D9D80AAE27B350994D2917609B1944187B769DE4798F2BC0FF5FD1F58AF1DF19`
SHA384 | `AF4AE5D6A3712EAF16FD22187A7A0E694F88CF5A248DBF4D35F46746217270CC4527F90D380EB22D079F034020660F51`
SHA512 | `B0BFFAB0D39C44A5D51212729D3E6096BF4A3DAD06347202905A194DF05828A0BFB972CC4FBC630183D0A04197417646B56BA543EBE6BABA51ED72609A20A972`
SSDEEP | `3072:+JPjYKBwkkGb4WRKEzC8S7oainDvUqw8vbJCCguyAuShuboaG8aVubA:+ljYkkG5zrS3ia8v9n89GLu`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft PnP Utility

PNPUTIL [/add-driver <...> | /delete-driver <...> |
         /export-driver <...> | /enum-drivers |
         /enum-devices [<...>] | /enum-interfaces [<...>] | /?]

Commands:

  /add-driver <filename.inf | *.inf> [/subdirs] [/install] [/reboot]

    Add driver package(s) into the driver store.
      /subdirs - traverse sub directories for driver packages.
      /install - install/update drivers on any matching devices.
      /reboot - reboot system if needed to complete the operation.

    Examples:
      Add driver package:
        pnputil /add-driver x:\driver.inf
      Add multiple driver packages:
        pnputil /add-driver c:\oem\*.inf
      Add and install driver package:
        pnputil /add-driver device.inf /install

  /delete-driver <oem#.inf> [/uninstall] [/force] [/reboot]

    Delete driver package from the driver store.
      /uninstall - uninstall driver package from any devices using it.
      /force - delete driver package even when it is in use by devices.
      /reboot - reboot system if needed to complete the operation.

    Examples:
      Delete driver package:
        pnputil /delete-driver oem0.inf
      Force delete driver package:
        pnputil /delete-driver oem1.inf /force

  /export-driver <oem#.inf | *> <target directory>

    Export driver package(s) from the driver store into a target directory.

    Examples:
      Export driver package:
        pnputil /export-driver oem6.inf .
      Export all driver packages:
        pnputil /export-driver * c:\backup

  /enum-drivers

    Enumerate all 3rd party driver packages in the driver store.

    Examples:
      Enumerate all OEM driver packages:
        pnputil /enum-drivers

  /enum-devices [/connected | /disconnected] [/instanceid <instance ID>]
                [/class <name | GUID>] [/problem [<code>]] [/ids] [/relations]

    Enumerate all devices on the system.
      /connected | /disconnected - filter by connected devices or
                                   filter by disconnected devices.
      /instanceid <instance ID> - filter by device instance ID.
      /class <name | GUID> - filter by device class name or GUID.
      /problem [<code>] - filter by devices with problems or
                          filter by specific problem code.
      /ids - display hardware IDs and compatible IDs.
      /relations - display parent and child device relations.

    Examples:
      Enumerate only connected devices on the system:
        pnputil /enum-devices /connected
      Enumerate device with specific instance ID:
        pnputil /enum-devices /instanceid "ACPI\PNP0A08\1"
      Enumerate all devices with specific class:
        pnputil /enum-devices /class Display
        pnputil /enum-devices /class {00000000-0000-0000-0000-000000000000}
      Enumerate all devices with specific problem code:
        pnputil /enum-devices /problem 28
        pnputil /enum-devices /problem 0xA
      Enumerate all devices with problems and display hardware/compatible IDs:
        pnputil /enum-devices /problem /ids

  /enum-interfaces [/enabled | /disabled] [/class <GUID>]

    Enumerate all device interfaces on the system.
      /enabled | /disabled - filter by enabled interfaces or
                             filter by disabled interfaces.
      /class <GUID> - filter by interface class GUID.

    Examples:
      Enumerate only enabled interfaces on the system:
        pnputil /enum-interfaces /enabled
      Enumerate all interfaces with specific interface class GUID:
        pnputil /enum-interfaces /class {00000000-0000-0000-0000-000000000000}

  /?

    Show usage screen.


```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pnputil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `pnputil.exe` being misused. While `pnputil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pnputil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pnputil.yml) | `Name: Pnputil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pnputil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pnputil.yml) | `- Command: pnputil.exe -i -a C:\Users\hai\Desktop\mo.inf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pnputil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pnputil.yml) | `- Path: C:\Windows\system32\pnputil.exe`{:.highlight .language-yaml} | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## pnputil

Pnputil.exe is a command line utility that you can use to manage the driver store. You can use this command to add driver packages, remove driver packages, and list driver packages that are in the store.

### Syntax

```
pnputil.exe [-f | -i] [ -? | -a | -d | -e ] <INF name>
```

#### Parameters

| Parameter | Description |
|--|--|
| -a | Specifies to add the identified INF file. |
| -d | Specifies to delete the identified INF file. |
| -e | Specifies to enumerate all third-party INF files. |
| -f | Specifies to force the deletion of the identified INF file. Can't be used in conjunction with the **â€“i** parameter. |
| -i | Specifies to install the identified INF file. Can't be used in conjunction with  the **-f** parameter. |
| /? | Displays help at the command prompt. |

#### Examples

To add an INF file, named USBCAM.INF, type:

```
pnputil.exe -a a:\usbcam\USBCAM.INF
```

To add all INF files, located in c:\drivers, type:

```
pnputil.exe -a c:\drivers\*.inf
```

To add and install the USBCAM.INF driver, type:

```
pnputil.exe -i -a a:\usbcam\USBCAM.INF
```

To enumerate all third-party drivers, type:

```
pnputil.exe â€“e
```

To delete the INF file and driver named oem0.inf, type:

```
pnputil.exe -d oem0.inf
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [popd command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/popd.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


