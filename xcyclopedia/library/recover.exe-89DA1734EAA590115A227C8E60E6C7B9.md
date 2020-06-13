
# recover.exe 

* File Path: `C:\WINDOWS\SysWOW64\recover.exe`
* Description: Recover Files Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `89DA1734EAA590115A227C8E60E6C7B9`
SHA1 | `886C428C20A4AC98B8AE940FA56F211DB88A731D`
SHA256 | `E1E9C5AE4D6C5D0EACC305C9147FC34D72F616F8BC7866509D212F6401CF45C9`
SHA384 | `AB276CEB1F545E4F94535224037279798E831AB554B2D679335D302DE8A90A855062E4C94CC3182F9B87CA88C0950BC4`
SHA512 | `07E3F9C7FC1F010B51CE4D3381557348485D1BD431F8F575CE112A2D58F43CB1EDF43AC18A6EF268241017439B0CE55548A765ECA0040619B7CF30A9D6299DD1`
SSDEEP | `192:ziiU4v5m0us/ppTgY1Qqp8DNt2rYvk2TWlnWVMcSkt:z9jv5QCptgiQqp4212TWlnWacv`

## Runtime Data

### Usage (stdout):
```Batchfile
Access Denied as you do not have sufficient privileges or
the disk may be locked by another process.
You have to invoke this utility running in elevated mode
and make sure the disk is unlocked.

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

* Original Filename: Recover.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# recover



Recovers readable information from a bad or defective disk.



## Syntax

```
recover [<Drive>:][<Path>]<FileName>
```

### Parameters

|           Parameter           |                                          Description                                          |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| [\<Drive>:][<Path>]<FileName> | Specifies the location and name of the file that you want to recover. *FileName* is required. |
|              /?               |                             Displays help at the command prompt.                              |

## Remarks

-   The **recover** command reads a file, sector-by-sector, and recovers data from the good sectors. Data in bad sectors is lost.
-   Bad sectors reported by **chkdsk** were marked as bad when your disk was prepared for operation. They pose no danger, and **recover** does not affect them.
-   Because all data in bad sectors is lost when you recover a file, you should recover only one file at a time.
-   You cannot use wildcard characters (**&#42;** and **?**) with the **recover** command. You must specify a file (and the location of the file if it is not in the current directory).

## Examples

To recover the file Story.txt in the \Fiction directory on drive D, type:
```
recover d:\fiction\story.txt 
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


