﻿---
title: find.exe | Find String (grep) Utility
excerpt: What is find.exe?
---

# find.exe 

* File Path: `C:\Windows\SysWOW64\find.exe`
* Description: Find String (grep) Utility

## Hashes

Type | Hash
-- | --
MD5 | `F61F39E72D0874BA52D83B8D1BFDFDB4`
SHA1 | `ECC0E6E32A27FFA8A78DCCA4DC0C645EBA72F459`
SHA256 | `6A42C41B345F3F8A22E5F3658B4673ABAE612242ACF12042EC5DE4DEE57A98D8`
SHA384 | `028D3BB098E820D6B7CDA8F8037BA88A6E2786822E506FB31DAA20F0C0E7647D4ABD6D88DD6D18AA4439E895F5080904`
SHA512 | `E37A6621D44E2F25C27FCA07E3EB57B77FA71A439412050E3FE9900012CA0040B89BF530B9898D450AE67EDB6AE7DA338C5853270F12C8919A97A10DD786490F`
SSDEEP | `384:KyST+0IAVY83RUHNQ2m9MeKZKYe6QO0jWpIWju:KySS0IAVY83RUtLm9MeKZK6J0Cp`
IMP | `F1CCECB8E289C2632DEE607CD74A0CCA`
PESHA1 | `9880DD0D6505751EB7A77C4B40A0E4126A24675F`
PE256 | `CE8DD57773D81EB78433FA7F640F1CE0D48A7567977BADF6F737E5443C8F68EC`

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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FIND.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/6a42c41b345f3f8a22e5f3658b4673abae612242acf12042ec5de4dee57a98d8/detection/


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


