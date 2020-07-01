---
title: rdpsign.exe | Remote Desktop Session Host Server Sign Tool
---

# rdpsign.exe 

* File Path: `C:\windows\SysWOW64\rdpsign.exe`
* Description: Remote Desktop Session Host Server Sign Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FFD4F6214E18C050A465658F16CC303B`
SHA1 | `F3CCAFC9B42DE33FF8EB1AD9519225DD7857972A`
SHA256 | `18A0DEFB57E307A84FB497D096A7834AB6BA59D7683DCA00D99DBFAB64E5E2C4`
SHA384 | `B9C3556908E57DA160F370B36A706CC3B1ED32DD3BE397577B8FF64D1BB89CD7B734224E22325C0089AD6E76C284926F`
SHA512 | `5D1187971D9D263E27307AB3B9AC1938B9D9734AD7FA13228C3EB744971EF08B0AFC2E684D299826FCF83CA0B9B7FCA153571934E4941BE878E81318AE05CD20`
SSDEEP | `1536:+h87Z+sNlxXF4RuGuqqgP0uPAzrUjXfkr0QtsamYxvkz:+h8V+u14M/A0GXXfI0QuamYxMz`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\rdpsign.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


