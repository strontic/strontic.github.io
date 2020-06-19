
# sfc.exe 

* File Path: `C:\WINDOWS\system32\sfc.exe`
* Description: System Integrity Check and Repair
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C297C70EF04FE6E2F27B9285530E8100`
SHA1 | `03915B474A8C2C78C83A3C009BA1923FCFA99FDE`
SHA256 | `786D3CB14F160E4795690F198278424648E3973DFF9CA86317658714406CAD87`
SHA384 | `E35548E61EC2DC3C5AA27126B7854C696AEDEF8CB8615159049A58AA114F4C6C82790B1E18AD9E27962B1B0673DF9FA9`
SHA512 | `B72F8D6859A6CD472067C8197C6B61B7D003D67B577C4B0979179A8DC04DA10051A24BF7BCBCABD5479F6885C697D14E26E5E1BCE8226785682F23614297A0A6`
SSDEEP | `768:rqb1u94qTNIJ735pceeGklnbG5cVsmSWuRavKSgjEjJpO3J9Hn3GxZ56:409kjiNnb2XRaiSgXj3G756`

## Runtime Data

### Usage (stdout):
```Batchfile

You must be an administrator running a console session in order to 
use the sfc utility.

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

* Original Filename: sfc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


