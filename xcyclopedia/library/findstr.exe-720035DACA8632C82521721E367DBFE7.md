
# findstr.exe 
* File Path: `C:\WINDOWS\system32\findstr.exe`
* Description: Find String (QGREP) Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `720035DACA8632C82521721E367DBFE7`
SHA1 | `9776565DC57CCF0E51B7A657A89E0610B0FFFA2B`
SHA256 | `E09620769585ACDA7F33096F8CACC609D1BFA327D9DA051A597FFFFEFD96172D`
SHA384 | `885B48B3137F13EF53A585AD34954016BBEB52F450DC7AAC7CB1F921594BD1470545327C9C193DFF74CB9A45840AC3B5`
SHA415 | `8387F391A718DE391D9788919F6053635DB367CC296E32B232765123D91E03C2B28E6449848AA472ADA9D622BC5906894CBA234035093168F5AB2CEF2AA4FDE9`
SSDEEP | `768:JH5IEkl2sPp+bHEvHnmFm5Puf61UXmJXEYQTUDtHHtSWfcLS9st0/63:pqYrbHEvmWuy1wmh6UNHQYkSSt0/63`

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

* Original Filename: FINDSTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


