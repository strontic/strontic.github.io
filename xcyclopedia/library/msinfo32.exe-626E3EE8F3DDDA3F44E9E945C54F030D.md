
# msinfo32.exe 

* File Path: `C:\WINDOWS\SysWOW64\msinfo32.exe`
* Description: System Information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `626E3EE8F3DDDA3F44E9E945C54F030D`
SHA1 | `38678C4AEE8B9B24D98F5677D111D40F9C1CF6EC`
SHA256 | `B09193EBC6F828035A5C712CB804B0D60BCECCFDCC86674B9EE95A2EA9507F5A`
SHA384 | `7725C9A7EB7E9D93D3C282524FBA8BADB545D37875D9EE478D29B53B11A9BDFD43A66DCA339C54BA5905AF1796FE6276`
SHA512 | `E44A641122ED6E708F2A1AB867C421BD2026A0B72A66250134BBE1B5F9399D6506D07260DA6BE5E47B08F44C1C8577A58934B793A59B8443192B4B96F4C5A7A8`
SSDEEP | `6144:Jaq0Jr2rk3LZ6FWszl7TxKhph5hphba31oQmSZEOHHrpm1XUZLxEZEOHHrpm1XUK:JaqACwkF357TxKhph5hphba31QOtLpmw`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msinfo.dll
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


