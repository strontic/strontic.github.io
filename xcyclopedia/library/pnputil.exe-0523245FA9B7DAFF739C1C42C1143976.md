---
title: pnputil.exe | Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.
---

# pnputil.exe 

* File Path: `C:\Windows\system32\pnputil.exe`
* Description: Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.

## Hashes

Type | Hash
-- | --
MD5 | `0523245FA9B7DAFF739C1C42C1143976`
SHA1 | `7D0BCA01EE1FD0D07D8A35AA5A31973E536B760E`
SHA256 | `D11EA7611A503979C30531EB7F8E5C6F75C874B09B590F8F6B12DA84F6272FA2`
SHA384 | `50051D98545E13E126195FC2AA802A731718C143416C645E7C6FA928BD3194801F11547A25207529D195FA68A30B6848`
SHA512 | `C3CB23AC0C8F5DB03E82E78B7D7DA8DE134729D5F3DFE6CD9CC8CE82602E247EFB165251BC4CD6E8146C783228B3AF161E8D223250DEE5BD4E4189EFA24FDF13`
SSDEEP | `3072:0NW1s+CH73jzcN0VF87uLdqsLFuxV8tNcGTptemDEi6Khwayrn:K4s+Cb3V87uLUTuNnZ6c`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft PnP Utility

PNPUTIL [/add-driver <...> | /delete-driver <...> |
         /export-driver <...> | /enum-drivers | /?]

Commands:

  /add-driver <filename.inf | *.inf> [/subdirs] [/install]

    Add driver package(s) into the driver store.
      /subdirs - traverse sub directories for driver packages.
      /install - install/update drivers on any matching devices.

  /delete-driver <oem#.inf> [/force]

    Delete driver package from the driver store.
      /force - delete driver package even when it is in use by devices.

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

* Original Filename: pnputil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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



MIT License. Copyright (c) 2020 Strontic.


