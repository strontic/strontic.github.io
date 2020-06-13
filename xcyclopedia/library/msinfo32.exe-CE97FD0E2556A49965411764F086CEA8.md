
# msinfo32.exe 

* File Path: `C:\WINDOWS\system32\msinfo32.exe`
* Description: System Information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CE97FD0E2556A49965411764F086CEA8`
SHA1 | `D6B32910CBBE1DB8401E33DC50E45D9E9F6296FB`
SHA256 | `1FDA48C3353D7837C2CA986D0F79CB6D615BD95CEE37F50F8CD9F28D1731E66C`
SHA384 | `59A4977C3061C7B9C03172AC1CDD1526889B2D9AB40B2EA081F692717ED01D3D82D48F63F7E3E11BC5DDA098235082E5`
SHA512 | `67C1D029825788983328440D101B2AA8E011C4CD279341B85AFE458E6C2F7715AB25E312790F989B8A0DE441D391BEC41051E8FF5BF4AC3FDE6EDF2D5F38BAAB`
SSDEEP | `6144:ApS7G6IHuv0o5KXcSK27WjWzPKRw/2ZEOHHrpm1XUZLxEZEOHHrpm1XUZLx:sSnX5KBByjKx/atLpm1EwtLpm1E`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msinfo.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# msinfo32

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Opens the System Information tool to display a comprehensive view of the hardware, system components, and software environment on the local computer.

Some System Information categories contain large amounts of data. You can use the **start /wait** command to optimize reporting performance for these categories. For more information, see [System Information](https://technet.microsoft.com/library/cc783305(v=ws.10).aspx).

## Syntax

```
msinfo32 [/pch] [/nfo <path>] [/report <path>] [/computer <computername>] [/showcategories] [/category <categoryID>] [/categories {+<categoryID>(+<categoryID>)|+all(-<categoryID>)}]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<path>` | Specifies the file to be opened in the format *C:\Folder1\File1.xxx*, where *C* is the drive letter, *Folder1* is the folder, *File1* is the file name, and *xxx* is the file name extension.<p>This file can be an **.nfo**, **.xml**, **.txt**, or **.cab** file. |
| `<computername>` | Specifies the name of the target or local computer. This can be a UNC name, an IP address, or a full computer name. |
| `<categoryID>` | Specifies the ID of the category item. You can obtain the category ID by using **/showcategories**. |
| /pch | Displays the System History view in the System Information tool. |
| /nfo | Saves the exported file as an **.nfo** file. If the file name that is specified in *path* does not end in an **.nfo** extension, the **.nfo** extension is automatically appended to the file name. |
| /report | Saves the file in *path* as a text file. The file name is saved exactly as it appears in *path*. The .txt extension is not appended to the file unless it is specified in path. |
| /computer | Starts the System Information tool for the specified remote computer. You must have the appropriate permissions to access the remote computer. |
| /showcategories | Starts the System Information tool with all available category IDs displayed, rather than displaying the friendly or localized names. For example, the Software Environment category is displayed as the **SWEnv** category. |
| /category | Starts System Information with the specified category selected. Use **/showcategories** to display a list of available category IDs. |
| /categories | Starts System Information with only the specified category or categories displayed. It also limits the output to the selected category or categories. Use **/showcategories** to display a list of available category IDs. |
| /? | Displays help at the command prompt. |

### Examples

To list the available category IDs, type:

```
msinfo32 /showcategories
```

To start the System Information tool with all available information displayed, except Loaded Modules, type:

```
msinfo32 /categories +all -loadedmodules
```

To display **System Summary** information and to create an .nfo file called *syssum.nfo*, which contains information in the **System Summary** category, type:

```
msinfo32 /nfo syssum.nfo /categories +systemsummary
```

To display resource conflict information and to create an .nfo file called *conflicts.nfo*, which contains information about resource conflicts, type:

```
msinfo32 /nfo conflicts.nfo /categories +componentsproblemdevices+resourcesconflicts+resourcesforcedhardware
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


