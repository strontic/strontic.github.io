---
title: sort.exe | Sort Utility
---

# sort.exe 

* File Path: `C:\Windows\SysWOW64\sort.exe`
* Description: Sort Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `995F41569F595164CD60C8160C128D05`
SHA1 | `BC66C5F68BDD7C2D473786F472EDCCC10661F409`
SHA256 | `4529B7450EA09756EDC9EAE43C1DC4EDD29D1A7A19321BE810654997F26A0F8B`
SHA384 | `C522920FE923BD0F4244322D0C18D2A014DB72C9A698DE6FE4948B6CB2FE5413E6C6F482F736FECA027E69AE3A290E82`
SHA512 | `36D2D8F0F635B4C8585933E2E21613A300F1C8B9837F92D7889F51B8C0E3DEE29E16D0F3C0A1F10D7D76CE223227A21F5A7E1414164AC826E1D935884029D3A8`
SSDEEP | `384:i0RnTyULFfjVsEI+4e+lMAw1WjHKXRfa7ZbHWjnWoYwc5:i0tZZsP+3+lMp1k1bwhc5`

## Runtime Data

### Usage (stdout):
```Batchfile
SORT [/R] [/+n] [/M kilobytes] [/L locale] [/REC recordbytes]
  [[drive1:][path1]filename1] [/T [drive2:][path2]]
  [/O [drive3:][path3]filename3]
  /+n                         Specifies the character number, n, to
                              begin each comparison.  /+3 indicates that
                              each comparison should begin at the 3rd
                              character in each line.  Lines with fewer
                              than n characters collate before other lines.
                              By default comparisons start at the first
                              character in each line.
  /L[OCALE] locale            Overrides the system default locale with
                              the specified one.  The ""C"" locale yields
                              the fastest collating sequence and is
                              currently the only alternative.  The sort
                              is always case insensitive.
  /M[EMORY] kilobytes         Specifies amount of main memory to use for
                              the sort, in kilobytes.  The memory size is
                              always constrained to be a minimum of 160
                              kilobytes.  If the memory size is specified
                              the exact amount will be used for the sort,
                              regardless of how much main memory is
                              available.

                              The best performance is usually achieved by
                              not specifying a memory size.  By default the
                              sort will be done with one pass (no temporary
                              file) if it fits in the default maximum
                              memory size, otherwise the sort will be done
                              in two passes (with the partially sorted data
                              being stored in a temporary file) such that
                              the amounts of memory used for both the sort
                              and merge passes are equal.  The default
                              maximum memory size is 90% of available main
                              memory if both the input and output are
                              files, and 45% of main memory otherwise.
  /REC[ORD_MAXIMUM] characters Specifies the maximum number of characters
                              in a record (default 4096, maximum 65535).
  /R[EVERSE]                  Reverses the sort order; that is,
                              sorts Z to A, then 9 to 0.
  [drive1:][path1]filename1   Specifies the file to be sorted.  If not
                              specified, the standard input is sorted.
                              Specifying the input file is faster than
                              redirecting the same file as standard input.
  /T[EMPORARY]
    [drive2:][path2]          Specifies the path of the directory to hold
                              the sort's working storage, in case the data
                              does not fit in main memory.  The default is
                              to use the system temporary directory.
  /O[UTPUT]
    [drive3:][path3]filename3 Specifies the file where the sorted input is
                              to be stored.  If not specified, the data is
                              written to the standard output.   Specifying
                              the output file is faster than redirecting
                              standard output to the same file.


```

### Usage (stderr):
```Batchfile
Invalid switch.


```

### Child Processes:
perfmon.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Sort.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


