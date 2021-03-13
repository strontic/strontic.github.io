---
title: sort.exe | Sort Utility
excerpt: What is sort.exe?
---

# sort.exe 

* File Path: `C:\Windows\system32\sort.exe`
* Description: Sort Utility

## Hashes

Type | Hash
-- | --
MD5 | `C824EDDD464E93C4FC77294EB2BB92DF`
SHA1 | `D89071E1B408B6281E631B314DCA5E0E462D5D5D`
SHA256 | `15058D3D03436CA20805750697C289F8F3B40E218BA2A1BB74DE12F68E572183`
SHA384 | `AC9F96B81607E31F4A78B67B5C26E46BD739DC0B6F919D57D461BB5632DBC0E47EFC13CCFB676E6D3273900F421831EB`
SHA512 | `171AF6EAF0329FA924BE66F35A8DA88BB386B025668C7D1A7F8F790C0850103F2652E835167F46141CEFBDBB1C718CAA236D12251197A9212CFAEDD900ED8DD5`
SSDEEP | `384:vfWsOdFNAA0rAIQc7fS41FV6Z4ex5Zk12M65rrqsyxIhCWXRNwNyOabKPSOkNnWK:nWs+6xDS4nV5umyqTZ0bK6OYQ`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
Invalid switch.


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



MIT License. Copyright (c) 2020-2021 Strontic.


