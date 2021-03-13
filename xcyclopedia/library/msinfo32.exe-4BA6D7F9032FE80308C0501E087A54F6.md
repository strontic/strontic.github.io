---
title: msinfo32.exe | System Information
excerpt: What is msinfo32.exe?
---

# msinfo32.exe 

* File Path: `C:\windows\system32\msinfo32.exe`
* Description: System Information

## Screenshot

![msinfo32.exe](screenshots/msinfo32.exe-41AA3C8C427A773B6C08460535EE8070-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `4BA6D7F9032FE80308C0501E087A54F6`
SHA1 | `CAB05A3DC00EAE14BBBDB1F7AA60E0132157220C`
SHA256 | `9B468BC8C55A8CFF66DDA42C5A25A0A3E4915536887B8F489DE59DB87703C3D9`
SHA384 | `9F7735C2C941CB47F4F5CCED4A2A89B9C44D06B14DB8697AD65D0C25F1AE63A5687FAAB81A52CC59D6BEE0C19844182E`
SHA512 | `45A7602EF497BDACC3CB4841EB6709BC81CEC831E59A9BD09E6D99CEF0F6620D81BD7466A4678094C19A08F4B833B51424949255E3B27F7753D89A2A454F3C13`
SSDEEP | `6144:+c1dmdmeFBILP5Zk7imi0ZEOHHrpm1XUZLxEZEOHHrpm1XUZLx:+cSmW2L07s8tLpm1EwtLpm1E`

## Signature

* Status: The file C:\windows\system32\msinfo32.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: msinfo.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Common Files\Microsoft Shared\MSInfo\msinfo32.exe](msinfo32.exe-E0A7B839C77497E01864479B70ACB5AE.md) | 57
[C:\Program Files (x86)\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-F589A0D3F0DA328F90A2A9556EF513B5.md) | 61
[C:\Program Files\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-238137CD0CD9CC74F361BEBD0178F0E6.md) | 63
[C:\Program Files\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-41AA3C8C427A773B6C08460535EE8070.md) | 69
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-238137CD0CD9CC74F361BEBD0178F0E6.md) | 63
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-41AA3C8C427A773B6C08460535EE8070.md) | 69
[C:\WINDOWS\system32\msinfo32.exe](msinfo32.exe-CE97FD0E2556A49965411764F086CEA8.md) | 60
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-DA35587758FC9C154435FB76C7183BE4.md) | 61
[C:\Windows\SysWOW64\msinfo32.exe](msinfo32.exe-2D3773A656D92C8E4367511AD4DCDD8C.md) | 54
[C:\windows\SysWOW64\msinfo32.exe](msinfo32.exe-54E568D65C876CF31586CCE68F51DEEA.md) | 65
[C:\WINDOWS\SysWOW64\msinfo32.exe](msinfo32.exe-626E3EE8F3DDDA3F44E9E945C54F030D.md) | 54
[C:\Windows\SysWOW64\msinfo32.exe](msinfo32.exe-E0A7B839C77497E01864479B70ACB5AE.md) | 57
[C:\Windows\SysWOW64\msinfo32.exe](msinfo32.exe-F589A0D3F0DA328F90A2A9556EF513B5.md) | 61


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## msinfo32

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Opens the System Information tool to display a comprehensive view of the hardware, system components, and software environment on the local computer.

Some System Information categories contain large amounts of data. You can use the **start /wait** command to optimize reporting performance for these categories. For more information, see [System Information](/previous-versions/windows/it-pro/windows-server-2003/cc783305(v=ws.10)).

### Syntax

```
msinfo32 [/pch] [/nfo <path>] [/report <path>] [/computer <computername>] [/showcategories] [/category <categoryID>] [/categories {+<categoryID>(+<categoryID>)|+all(-<categoryID>)}]
```

#### Parameters

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

#### Examples

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

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


