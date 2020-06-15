
# recover.exe 

* File Path: `C:\Windows\system32\recover.exe`
* Description: Recover Files Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EEE30874AB672B5950F24ABB45841992`
SHA1 | `4BB89260CA0CFC695FB55EB9402129E41E131F60`
SHA256 | `4696EFE7AB6648628FE6BFC5BA47335D33B8108C9919887E99194A1F3CEEEA92`
SHA384 | `69C162A3841F88DF7D8B01CE5807A8A7E3B54D3196F59EBA95A818E0421A1C979290BA17108A887B4A02DAD1DCCEFDE6`
SHA512 | `A759A17DD97CCF7C645E765D692E8E6323D4C00F043974AC3F6F785459EC0D9F9A0876DE7A19FA51B0BBF6B171D8E7E3D7B70FD51955018D6DFD4388D8A8554D`
SSDEEP | `192:LkWSS0p+GgpEEKspPvd/utlTA4zkmiVa40gJuB5IG1019Rxm2LWLnWr:QWSt+FpEJsX/u7VgmaNnm6uR2LWLnW`

## Runtime Data

### Usage (stdout):
```Batchfile
Recovers readable information from a bad or defective disk.

RECOVER [drive:][path]filename
Consult the online Command Reference in Windows Help
before using the RECOVER command.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Recover.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\recover.exe](recover.exe-D1B908D88FB9EEA82933DB365D398FDD.md) | 29


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

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


