---
title: msinfo32.exe | System Information
excerpt: What is msinfo32.exe?
---

# msinfo32.exe 

* File Path: `C:\Windows\SysWOW64\msinfo32.exe`
* Description: System Information

## Screenshot

![msinfo32.exe](screenshots/msinfo32.exe-41AA3C8C427A773B6C08460535EE8070-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `2D3773A656D92C8E4367511AD4DCDD8C`
SHA1 | `1EA1CA2B89A2AE6FA1C70922A40BFD5742CFE9C3`
SHA256 | `6860E80226EF8A8470B090A2969D834AB32D48B1821167628BB32B970A2DDE80`
SHA384 | `E5FD465C1879BAFD9F85463514FA962E3C5B6429400A3C3EBA7A626F4BCAF760159EB7AE925D6800C2BD816B753B90DA`
SHA512 | `4BDD31AA11D0A5CF14C3F40FA978FAD0B76E5081C5809C9F3DF856E686CE18DDB4D7F70B196061037548C4DAB65EA4FAF8031E2CCBE3303D79BB0F671BEAAE1D`
SSDEEP | `6144:wEiT2KFUUs3gcYKB6BUK07kc0ckcUkOnS58+SZEOHHrpm1XUZLxEZEOHHrpm1XUT:wEiT2Khs3gj8ZK07kc0ckcUky+OtLpmZ`

## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msinfo.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.351 (rs1_release_inmarket.161014-1755)
* Product Version: 10.0.14393.351
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Common Files\Microsoft Shared\MSInfo\msinfo32.exe](msinfo32.exe-5C49B7B55D4AF40DB1047E08484D6656.md) | 44
[C:\Program Files (x86)\Common Files\Microsoft Shared\MSInfo\msinfo32.exe](msinfo32.exe-E0A7B839C77497E01864479B70ACB5AE.md) | 49
[C:\Program Files (x86)\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-F589A0D3F0DA328F90A2A9556EF513B5.md) | 47
[C:\Program Files\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-0AED91DA63713BF9F881B03A604A1C9D.md) | 49
[C:\Program Files\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-238137CD0CD9CC74F361BEBD0178F0E6.md) | 50
[C:\Program Files\Common Files\microsoft shared\MSInfo\msinfo32.exe](msinfo32.exe-41AA3C8C427A773B6C08460535EE8070.md) | 57
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-0AED91DA63713BF9F881B03A604A1C9D.md) | 49
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-238137CD0CD9CC74F361BEBD0178F0E6.md) | 50
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-41AA3C8C427A773B6C08460535EE8070.md) | 57
[C:\WINDOWS\system32\msinfo32.exe](msinfo32.exe-429012FF95F4229B423BB4E322A62277.md) | 33
[C:\windows\system32\msinfo32.exe](msinfo32.exe-4BA6D7F9032FE80308C0501E087A54F6.md) | 54
[C:\WINDOWS\system32\msinfo32.exe](msinfo32.exe-CE97FD0E2556A49965411764F086CEA8.md) | 50
[C:\Windows\system32\msinfo32.exe](msinfo32.exe-DA35587758FC9C154435FB76C7183BE4.md) | 50
[C:\WINDOWS\SysWOW64\msinfo32.exe](msinfo32.exe-4A695CCD0B9FAD7D22BC66EA38CDF6CE.md) | 35
[C:\windows\SysWOW64\msinfo32.exe](msinfo32.exe-54E568D65C876CF31586CCE68F51DEEA.md) | 50
[C:\Windows\SysWOW64\msinfo32.exe](msinfo32.exe-5C49B7B55D4AF40DB1047E08484D6656.md) | 44
[C:\WINDOWS\SysWOW64\msinfo32.exe](msinfo32.exe-626E3EE8F3DDDA3F44E9E945C54F030D.md) | 50
[C:\Windows\SysWOW64\msinfo32.exe](msinfo32.exe-E0A7B839C77497E01864479B70ACB5AE.md) | 49
[C:\Windows\SysWOW64\msinfo32.exe](msinfo32.exe-F589A0D3F0DA328F90A2A9556EF513B5.md) | 47


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## msinfo32

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


