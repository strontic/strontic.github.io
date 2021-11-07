---
title: find.exe | Find String (grep) Utility
excerpt: What is find.exe?
---

# find.exe 

* File Path: `C:\Windows\SysWOW64\find.exe`
* Description: Find String (grep) Utility

## Hashes

Type | Hash
-- | --
MD5 | `31D06677CD9ACA84EA2E2E8E3BF22D65`
SHA1 | `83780092915B15E5188AD0B2E7A683442566F3BF`
SHA256 | `63DDBCB0233ED7C8C90748869EC5879309A351FFC6D230AF66CCDE8372F00B34`
SHA384 | `397D0BE78FF9E7F80E3C1EDFE841CC85F9BC66435DD3BFEE1E4C1077C92B6506F100B10E53430A050BB160B1E8B2CFE5`
SHA512 | `AEF0356F9D6C9A35189305A507A02E3874F573A693293331971BF46F698A1398C2DEE1D89F742D25109E28DB826DB8932CB1FDEA412FB123BFAF6B6D7FDAAE33`
SSDEEP | `384:HIGKTPCCRLMRUXIQmm9Me7sNDT6zjazWOIW7:HIGKjCCRLMRU4bm9Me7sJGzONR`
IMP | `F1CCECB8E289C2632DEE607CD74A0CCA`
PESHA1 | `16E63F62C8A3D27CDDF30E1A69928DE534E05D16`
PE256 | `67DC28AD2A6507CE06FCF58F3CF642F44A87DF2A6F5BA85D48C2F757BFB276BF`

## Runtime Data

### Usage (stdout):
```cmhg
Searches for a text string in a file or files.

FIND [/V] [/C] [/N] [/I] [/OFF[LINE]] "string" [[drive:][path]filename[ ...]]

  /V         Displays all lines NOT containing the specified string.
  /C         Displays only the count of lines containing the string.
  /N         Displays line numbers with the displayed lines.
  /I         Ignores the case of characters when searching for the string.
  /OFF[LINE] Do not skip files with offline attribute set.
  "string"   Specifies the text string to find.
  [drive:][path]filename
             Specifies a file or files to search.

If a path is not specified, FIND searches the text typed at the prompt
or piped from another command.

```

### Usage (stderr):
```cmhg
FIND: Parameter format not correct

```

### Child Processes:
mmc.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\find.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FIND.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/63ddbcb0233ed7c8c90748869ec5879309a351ffc6d230af66ccde8372f00b34/detection


## Possible Misuse

*The following table contains possible examples of `find.exe` being misused. While `find.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\find.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## find

Searches for a string of text in a file or files, and displays lines of text that contain the specified string.

### Syntax

```
find [/v] [/c] [/n] [/i] [/off[line]] <"string"> [[<drive>:][<path>]<filename>[...]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /v | Displays all lines that don't contain the specified `<string>`. |
| /c | Counts the lines that contain the specified `<string>` and displays the total. |
| /n | Precedes each line with the file's line number. |
| /i | Specifies that the search is not case-sensitive. |
| [/off[line]] | Doesn't skip files that have the offline attribute set. |
| `<"string">` | Required. Specifies the group of characters (enclosed in quotation marks) that you want to search for. |
| `[<drive>:][<path>]<filename>` | Specifies the location and name of the file in which to search for the specified string. |
| /? | Displays help at the command prompt. |

#### Exit codes

| Exit code | Description |
| --------- | ----------- |
| 0 | The searched string was found |
| 1 | Searched string not found |
| 2 | Searched file not found or invalid command line switch was given |

##### Remarks

- If you don't use **/i**, this command searches for exactly what you specify for *string*. For example, this command treats the characters `a` and `A` differently. If you use **/i**, however, the search becomes case insensitive, and it treats `a` and `A` as the same character.

- If the string you want to search for contains quotation marks, you must use double quotation marks for each quotation mark contained within the string (for example, """This string contains quotation marks""").

- If you omit a file name, this command acts as a filter, taking input from the standard input source (usually the keyboard, a pipe (|), or a redirected file) and then displays any lines that contain *string*.

- To exit the console search use `CTRL-X` or `CTRL-z`.

- You can type parameters and command-line options for the **find** command in any order.

- You can't use wildcards (**&#42;** and **?**) in the searched string. To search for a string with wild cards and regex patterns, you can use the **FINDSTR** command.

- If you use **/c** and **/v** in the same command line, this command displays a count of the lines that don't contain the specified string. If you specify **/c** and **/n** in the same command line, **find** ignores **/n**.

- This command doesn't recognize carriage returns. When you use this command to search for text in a file that includes carriage returns, you must limit the search string to text that can be found between carriage returns (that is, a string that is not likely to be interrupted by a carriage return). For example, this command doesn't report a match for the string tax file if a carriage return occurs between the words tax and file.

- The command accepts wildcards for file names. When searching in file (or files) it will print the file of the processed file predeceased by ten dashes.

- **Find** command cannot read alternate data streams. For searching in alternate data streams use **findstr**, **more** or **for /f** commands.

#### Examples

To display all lines from *pencil.md* that contain the string *pencil sharpener*, type:

```
find "pencil sharpener" pencil.md
```

To find the text, *"The scientists labeled their paper for discussion only. It is not a final report."* (including the quotes) in the *report.txt* file, type:

```
find """The scientists labeled their paper for discussion only. It is not a final report.""" < report.txt
```

To search for a set of files, you can use wildcards. To search the current directory for files that have the extension *.bat* and that contain the string *PROMPT* ignoring the case, type:

```
find /i "PROMPT" *.bat
```

To find files names in a directory that contain the string *CPU*, use the pipe (|) to direct the output of the *dir* command to the find command as follows:

```
dir c:\temp /s /b | find "CPU"
```

Find all running processes that do NOT contain  *agent*:

```
tasklist | find /v /i "agent"
```

Check if a service is running:

```
sc query  Winmgmt | find "RUNNING" >nul 2>&1 && (echo service is started) || (echo service is stopped)
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [findstr command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/findstr.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


