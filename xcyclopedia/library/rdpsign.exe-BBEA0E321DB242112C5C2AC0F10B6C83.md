---
title: rdpsign.exe | Remote Desktop Session Host Server Sign Tool
---

# rdpsign.exe 

* File Path: `C:\windows\system32\rdpsign.exe`
* Description: Remote Desktop Session Host Server Sign Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `BBEA0E321DB242112C5C2AC0F10B6C83`
SHA1 | `C64BE57FA7B2CE13A43590C1101BBE997A5CDE31`
SHA256 | `89412D995DFECD94256BF93978A02D0B4D349461FA9B5E0376B1928D482A1E42`
SHA384 | `6935B8BFFCDF5936E1CA41DDEA6620559DF6B5C8DCC4D7A0D3311094FBCCEA77C07639223B01B0C8A8BCB2310D65F19D`
SHA512 | `0B14EDC6CEC0B211A1A2AD45614EEDFD53DF3EB6256B963CFC346AC9F7937FB5ED21F2FC75B084359947EAED53AD98A0924B37E60AB968FD3F57A4A8C066B97B`
SSDEEP | `1536:Nz864NbAFyw/RAI/gz+PYkiOCbg/4CPJclm4az3DI5z5:Nz8pC7Rlozjkih4muAz5`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\rdpsign.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: TSSignTool.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## rdpsign

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables you to digitally sign a Remote Desktop Protocol (.rdp) file.


> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

### Syntax
```
rdpsign /sha1 <hash> [/q | /v |] [/l] <file_name.rdp>
```

#### Parameters

|Parameter|Description|
|-------|--------|
|/sha1 \<hash>|Specifies the thumbprint, which is the Secure Hash Algorithm 1 (SHA1) hash of the signing certificate that is included in the certificate store. Used in Windows Server 2012 R2 and older.|
|/sha256 \<hash>|Specifies the thumbprint, which is the Secure Hash Algorithm 256 (SHA256) hash of the signing certificate that is included in the certificate store. Replaces /sha1 in Windows Server 2016 and newer.|
|/q|Quiet mode. No output when the command succeeds and minimal output if the command fails.|
|/v|verbose mode. Displays all warnings, messages, and status.|
|/l|Tests the signing and output results without actually replacing any of the input files.|
|/?|Displays help at the command prompt.|

### Remarks
-   The SHA1 or SHA256 certificate thumbprint should represent a trusted .rdp file publisher. To obtain the certificate thumbprint, open the Certificates snap-in, double-click the certificate that you want to use (either in the local computer's certificates store or in your personal certificates store), click the **details** tab, and then in the **Field** list, click **Thumbprint**.

    > [!NOTE]
    > When you copy the thumbprint for use with the rdpsign.exe tool, you must remove any spaces.

-   You must specify the .rdp file (or files) to sign by using the full file name. Wildcard characters are not accepted.
-   The signed output files will overwrite the input files.
-   if any of the .rdp files cannot be read or written to, the tool will continue to the next file if multiple files are specified.

### <a name="BKMK_examples"></a>Examples
- To sign an .rdp file that is named File1.rdp, navigate to the folder where you saved the .rdp file, and then type the following:
  ```
  rdpsign /sha1 hash file1.rdp
  ```
  > [!NOTE]
  > The *hash* value represents the SHA1 certificate thumbprint, without any spaces.
- To test whether digital signing will succeed for an .rdp file without actually signing the file, type the following:
  ```
  rdpsign /sha1 hash /l file1.rdp
  ```
- To sign multiple .rdp files, separate the file names by using spaces. For example, to sign multiple .rdp files that are named File1.rdp, File2.rdp, and File3.rdp, type the following:
  ```
  rdpsign /sha1 hash file1.rdp file2.rdp file3.rdp
  ```
  ## See Also
  - [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)
  [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


