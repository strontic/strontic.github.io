
# replace.exe 

* File Path: `C:\Windows\SysWOW64\replace.exe`
* Description: Replace File Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `48E66EA496BBC345592997347B5220D4`
SHA1 | `20D17BBEA61B1F98CE4BAEF5E57DDDD0AC1E4947`
SHA256 | `E6FC8FA07A57A0D5AF992B49C67EBF65CE7297D7BE8EEBCE645EE78041580897`
SHA384 | `3EE8ED7B371AF93F234A82802A37515799F8340B5161E09F8F4192768328AD1DAF753146B16B10E90A33D81789EBC89B`
SHA512 | `36D3BA2CF14A27BA6037D9E238E4A60A1ED211DDDEF9BFB9D657C384EC150484175DEC39F6DDE404BFFF0EFDB53C91394393C8D89F0BE011A05A020C82FF144F`
SSDEEP | `384:tvp8Vc0mTVLYq6lDRP5QeXXgsDg7rF9KKdlWFh/WoR4:tRuc/VkdNRPevUg9p8T`

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
RdpSa.exe

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


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


