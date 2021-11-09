---
title: find.exe | Find String (grep) Utility
excerpt: What is find.exe?
---

# find.exe 

* File Path: `C:\WINDOWS\system32\find.exe`
* Description: Find String (grep) Utility

## Hashes

Type | Hash
-- | --
MD5 | `3736A095A393267AAD4952C8D9011397`
SHA1 | `0CBF2A606E33D3F161625E68A97AA0ED2F9B3C45`
SHA256 | `A4AF9EF6E345B3B4EA50DDE672A986C14F9A195E407EBAC36B1652AACC10E3EE`
SHA384 | `E78E849F577DD07A05BFC56E6800DA473D1D10EB052B592702CF1824CD89CB50182E5FECDBF8759DBAA2718AA80EFA90`
SHA512 | `CB1A2B7B7F8EE6DA2C39757E0501042CCDACB21434FA2AE0D7FD1F9898C01D2C8831CB69F133A55AB87565C8A90D0892E4AC2E968C308FAEEF1FFAFDBEAE6E12`
SSDEEP | `384:1pK7zSm5VhoW1AmAujb/kLkllJbTWdIW:1pcVyIAuXkLkll1+`
IMP | `53D01F599FA823367954405BF5F690B3`
PESHA1 | `2BD523CF235FC2A955424B000457B06DB7A88C3A`
PE256 | `30432EA750F35117FB3821AE9BA9F8FD6400113A08B64174BC888EA9B653D66F`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\find.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FIND.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/a4af9ef6e345b3b4ea50dde672a986c14f9a195e407ebac36b1652aacc10e3ee/detection


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


