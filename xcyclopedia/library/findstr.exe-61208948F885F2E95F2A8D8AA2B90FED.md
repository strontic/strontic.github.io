
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
SHA415 | `BE8C4AA06F971FE120C6B4F0C4A504A5659061E12477BECF00512454EAE747A14FCF0AC726960C92435A9CC134AEC0E5EDFAB77E01E92B60A1B24217B10AE1FB`
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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
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

MIT License. Copyright (c) 2020 Strontic.


