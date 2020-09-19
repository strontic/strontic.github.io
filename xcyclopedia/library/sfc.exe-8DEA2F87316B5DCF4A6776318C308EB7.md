---
title: sfc.exe | System Integrity Check and Repair
---

# sfc.exe 

* File Path: `C:\Windows\system32\sfc.exe`
* Description: System Integrity Check and Repair

## Hashes

Type | Hash
-- | --
MD5 | `8DEA2F87316B5DCF4A6776318C308EB7`
SHA1 | `B351728CAE37E6418BD8EC5FB03AD541520F1825`
SHA256 | `BAF13CE3859FC727B767818B27262D549519870E6CCA5E960EEA266EB90E99C9`
SHA384 | `E9D6932430F1AED2E85A7A7D1651B9BF3BC0DB28E01087858AEC27ABD2F59F6C9D2590AD99551E90585E439F5F41FFB9`
SHA512 | `CE6669815C28D97E8D1C1911F07D6B23938A67D2FF038D7D32C1C98D379FC2F4832449DBFD61AFADEE121AACC82B7C7AE775CA519CBEF3FD22EF0F80941AF28D`
SSDEEP | `768:EIWuwKxUjiD7KCi3HsfVRzll5RQ9aHLedvYw9rD6zhiaSkPpzKYokcHG56Zk:BwCECVJ5C9ar49QiaRVKTHGEZk`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) Windows (R) Resource Checker Version 6.0
Copyright (C) Microsoft Corporation. All rights reserved.

Scans the integrity of all protected system files and replaces incorrect versions with 
correct Microsoft versions.

SFC [/SCANNOW] [/VERIFYONLY] [/SCANFILE=<file>] [/VERIFYFILE=<file>]
    [/OFFWINDIR=<offline windows directory> /OFFBOOTDIR=<offline boot directory> [/OFFLOGFILE=<log file path>]]

/SCANNOW        Scans integrity of all protected system files and repairs files with
                problems when possible.
/VERIFYONLY     Scans integrity of all protected system files. No repair operation is
                performed.
/SCANFILE       Scans integrity of the referenced file, repairs file if problems are
                identified. Specify full path <file>
/VERIFYFILE     Verifies the integrity of the file with full path <file>.  No repair
                operation is performed.
/OFFBOOTDIR     For offline repair, specify the location of the offline boot directory
/OFFWINDIR      For offline repair, specify the location of the offline windows directory
/OFFLOGFILE     For offline repair, optionally enable logging by specifying a log file path

e.g.

        sfc /SCANNOW
        sfc /VERIFYFILE=c:\windows\system32\kernel32.dll
        sfc /SCANFILE=d:\windows\system32\kernel32.dll /OFFBOOTDIR=d:\ /OFFWINDIR=d:\windows
        sfc /SCANFILE=d:\windows\system32\kernel32.dll /OFFBOOTDIR=d:\ /OFFWINDIR=d:\windows /OFFLOGFILE=c:\log.txt
        sfc /VERIFYONLY

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sfc.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sfc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sfc.exe` being misused. While `sfc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | 		$s4 = "\\sfc.exe" fullword ascii /* score: '11.005' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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


