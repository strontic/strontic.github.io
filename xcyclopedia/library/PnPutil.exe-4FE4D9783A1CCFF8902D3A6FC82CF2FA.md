---
title: PnPutil.exe | Microsoft PnP Utility - Tool to add, delete and enumerate driver packages.
excerpt: What is PnPutil.exe?
---

# PnPutil.exe 

* File Path: `C:\windows\system32\PnPutil.exe`
* Description: Microsoft PnP Utility - Tool to add, delete and enumerate driver packages.

## Hashes

Type | Hash
-- | --
MD5 | `4FE4D9783A1CCFF8902D3A6FC82CF2FA`
SHA1 | `E95BC7453DB0BBCDEA01370F462C2FE83616929D`
SHA256 | `47DDC47F579CDF2AFCD1FE1FA1FA4241746775273CF82BFF02388E20AEC1554A`
SHA384 | `8E3C8A2124E5B68FA40AE88171B6ED3E5A7DE250A5AFD6A5A97F5FAB26EE7D1307FA483FC51181F242358F5029D8D987`
SHA512 | `B77EEA4FFB63001D91A6565A18003EE66726E84CE3FDD6016045F9CB45E1F20E4D50AC005FFDC39F61E171BF838E6AA3834C88586ECCB386DE73CF7514A29E2B`
SSDEEP | `384:4J3e7GlAaLCPQwEyhD5yssigbB1yXdbg7sGPT/evOKE/WR8vW:c3kzwssigb4GSvOKEh`

## Signature

* Status: The file C:\windows\system32\PnPutil.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: PnPutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `PnPutil.exe` being misused. While `PnPutil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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


