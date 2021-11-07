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
MD5 | `A143EA998B2011E397CFE603F9D2C125`
SHA1 | `0E83DD7B28B049F9F7AF9242CE1C13DCE12E90E6`
SHA256 | `008E3EF11D666D456902B267C192AAA57ADC69CA9B6680C6136043695BE5644B`
SHA384 | `41910514FCC924E1196C5ACBC56CEF94407C2A7C704CA22B132AA6FA44F2373929A30AB4073E3EDCAC50CF791473A2AA`
SHA512 | `DFE5DFED947C927C133F57A57A6615C9B2D38CB629CA9DC3D690A16B6A69D5641BA6888DE63F6E6372DA65A8BF0ED8091CA387BB4971321E0BF0D8D7FF82117B`
SSDEEP | `3072:Ybgw6wspDHtZN01HaJ3i71XnlU/PfAEKJYqjSYCjPHHUAuSGdY5BbAXaH/Px:Ybf6wADHd09aJ3UXnlbVSjPHpt9A+`
IMP | `16667493AA19EF905772DBF54729674D`
PESHA1 | `E1A8ED19547D764660501D4B97FEE283B7998454`
PE256 | `366CA08F58262270978D3C0BE25DEA2EC5FF9EA15259DC2A9C8C8970815E155D`

## Runtime Data

### Usage (stdout):
```cmhg
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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/008e3ef11d666d456902b267c192aaa57adc69ca9b6680c6136043695be5644b/detection


## Possible Misuse

*The following table contains possible examples of `pnputil.exe` being misused. While `pnputil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `title: Suspicious Driver Install by pnputil.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `description: Detects when a possible suspicious driver is being installed via pnputil.exe lolbin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `- https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/pnputil-command-syntax`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `- https://strontic.github.io/xcyclopedia/library/pnputil.exe-60EDC5E6BDBAEE441F2E3AEACD0340D2.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `- '\pnputil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `- Pnputil.exe being used may be performed by a system administrator. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml) | `- Pnputil.exe being executed from unfamiliar users should be investigated. If known behavior is causing false positives, it can be exempted from the rule.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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


