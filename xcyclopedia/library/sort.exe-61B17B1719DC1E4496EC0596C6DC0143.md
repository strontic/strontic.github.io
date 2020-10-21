---
title: sort.exe | Sort Utility
excerpt: What is sort.exe?
---

# sort.exe 

* File Path: `C:\windows\system32\sort.exe`
* Description: Sort Utility

## Hashes

Type | Hash
-- | --
MD5 | `61B17B1719DC1E4496EC0596C6DC0143`
SHA1 | `EAFEB93AC67C8822A845E857F1203FF4D12E9BAB`
SHA256 | `E589CE8E69251502CF1FFF510142B3EBDC4A87D4874324435E257AD4E5D5F72A`
SHA384 | `057E8CEB362D141B9ED0213622C4C484D9E078C258C22DB30C91776DF1BB8352B2FA149A4E7DCBFD7C00614DAB33D8C0`
SHA512 | `B8FB474518C57F02784928460D3ACBADE75394906965079F0B4EC060B45614FB0A5995DE3126CB61F8B1B4D6AEDA7328CBD2C2EDFB9B67A35F587A52EE4ED9E7`
SSDEEP | `384:YfKSvecON1zkgrEPHdWXiGDRYu75DHft4SdMxk5Prt39yng0PRd1amCLkIX3ZgnU:IKWOch9WXiGDbySmGbyng0Xk/5Zgt`

## Signature

* Status: The file C:\windows\system32\sort.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
sort [/r] [/+<N>] [/m <kilobytes>] [/l <locale>] [/rec <characters>] [[<drive1>:][<path1>]<filename1>] [/t [<drive2>:][<path2>]] [/o [<drive3>:][<path3>]<filename3>]
```

#### Parameters

| Parameter | Description |
|--|--|
| /r | Reverses the sort order (that is, sorts from Z to A and from 9 to 0). |
| `/+<N>` | Specifies the character position number where **sort** will begin each comparison. *N* can be any valid integer. |
| /m `<kilobytes>` | Specifies the amount of main memory to use for the sort in kilobytes (KB). |
| /l \<locale> | Overrides the sort order of characters that are defined by the system default locale (that is, the language and Country/Region selected during installation). |
| /rec `<characters>` | Specifies the maximum number of characters in a record or a line of the input file (the default value is 4,096 and the maximum is 65,535). |
| `[<drive1>:][<path1>]<filename1>` | Specifies the file to be sorted. If no file name is specified, the standard input is sorted. Specifying the input file is faster than redirecting the same file as standard input. |
| /t `[<drive2>:][<path2>]` | Specifies the path of the directory to hold the **sort** command's working storage if the data does not fit in the main memory. By default, the system temporary directory is used. |
| /o `[<drive3>:][<path3>]<filename3>` | Specifies the file where the sorted input is to be stored. If not specified, the data is written to the standard output. Specifying the output file is faster than redirecting standard output to the same file. |
| /? | Displays help at the command prompt. |

##### Remarks

- By default, comparisons start at the first character of each line. The **/+** command-line option starts comparisons at the character that is specified by *N*. For example, `/+3` indicates that each comparison should begin at the third character of each line. Lines with fewer than *N* characters collate before other lines.

- The memory used is always a minimum of 160 KB. If the memory size is specified, the exact specified amount is used for the sort (must be at least 160 KB), regardless of how much main memory is available.

- The default maximum memory size when no size is specified is 90% of the available main memory, if both the input and output are files, or 45% of main memory otherwise. The default setting usually gives the best performance.

- Currently, the only alternative to the default locale is the C locale, which is faster than natural language sorting (it sorts characters according to their binary encodings).

- You can use the pipe symbol (`|`) to direct input data to the **sort** command from another command or to direct sorted output to another command. You can specify input and output files by using redirection symbols (`<` or `>`). It can be faster and more efficient (especially with large files) to specify the input file directly (as defined by *filename1* in the command syntax), and then specify the output file using the **/o** parameter.

- The **sort** command doesn't distinguish between uppercase and lowercase letters and has no limit on file size.

- The sort program uses the collating-sequence table that corresponds to the **Country/Region** code and code-page settings. Characters greater than ASCII code 127 are sorted based on information in the Country.sys file or in an alternate file specified by the **country** command in your Config.nt file.

- If the sort fits within the maximum memory size (as set by default or as specified by the **/m** parameter), the sort is performed in a single pass. Otherwise, the sort is performed in two separate sort and merge passes, and the amounts of memory used for both passes are equal. When two passes are performed, the partially sorted data is stored in a temporary file on disk. If there is not enough memory to perform the sort in two passes, a run-time error is issued. If the **/m** command-line option is used to specify more memory than is truly available, performance degradation or a run-time error can occur.

### Examples

- To sort and display, in reverse order, the lines in a file named *expenses.txt*, type:

    ```
    sort /r expenses.txt
    ```

- To search a large file named *maillist.txt* for the text *Jones*, and to sort the results of the search using the pipe (`|`) to direct the output of a **find** command to the **sort** command, type:

    ```
    find Jones maillist.txt | sort
    ```

    The command produces a sorted list of lines that contain the specified text.

- To sort keyboard input and display the results alphabetically on the screen, you can first use the **sort** command with no parameters, by typing:

    ```
    sort
    ```

    Then type the text that you want sorted, and press ENTER at the end of each line. When you have finished typing text, press CTRL+Z, and then press ENTER. The **sort** command displays the text you typed, sorted alphabetically.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


