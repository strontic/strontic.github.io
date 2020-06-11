
# findstr.exe 

* File Path: `C:\WINDOWS\SysWOW64\findstr.exe`
* Description: Find String (QGREP) Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `632DF50AB80EB40B6D3D05392A231A14`
SHA1 | `ED5B9185C8E655C511A1650F0D67556BAE9C1DC8`
SHA256 | `3E543C71749DE0E95D39EAF328FCA253D5F025FD85ECB07670A1536EC87015DA`
SHA384 | `831F82F8F62DF029A28147DEF379CCB4B6821EDFBCD0D0F003FBB1AD3C4166E70B51F5F822FAC1B16F00122C66ED56C1`
SHA415 | `BA0947B9ECA9A30DC03DA9D92E2113C93D40E7C544371935599DB3B93A0F47768675CC017B4C5DBA81336201173379EFBE67A835902D3DB1268C0648F0EC1125`
SSDEEP | `384:tpHR5XBWHG7B71Cn7GYvQThNUjBXqTYgP3Nw7Hu26RAtjHv8Of2GNYNCPUt0DXPi:d5XYmVZfiYdZC8FgYZt0T3a`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FINDSTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


