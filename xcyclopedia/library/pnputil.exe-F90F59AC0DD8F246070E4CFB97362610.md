---
title: pnputil.exe | Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.
excerpt: What is pnputil.exe?
---

# pnputil.exe 

* File Path: `C:\Windows\system32\pnputil.exe`
* Description: Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.

## Hashes

Type | Hash
-- | --
MD5 | `F90F59AC0DD8F246070E4CFB97362610`
SHA1 | `18FEEFE0E5F5930C254E646177AA3E17DC5717C8`
SHA256 | `38F65CCC55E9C28BFB8E44A11A8295F3DD9F73DE29F67FF5E043F0BD5A2003EF`
SHA384 | `D8930B60C15FD69020462A15B2C1886820A084B2EC6401DCA12A86B58742A647A52A1D0066984E894DCA9C737F4878F3`
SHA512 | `3EC466E0CCB4302FFFEB7725560C38A67812EE58F930F7B937CB7744E002DE4A1494FE2DC1DC955C44EBCDF06CA627A19D742CCB622160A8F399178DFD15B32D`
SSDEEP | `3072:BCJDyM6Wz63GfINmCTfzAn6SFD4bJjgwQ+sJ6ZtAupdZppPsYtaLC:BCJDyM6WzBfINmccn6qxH78UY`
IMP | `77C66AA0A4495185A477C13839B45D00`
PESHA1 | `02A13D0EC2E66FAA2620485FAAA83A02B481FFEC`
PE256 | `4519624068417F62BE85012857D34B3F9BA9BCA350C30A3D66D41C2286B57773`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft PnP Utility

PNPUTIL [/add-driver <...> | /delete-driver <...> |
         /export-driver <...> | /enum-drivers | /?]

Commands:

  /add-driver <filename.inf | *.inf> [/subdirs] [/install] [/reboot]

    Add driver package(s) into the driver store.
      /subdirs - traverse sub directories for driver packages.
      /install - install/update drivers on any matching devices.
      /reboot - reboot system if needed to complete the operation.

  /delete-driver <oem#.inf> [/uninstall] [/force] [/reboot]

    Delete driver package from the driver store.
      /uninstall - uninstall driver package from any devices using it.
      /force - delete driver package even when it is in use by devices.
      /reboot - reboot system if needed to complete the operation.

  /export-driver <oem#.inf | *> <target directory>

    Export driver package(s) from the driver store into a target directory.

  /enum-drivers

    Enumerate all 3rd party driver packages in the driver store.

  /?

    Show this usage screen.

Legacy Commands:

  [-i] -a <filename.inf> ==> /add-driver <filename.inf> [/install]
  [-f] -d <oem#.inf>     ==> /delete-driver <oem#.inf> [/force]
  -e                     ==> /enum-drivers

Examples:

  pnputil /add-driver x:\driver.inf       <- Add driver package
  pnputil /add-driver c:\oem\*.inf        <- Add multiple driver packages
  pnputil /add-driver device.inf /install <- Add and install driver package
  pnputil /enum-drivers                   <- Enumerate OEM driver packages
  pnputil /delete-driver oem0.inf         <- Delete driver package
  pnputil /delete-driver oem1.inf /force  <- Force delete driver package
  pnputil /export-driver oem6.inf .       <- Export driver package
  pnputil /export-driver * c:\backup      <- Export all driver packages


```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pnputil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/38f65ccc55e9c28bfb8e44a11a8295f3dd9f73de29f67ff5e043f0bd5a2003ef/detection/


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


