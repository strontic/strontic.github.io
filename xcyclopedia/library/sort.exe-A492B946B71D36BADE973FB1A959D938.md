---
title: sort.exe | 
---

# sort.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\sort.exe`

## Hashes

Type | Hash
-- | --
MD5 | `A492B946B71D36BADE973FB1A959D938`
SHA1 | `F66542F398AA4BBC6A48374EAEE3BDE603424848`
SHA256 | `A37CC2B276FAE7465D903834664F540157B2A197C9638FF9936588C7D3E87C3D`
SHA384 | `FF31C95069DC7EF76A79629E5751F3C6C519B670729F49FD017B04305025B33F693A16509B96507B3A01B8BEEEED5E16`
SHA512 | `3EAC535DECC8619D4C67EDA8334F45E7BE77D1C0D1EE56E7E7F6547242FF73C2F146ABED1949A9AF65561D5D3023F0ECAFC742C8D3A592D5E8247798D3FF5AA1`
SSDEEP | `1536:yG5m/NWdXWwvKJpUwnlsJw9L190nmk7xuiyfrZykWFrodbaUfY:x6cd/vEmSuJw11oHErZyxFrodbC`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: /usr/bin/sort [OPTION]... [FILE]...
  or:  /usr/bin/sort [OPTION]... --files0-from=F
Write sorted concatenation of all FILE(s) to standard output.

With no FILE, or when FILE is -, read standard input.

Mandatory arguments to long options are mandatory for short options too.
Ordering options:

  -b, --ignore-leading-blanks  ignore leading blanks
  -d, --dictionary-order      consider only blanks and alphanumeric characters
  -f, --ignore-case           fold lower case to upper case characters
  -g, --general-numeric-sort  compare according to general numerical value
  -i, --ignore-nonprinting    consider only printable characters
  -M, --month-sort            compare (unknown) < 'JAN' < ... < 'DEC'
  -h, --human-numeric-sort    compare human readable numbers (e.g., 2K 1G)
  -n, --numeric-sort          compare according to string numerical value
  -R, --random-sort           shuffle, but group identical keys.  See shuf(1)
      --random-source=FILE    get random bytes from FILE
  -r, --reverse               reverse the result of comparisons
      --sort=WORD             sort according to WORD:
                                general-numeric -g, human-numeric -h, month -M,
                                numeric -n, random -R, version -V
  -V, --version-sort          natural sort of (version) numbers within text

Other options:

      --batch-size=NMERGE   merge at most NMERGE inputs at once;
                            for more use temp files
  -c, --check, --check=diagnose-first  check for sorted input; do not sort
  -C, --check=quiet, --check=silent  like -c, but do not report first bad line
      --compress-program=PROG  compress temporaries with PROG;
                              decompress them with PROG -d
      --debug               annotate the part of the line used to sort,
                              and warn about questionable usage to stderr
      --files0-from=F       read input from the files specified by
                            NUL-terminated names in file F;
                            If F is - then read names from standard input
  -k, --key=KEYDEF          sort via a key; KEYDEF gives location and type
  -m, --merge               merge already sorted files; do not sort
  -o, --output=FILE         write result to FILE instead of standard output
  -s, --stable              stabilize sort by disabling last-resort comparison
  -S, --buffer-size=SIZE    use SIZE for main memory buffer
  -t, --field-separator=SEP  use SEP instead of non-blank to blank transition
  -T, --temporary-directory=DIR  use DIR for temporaries, not $TMPDIR or /tmp;
                              multiple options specify multiple directories
      --parallel=N          change the number of sorts run concurrently to N
  -u, --unique              with -c, check for strict ordering;
                              without -c, output only the first of an equal run
  -z, --zero-terminated     line delimiter is NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

KEYDEF is F[.C][OPTS][,F[.C][OPTS]] for start and stop position, where F is a
field number and C a character position in the field; both are origin 1, and
the stop position defaults to the line's end.  If neither -t nor -b is in
effect, characters in a field are counted from the beginning of the preceding
whitespace.  OPTS is one or more single-letter ordering options [bdfgiMhnRrV],
which override global ordering options for that key.  If no key is given, use
the entire line as the key.  Use --debug to diagnose incorrect key usage.

SIZE may be followed by the following multiplicative suffixes:
% 1% of memory, b 1, K 1024 (default), and so on for M, G, T, P, E, Z, Y.

*** WARNING ***
The locale specified by the environment affects sort order.
Set LC_ALL=C to get the traditional sort order that uses
native byte values.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/sort>
or available locally via: info '(coreutils) sort invocation'

```

### Usage (stderr):
```Batchfile
sort: unknown option -- e
Try '/usr/bin/sort --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\sort.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 



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


