
# replace.exe 

* File Path: `C:\WINDOWS\system32\replace.exe`
* Description: Replace File Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D5F41D113E81AF4E732BD9B785FA6DFA`
SHA1 | `7B7AC0E6E1A5EF85D5A8FA79B75F53AD7C7847A9`
SHA256 | `D66CCD7D5CCA8B95910E04C8A7300ED7AC4CF96282E6C35664A980E7A187BC93`
SHA384 | `7E08C008404EFD2EC1AADDB66977A5B85F23EFA9C4B9B683A78638501F97E0214F9747416BD1665839340AEE326CB080`
SHA512 | `D8AF96D758B55055606872BC767507BBBA2FBEF0F710695EA52A34F2EBA9BD7419F80E6AAC603C3003F7E61A3688D3D87D688BEAC13AF1ABCD9FD36285A517C8`
SSDEEP | `384:GwHgx1QR0ftLlp048Y9dmKsvmHOBsjw4pw163tW7h/W:GoRutrR9gLvI9jw4++2`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REPLACE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


