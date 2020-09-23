---
title: sfc.exe | System Integrity Check and Repair
excerpt: What is sfc.exe?
---

# sfc.exe 

* File Path: `C:\windows\SysWOW64\sfc.exe`
* Description: System Integrity Check and Repair

## Hashes

Type | Hash
-- | --
MD5 | `A7424D3F969DF63145BB317D2167101E`
SHA1 | `78BABE98BC4BA57C8D8E98F1414F8779EB7BD20C`
SHA256 | `17EFB7CA5F719D6A8C08791C355CAECAF77B29B02383BC8BADF078E086A0ACC8`
SHA384 | `F5AD0EA23D995596F18C83BD5E18C95127DB0C1B51D694A0D4395F10793ECB5F703C0B3DF43C7E473D4AC7C563979BC2`
SHA512 | `602B722943CF8627DAB77751FE26DEC995593EA9C4DA817263FF27875A4964826A9D7464456285F494B2BDCEB7A4E93EB9DCFAAB2C62C472BEB6248C0509DABB`
SSDEEP | `768:QpTlBpVdFfxFQzCLEsR96FbvJzYDfIU2559:gH9hgbpWgU2559`

## Signature

* Status: The file C:\windows\SysWOW64\sfc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sfc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `sfc.exe` being misused. While `sfc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s4 = "\\sfc.exe" fullword ascii /* score: '11.005' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## sfc

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Scans and verifies the integrity of all protected system files and replaces incorrect versions with correct versions.


### Syntax
```
sfc [/scannow] [/verifyonly] [/scanfile=<file>] [/verifyfile=<file>] [/offwindir=<offline windows directory> /offbootdir=<offline boot directory>]
```

##### Parameters
|Parameter|Description|
|-------|--------|
|/scannow|Scans the integrity of all protected system files and repairs files with problems when possible.|
|/verifyonly|Scans integrity of all protected system files. No repair operation is performed.|
|/scanfile|Scans integrity of the specified file and repairs the file if problems are detected, when possible.|
|\<file>|Specified full path and filename|
|/verifyfile|verifies the integrity of the specified file. No repair operation is performed.|
|/offwindir|Specifies the location of the offline windows directory, for offline repair.|
|/offbootdir|Specifies the location of the offline boot directory for offline|
|/?|Displays help at the command prompt.|

### Remarks
-   You must be logged on as a member of the Administrators group to run **sfc.exe**.
-   if **sfc** discovers that a protected file has been overwritten, it retrieves the correct version of the file from the **systemroot\system32\dllcache** folder, and then replaces the incorrect file.
-   There are functional differences between **sfc** on Windows Server  2003,  Windows Server  2008 , and  Windows Server  2008 R2 :
-   for more information about **sfc** on Windows Server 2003, see [article 310747](https://go.microsoft.com/fwlink/?LinkId=227069) in the Microsoft Knowledge Base.
-   for more information about **sfc** on  Windows Server  2008 , and  Windows Server  2008 R2 , see [System File Checker](https://go.microsoft.com/fwlink/?LinkId=227071).

### Examples
To verify the **kernel32.dll file**, type:
```
sfc /verifyfile=c:\windows\system32\kernel32.dll
```
To setup offline repair of the **kernel32.dll** file with an offline boot directory set to **d:** and offline windows directory set to **d:\windows**, type:
```
sfc /scanfile=d:\windows\system32\kernel32.dll /offbootdir=d:\ /offwindir=d:\windows
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)


---



MIT License. Copyright (c) 2020 Strontic.


