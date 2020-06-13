
# findstr.exe 

* File Path: `C:\Windows\SysWOW64\findstr.exe`
* Description: Find String (QGREP) Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `61208948F885F2E95F2A8D8AA2B90FED`
SHA1 | `823E9B8239734C3B00C2B7FDDBF632C918A2E1B9`
SHA256 | `EA0C8F0CCB347ACF136A9CF692A06F9FBD13604CE8EC2327D58CAD7EEFA0144F`
SHA384 | `456C74A615EEBD392A1BD86E0BF0F625E38C7867CE1ED1CA95FC774B5B96BF9CB49E22C16AADCA2305F4163C1537A2F8`
SHA512 | `BE8C4AA06F971FE120C6B4F0C4A504A5659061E12477BECF00512454EAE747A14FCF0AC726960C92435A9CC134AEC0E5EDFAB77E01E92B60A1B24217B10AE1FB`
SSDEEP | `384:jippH3l2anBdjfqTBX6COoB64qzL7l7jKFG7H9K0oSmtrH0y2NXmscZQ8Z9/YVpY:G2anziNb0xJ0q0pQ6dYqXI0R`

## Runtime Data

### Usage (stdout):
```Batchfile
Searches for strings in files.

FINDSTR [/B] [/E] [/L] [/R] [/S] [/I] [/X] [/V] [/N] [/M] [/O] [/P] [/F:file]
        [/C:string] [/G:file] [/D:dir list] [/A:color attributes] [/OFF[LINE]]
        strings [[drive:][path]filename[ ...]]

  /B         Matches pattern if at the beginning of a line.
  /E         Matches pattern if at the end of a line.
  /L         Uses search strings literally.
  /R         Uses search strings as regular expressions.
  /S         Searches for matching files in the current directory and all
             subdirectories.
  /I         Specifies that the search is not to be case-sensitive.
  /X         Prints lines that match exactly.
  /V         Prints only lines that do not contain a match.
  /N         Prints the line number before each line that matches.
  /M         Prints only the filename if a file contains a match.
  /O         Prints character offset before each matching line.
  /P         Skip files with non-printable characters.
  /OFF[LINE] Do not skip files with offline attribute set.
  /A:attr    Specifies color attribute with two hex digits. See "color /?"
  /F:file    Reads file list from the specified file(/ stands for console).
  /C:string  Uses specified string as a literal search string.
  /G:file    Gets search strings from the specified file(/ stands for console).
  /D:dir     Search a semicolon delimited list of directories
  strings    Text to be searched for.
  [drive:][path]filename
             Specifies a file or files to search.

Use spaces to separate multiple search strings unless the argument is prefixed
with /C.  For example, 'FINDSTR "hello there" x.y' searches for "hello" or
"there" in file x.y.  'FINDSTR /C:"hello there" x.y' searches for
"hello there" in file x.y.

Regular expression quick reference:
  .        Wildcard: any character
  *        Repeat: zero or more occurrences of previous character or class
  ^        Line position: beginning of line
  $        Line position: end of line
  [class]  Character class: any one character in set
  [^class] Inverse class: any one character not in set
  [x-y]    Range: any characters within the specified range
  \x       Escape: literal use of metacharacter x
  \<xyz    Word position: beginning of word
  xyz\>    Word position: end of word

For full information on FINDSTR regular expressions refer to the online Command
Reference.

```

### Usage (stderr):
```Batchfile
FINDSTR: /h ignored
FINDSTR: Bad command line

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

* Original Filename: FINDSTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# findstr

Searches for patterns of text in files.

## Syntax

```
findstr [/b] [/e] [/l | /r] [/s] [/i] [/x] [/v] [/n] [/m] [/o] [/p] [/f:<file>] [/c:<string>] [/g:<file>] [/d:<dirlist>] [/a:<colorattribute>] [/off[line]] <strings> [<drive>:][<path>]<filename>[ ...]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| /b | Matches the text pattern if it is at the beginning of a line. |
| /e | Matches the text pattern if it is at the end of a line. |
| /l | Processes search strings literally. |
| /r | Processes search strings as regular expressions. This is the default setting. |
| /s | Searches the current directory and all subdirectories. |
| /i | Ignores the case of the characters when searching for the string. |
| /x | Prints lines that match exactly. |
| /v | Prints only lines that don't contain a match. |
| /n | Prints the line number of each line that matches. |
| /m | Prints only the file name if a file contains a match. |
| /o | Prints character offset before each matching line. |
| /p | Skips files with non-printable characters. |
| /off[line] | Does not skip files that have the offline attribute set. |
| /f:`<file>` | Gets a file list from the specified file. |
| /c:`<string>` | Uses the specified text as a literal search string. |
| /g:`<file>` | Gets search strings from the specified file. |
| /d:`<dirlist>` | Searches the specified list of directories. Each directory must be separated with a semicolon (;), for example `dir1;dir2;dir3`. |
| /a:`<colorattribute>` | Specifies color attributes with two hexadecimal digits. Type `color /?` for additional information. |
| `<strings>` | Specifies the text to search for in *filename*. Required. |
| `[\<drive>:][<path>]<filename>[ ...]` | Specifies the location and file or files to search. At least one file name is required. |
| /? | Displays Help at the command prompt. |

#### Remarks

- All **findstr** command-line options must precede *strings* and *filename* in the command string.

- Regular expressions use both literal characters and meta-characters to find patterns of text, rather than exact strings of characters.

  - A literal character is a character that doesn't have a special meaning in the regular-expression syntax; instead, it matches an occurrence of that character. For example, letters and numbers are literal characters.

  - A meta-character is a symbol with special meaning (an operator or delimiter) in the regular-expression syntax.

    The accepted meta-characters, are:

    | Meta-character | Value |
    | -------------- | ----- |
    | `.` | **Wildcard** - Any character |
    | `*` | **Repeat** - Zero or more occurrences of the previous character or class. |
    | `^` | **Beginning line position** - Beginning of the line. |
    | `$` | **Ending line position** - End of the line. |
    | `[class]` | **Character class** - Any one character in a set. |
    | `[^class]` | **Inverse class** - Any one character not in a set. |
    | `[x-y]` | **Range** - Any characters within the specified range. |
    | `\x` | **Escape** - Literal use of a meta-character. |
    | `<string` | **Beginning word position** - Beginning of the word. |
    | `string>` | **Ending word position** - End of the word. |

    The special characters in regular expression syntax have the most power when you use them together. For example, use the combination of the wildcard character (`.`) and repeat (`*`) character to match any string of characters: `.*`

    Use the following expression as part of a larger expression to match any string beginning with *b* and ending with *ing*: `b.*ing`

- To search for multiple strings in a set of files, you must create a text file that contains each search criterion on a separate line.

- Use spaces to separate multiple search strings unless the argument is prefixed with **/c**.

### Examples

To search for *hello* or *there* in file *x.y*, type:

```
findstr hello there x.y
```

To search for *hello there* in file *x.y*, type:

```
findstr /c:hello there x.y
```

To find all occurrences of the word *Windows* (with an initial capital letter W) in the file *proposal.txt*, type:

```
findstr Windows proposal.txt
```

To search every file in the current directory and all subdirectories that contained the word *Windows*, regardless of the letter case, type:

```
findstr /s /i Windows *.*
```

To find all occurrences of lines that begin with *FOR* and are preceded by zero or more spaces (as in a computer program loop), and to display the line number where each occurrence is found, type:

```
findstr /b /n /r /c:^ *FOR *.bas
```

To list the exact files that you want to search in a text file, use the search criteria in the file *stringlist.txt*, to search the files listed in *filelist.txt*, and then to store the results in the file *results.out*, type:

```
findstr /g:stringlist.txt /f:filelist.txt > results.out
```

To list every file containing the word *computer* within the current directory and all subdirectories, regardless of case, type:

```
findstr /s /i /m <computer> *.*
```

To list every file containing the word computer and any other words that begin with comp, (such as compliment and compete), type:

```
findstr /s /i /m <comp.* *.*
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


