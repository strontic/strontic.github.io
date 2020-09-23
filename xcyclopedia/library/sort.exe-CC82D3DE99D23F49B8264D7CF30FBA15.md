---
title: sort.exe | Sort Utility
excerpt: What is sort.exe?
---

# sort.exe 

* File Path: `C:\windows\SysWOW64\sort.exe`
* Description: Sort Utility

## Hashes

Type | Hash
-- | --
MD5 | `CC82D3DE99D23F49B8264D7CF30FBA15`
SHA1 | `FC42034FE2BFBD05766E694FBC201CABDA621663`
SHA256 | `6C190A2205122C65C196283B32BDCC1549C465E730793CB1C6169857DE781EAE`
SHA384 | `3F48C43F31DDBB690B188949D3426873BE5D58797FAB383677F5A2A7063172B8629CB43A7496E8138B275347B56FA5FF`
SHA512 | `F7555CB1D37CAF6BE618E4C2D7FEAC465A59A1B421A0F05946A2F0CAD99BD7A029B796F2F5CE8CC88D9D008047360778DD830A4DFA784010431E6EC455879F12`
SSDEEP | `384:xEvHDWoMB0xEyk0SqYhwOYCXJLyODE4LHWanW:UDW1A/ODDLN`

## Signature

* Status: The file C:\windows\SysWOW64\sort.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Sort.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## sort

Reads input, sorts data, and writes the results to the screen, to a file, or to another device.



### Syntax

```
sort [/r] [/+<N>] [/m <Kilobytes>] [/l <Locale>] [/rec <Characters>] [[<Drive1>:][<Path1>]<FileName1>] [/t [<Drive2>:][<Path2>]] [/o [<Drive3>:][<Path3>]<FileName3>]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|/r|Reverses the sort order (that is, sorts from Z to A and from 9 to 0).|
|/+\<N>|Specifies the character position number where **sort** will begin each comparison. *N* can be any valid integer.|
|/m \<Kilobytes>|Specifies the amount of main memory to use for the sort in kilobytes (KB).|
|/l \<Locale>|Overrides the sort order of characters that are defined by the system default locale (that is, the language and Country/Region selected during installation).|
|/rec \<Characters>|Specifies the maximum number of characters in a record or a line of the input file (the default value is 4,096 and the maximum is 65,535).|
|[\<Drive1>:][\<Path1>]\<FileName1>|Specifies the file to be sorted. If no file name is specified, the standard input is sorted. Specifying the input file is faster than redirecting the same file as standard input.|
|/t [\<Drive2>:][\<Path2>]|Specifies the path of the directory to hold the **sort** command's working storage if the data does not fit in the main memory. By default, the system temporary directory is used.|
|/o [\<Drive3>:][\<Path3>]\<FileName3>|Specifies the file where the sorted input is to be stored. If not specified, the data is written to the standard output. Specifying the output file is faster than redirecting standard output to the same file.|
|/?|Displays help at the command prompt.|

### Remarks

-   Using the **/+** command-line option

    By default, comparisons start at the first character of each line. The **/+** command-line option starts comparisons at the character that is specified by *N*. For example, `/+3` indicates that each comparison should begin at the third character of each line. Lines with fewer than *N* characters collate before other lines.
-   Using the **/m** command-line option

    The memory used is always a minimum of 160 KB. If the memory size is specified, the exact specified amount is used for the sort (must be at least 160 KB), regardless of how much main memory is available.

    The default maximum memory size when no size is specified is 90 percent of the available main memory if both the input and output are files, or 45 percent of main memory otherwise. The default setting usually gives the best performance.
-   Using the **/l** command-line option

    Currently, the only alternative to the default locale is the C locale, which is faster than natural language sorting (it sorts characters according to their binary encodings).
-   Using redirection symbols with the **sort** command

    You can use the pipe symbol (**|**) to direct input data to the **sort** command from another command or to direct sorted output to another command. You can specify input and output files by using redirection symbols (**<** or **>**). It can be faster and more efficient (especially with large files) to specify the input file directly (as defined by *FileName1* in the command syntax), and then specify the output file using the **/o** parameter.
-   Case sensitivity

    The **sort** command does not distinguish between uppercase and lowercase letters.
-   Limits on file size

    The **sort** command has no limit on file size.
-   Collating sequence

    The sort program uses the collating-sequence table that corresponds to the Country/Region code and code-page settings. Characters greater than ASCII code 127 are sorted based on information in the Country.sys file or in an alternate file specified by the **country** command in your Config.nt file.
-   Memory usage

    If the sort fits within the maximum memory size (as set by default or as specified by the **/m** parameter), the sort is performed in a single pass. Otherwise, the sort is performed in two separate sort and merge passes, and the amounts of memory used for both passes are equal. When two passes are performed, the partially sorted data is stored in a temporary file on disk. If there is not enough memory to perform the sort in two passes, a run-time error is issued. If the **/m** command-line option is used to specify more memory than is truly available, performance degradation or a run-time error can occur.

### Examples

**Sorting a file**

To sort and display in reverse order the lines in a file named Expenses.txt, type:

`sort /r expenses.txt`

**Sorting the output from a command**

To search a large file named Maillist.txt for the text Jones, and to sort the results of the search, use the pipe (|) to direct the output of a **find** command to the **sort** command, as follows:

`find Jones maillist.txt | sort`

The command produces a sorted list of lines that contain the specified text.

**Sorting keyboard input**

To sort keyboard input and display the results alphabetically on the screen, you can first use the **sort** command with no parameters, as follows:

`sort`

Then type the text that you want sorted, and press ENTER at the end of each line. When you have finished typing text, press CTRL+Z, and then press ENTER. The **sort** command displays the text you typed, sorted alphabetically.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


