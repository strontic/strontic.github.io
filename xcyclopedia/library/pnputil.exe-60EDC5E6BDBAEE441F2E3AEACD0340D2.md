---
title: pnputil.exe | Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.
---

# pnputil.exe 

* File Path: `C:\Windows\system32\pnputil.exe`
* Description: Microsoft PnP Utility - Tool to add, delete, export, and enumerate driver packages.

## Hashes

Type | Hash
-- | --
MD5 | `60EDC5E6BDBAEE441F2E3AEACD0340D2`
SHA1 | `B00E025A7B9B94EA59358E0C543522461CCFCC85`
SHA256 | `25EFA393011172FBDEDB60B362C82DD5B026B9EDFACCAC77AD4C60DB1E1E79C6`
SHA384 | `7ED7121DBBC16D5E0852A2E14031437CCCC6193D27DD8FB36ABAC47763E2DCA010D27F6EA4A2A2DB50C2C9F953E14F90`
SHA512 | `65ACBDB36FF96D62CE8F1D0073981D442758850A10E3BBF0EB024C25C5B1E8E4943C6CB60F4F200D1C438A0BC79634B1DE9B39DCA07F1C4FD709936C39828F71`
SSDEEP | `3072:JbAQqwEJjHN2N7191mTiQxXoUXsvfK/pgS/FHHrAuSGHZpzrqAXaG/3yy:Jbfqw4jHg7z1mTHXoUjiSVHsiKA9`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft PnP Utility

PNPUTIL [/add-driver <...> | /delete-driver <...> |
         /export-driver <...> | /enum-drivers |
         /enum-devices [<...>] | /enum-interfaces [<...>] |
         /disable-device <...> | /enable-device <...> |
         /restart-device <...> | /remove-device <...> |
         /scan-devices [<...>] | /?]

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

  /disable-device <instance ID> [/reboot]

    Disable devices on the system.
      /reboot - reboot system if needed to complete the operation.

    Examples:
      Disable device:
        pnputil /disable-device "USB\VID_045E&PID_00DB\6&870CE29&0&1"

  /enable-device <instance ID> [/reboot]

    Enable devices on the system.
      /reboot - reboot system if needed to complete the operation.

    Examples:
      Enable device:
        pnputil /enable-device "USB\VID_045E&PID_00DB\6&870CE29&0&1"

  /restart-device <instance ID> [/reboot]

    Restart devices on the system.
      /reboot - reboot system if needed to complete the operation.

    Examples:
      Restart device:
        pnputil /restart-device "USB\VID_045E&PID_00DB\6&870CE29&0&1"

  /remove-device <instance ID> [/subtree] [/reboot]

    Attempt to remove a device from the system.
      /subtree - remove entire device subtree, including any child devices.
      /reboot - reboot system if needed to complete the operation.

    Examples:
      Remove device:
        pnputil /remove-device "USB\VID_045E&PID_00DB\6&870CE29&0&1"

  /scan-devices [/instanceid <instance ID>] [/async]

    Scan the system for any device hardware changes.
      /instanceid <instance ID> - scan device subtree for changes.
      /async - scan for changes asynchronously.

    Examples:
      Scan devices:
        pnputil /scan-devices

  /enum-devices [/connected | /disconnected] [/instanceid <instance ID>]
                [/class <name | GUID>] [/problem [<code>]] [/ids] [/relations]
                [/drivers]

    Enumerate all devices on the system.
      /connected | /disconnected - filter by connected devices or
                                   filter by disconnected devices.
      /instanceid <instance ID> - filter by device instance ID.
      /class <name | GUID> - filter by device class name or GUID.
      /problem [<code>] - filter by devices with problems or
                          filter by specific problem code.
      /ids - display hardware IDs and compatible IDs.
      /relations - display parent and child device relations.
      /drivers - display matching and installed drivers.

    Examples:
      Enumerate only connected devices on the system:
        pnputil /enum-devices /connected
      Enumerate device with specific instance ID:
        pnputil /enum-devices /instanceid "ACPI\PNP0A08\1"
      Enumerate all devices with specific class:
        pnputil /enum-devices /class Display
        pnputil /enum-devices /class {4d36e97d-e325-11ce-bfc1-08002be10318}
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
        pnputil /enum-interfaces /class {884b96c3-56ef-11d1-bc8c-00a0c91405dd}

  /?

    Show usage screen.


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\pnputil.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pnputil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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


