
# rdpsign.exe 

* File Path: `C:\Windows\SysWOW64\rdpsign.exe`
* Description: Remote Desktop Session Host Server Sign Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `893425A9B8F613870DA35D9B3C0F9654`
SHA1 | `FE6B724DF1297631ABA8CC26BF4A0910352BEC71`
SHA256 | `221ADD740903EE9B8C7B15D19B0B01909B790626A224FE575B76710BD636A58D`
SHA384 | `B65AD134C5AC9921F4E32CD6CD5F6E194373DE54682E9962928BAB24CBD36A4203FE9C39F61640964A245333B9492A9D`
SHA512 | `85D0491CE6583BA77E30FD1DCE6013ED4C4338B8AA5C7E4C8F69DC7164D1D7698BACF91A526F09C827099BB64943F0E808C7AFCB99D2EE77B1CDB7C13FF66F01`
SSDEEP | `1536:cdScOMkk5gL2j6WBxYIK5Pv8oIi7RR1qKxCidFv6:hZMkk5sm6WBKIORR1pxCiPy`

## Runtime Data

### Usage (stdout):
```Batchfile
All rdp file(s) have been succesfully signed.

```

### Usage (stderr):
```Batchfile
NAME

rdpsign [options] [items to sign]

OPTIONS

  /sha256 HASH
       Specified the SHA256 hash of the signing certificate.
  /q
       Quiet mode:  No output when success, minimal output when failed.
  /v
       Verbose mode:  Display all warnings, messages, and status.
  /l
       Test signing and output results without actually replacing any of the inputs.  Ignores when input files are on stdin.



```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSSignTool.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---
# rdpsign

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables you to digitally sign a Remote Desktop Protocol (.rdp) file.


> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

## Syntax
```
rdpsign /sha1 <hash> [/q | /v |] [/l] <file_name.rdp>
```

### Parameters

|Parameter|Description|
|-------|--------|
|/sha1 \<hash>|Specifies the thumbprint, which is the Secure Hash Algorithm 1 (SHA1) hash of the signing certificate that is included in the certificate store. Used in Windows Server 2012 R2 and older.|
|/sha256 \<hash>|Specifies the thumbprint, which is the Secure Hash Algorithm 256 (SHA256) hash of the signing certificate that is included in the certificate store. Replaces /sha1 in Windows Server 2016 and newer.|
|/q|Quiet mode. No output when the command succeeds and minimal output if the command fails.|
|/v|verbose mode. Displays all warnings, messages, and status.|
|/l|Tests the signing and output results without actually replacing any of the input files.|
|/?|Displays help at the command prompt.|

## Remarks
-   The SHA1 or SHA256 certificate thumbprint should represent a trusted .rdp file publisher. To obtain the certificate thumbprint, open the Certificates snap-in, double-click the certificate that you want to use (either in the local computer's certificates store or in your personal certificates store), click the **details** tab, and then in the **Field** list, click **Thumbprint**.

    > [!NOTE]
    > When you copy the thumbprint for use with the rdpsign.exe tool, you must remove any spaces.

-   You must specify the .rdp file (or files) to sign by using the full file name. Wildcard characters are not accepted.
-   The signed output files will overwrite the input files.
-   if any of the .rdp files cannot be read or written to, the tool will continue to the next file if multiple files are specified.

## <a name="BKMK_examples"></a>Examples
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


