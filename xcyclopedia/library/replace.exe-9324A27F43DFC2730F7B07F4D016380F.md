
# replace.exe 

* File Path: `C:\Windows\system32\replace.exe`
* Description: Replace File Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9324A27F43DFC2730F7B07F4D016380F`
SHA1 | `362BBD4F661353AE0F7F2AA50953A77405C24664`
SHA256 | `CE49C1D7DC7CBD541D1B49A868E40FB8A3D4A5E6B2A2387357C3960E01BE82B5`
SHA384 | `C833C38E83C0C89AD22C6C3470E6DF6E6BB7A4747E2C379A95829C92D7A4114CF182DB3B33024A1A3D09B503659F2D78`
SHA512 | `FD802AC289A18D974F1D7CB747C3200364F0A0BC943AE9DEB058484A079B83F0C7AF62AC45C2A60310B4016B71127DE5A2D0CE738620D032AE589D61979F7075`
SSDEEP | `384:IM4UBCd83UMtmHiijohrHntRxggu/W4mnmXgyA9l+VWFh/W:rbkM0ljo1bxgY4amnASs`

## Runtime Data

### Usage (stdout):
```Batchfile
Replaces files.

REPLACE [drive1:][path1]filename [drive2:][path2] [/A] [/P] [/R] [/W]
REPLACE [drive1:][path1]filename [drive2:][path2] [/P] [/R] [/S] [/W] [/U]

  [drive1:][path1]filename Specifies the source file or files.
  [drive2:][path2]         Specifies the directory where files are to be
                           replaced.
  /A                       Adds new files to destination directory. Cannot
                           use with /S or /U switches.
  /P                       Prompts for confirmation before replacing a file or
                           adding a source file.
  /R                       Replaces read-only files as well as unprotected
                           files.
  /S                       Replaces files in all subdirectories of the
                           destination directory. Cannot use with the /A
                           switch.
  /W                       Waits for you to insert a disk before beginning.
  /U                       Replaces (updates) only files that are older than
                           source files. Cannot use with the /A switch.

```

### Usage (stderr):
```Batchfile
Invalid switch - -help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REPLACE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# replace



Replaces files. If used with the **/a** option, **replace** adds new files to a directory instead of replacing existing files.



## Syntax

```
replace [<Drive1>:][<Path1>]<FileName> [<Drive2>:][<Path2>] [/a] [/p] [/r] [/w] 
replace [<Drive1>:][<Path1>]<FileName> [<Drive2>:][<Path2>] [/p] [/r] [/s] [/w] [/u] 
```

### Parameters

|Parameter|Description|
|---------|-----------|
|[\<Drive1>:][\<Path1>]\<FileName>|Specifies the location and name of the source file or set of files. *FileName* is required, and can include wildcard characters (**&#42;** and **?**).|
|[\<Drive2>:][\<Path2>]|Specifies the location of the destination file. You cannot specify a file name for files you replace. If you do not specify a drive or path, **replace** uses the current drive and directory as the destination.|
|/a|Adds new files to the destination directory instead of replacing existing files. You cannot use this command-line option with the **/s** or **/u** command-line option.|
|/p|Prompts you for confirmation before replacing a destination file or adding a source file.|
|/r|Replaces Read-only and unprotected files. If you attempt to replace a Read-only file, but you do not specify **/r**, an error results and stops the replacement operation.|
|/w|Waits for you to insert a disk before the search for source files begins. If you do not specify **/w**, **replace** begins replacing or adding files immediately after you press ENTER.|
|/s|Searches all subdirectories in the destination directory and replaces matching files. You cannot use **/s** with the **/a** command-line option. The **replace** command does not search subdirectories that are specified in *Path1*.|
|/u|Replaces only those files on the destination directory that are older than those in the source directory. You cannot use **/u** with the **/a** command-line option.|
|/?|Displays help at the command prompt.|

## Remarks

- As **replace** adds or replaces files, the file names are displayed on the screen. After **replace** is finished, a summary line is displayed in one of the following formats:  
  ```
  nnn files added
  nnn files replaced
  no file added
  no file replaced
  ```  
- If you are using floppy disks and you need to switch disks during the **replace** operation, you can specify the **/w** command-line option so that **replace** will wait for you to switch the disks.
- You cannot use **replace** to update hidden files or system files.
- The following table shows each exit code and a brief description of its meaning:  
  |Exit code|Description|
  |---------|-----------|
  |0|The **replace** command successfully replaced or added the files.|
  |1|The **replace** command encountered an incorrect version of MS-DOS.|
  |2|The **replace** command could not find the source files.|
  |3|The **replace** command could not find the source or destination path.|
  |5|The user does not have access to the files that you want to replace.|
  |8|There is insufficient system memory to carry out the command.|
  |11|The user used the wrong syntax on the command line.|

> [!NOTE]
> You can use the ERRORLEVEL parameter on the **if** command line in a batch program to process exit codes that are returned by **replace**.

## <a name="BKMK_examples"></a>Examples

To update all the versions of a file named Phones.cli (which appear in multiple directories on drive C), with the latest version of the Phones.cli file from a floppy disk in drive A, type:

`replace a:\phones.cli c:\ /s`

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


