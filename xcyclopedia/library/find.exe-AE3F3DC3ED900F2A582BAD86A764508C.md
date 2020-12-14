---
title: find.exe | Find String (grep) Utility
excerpt: What is find.exe?
---

# find.exe 

* File Path: `C:\Windows\system32\find.exe`
* Description: Find String (grep) Utility

## Hashes

Type | Hash
-- | --
MD5 | `AE3F3DC3ED900F2A582BAD86A764508C`
SHA1 | `1E44EE63BDB2CF3A6E48B521844204218A001344`
SHA256 | `1A1876C5EED2B8CD9E14EBFF3F4EEB7E21552A4C6AAB4BF392A55F8DF3612DAB`
SHA384 | `79CD234F9166F15122D8DAC377DE28940139E7E68636BBAB93C4BD89BC4A450C9DF4D0E72212AE4DF2FE63B3D07BB904`
SHA512 | `059C0A371AADA5F36E72196109C06208B68475ED0FBEFB950BEB0CBEA2C29595151D65B087C5113AF41DF926596C4FE4E01102DAF4B75E999CF6D6517D26FF63`
SSDEEP | `384:Ahvo3AARFAaVDVxRshn92Jwpvwp0VJZyTWOIW:oV2DVM9Cuvu0VLyt`
IMP | `EF85879194FF4D8C5632D025B0B0AFDE`
PESHA1 | `EB3B8D1DE22CE44B52DE7B3A370A13F374F493C5`
PE256 | `1E5FD45808E7977FB54272C3B9280D4CC5CE265C2A5097F66F289C6B2F4243C2`

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
C:\Windows\system32\find.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FIND.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/1a1876c5eed2b8cd9e14ebff3f4eeb7e21552a4c6aab4bf392a55f8df3612dab/detection


## Possible Misuse

*The following table contains possible examples of `find.exe` being misused. While `find.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\find.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## find

Searches for a string of text in a file or files, and displays lines of text that contain the specified string.

### Syntax

```
find [/v] [/c] [/n] [/i] [/off[line]] <string> [[<drive>:][<path>]<filename>[...]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /v | Displays all lines that don't contain the specified `<string>`. |
| /c | Counts the lines that contain the specified `<string>` and displays the total. |
| /n | Precedes each line with the file's line number. |
| /i | Specifies that the search is not case-sensitive. |
| [/off[line]] | Doesn't skip files that have the offline attribute set. |
| `<string>` | Required. Specifies the group of characters (enclosed in quotation marks) that you want to search for. |
| `[<drive>:][<path>]<filename>` | Specifies the location and name of the file in which to search for the specified string. |
| /? | Displays help at the command prompt. |

##### Remarks

- If you don't use **/i**, this command searches for exactly what you specify for *string*. For example, this command treats the characters `a` and `A` differently. If you use **/i**, however, the search becomes non-case-sensitive, and it treats `a` and `A` as the same character.

- If the string you want to search for contains quotation marks, you must use double quotation marks for each quotation mark contained within the string (for example, ""This string contains quotation marks"").

- If you omit a file name, this command acts as a filter, taking input from the standard input source (usually the keyboard, a pipe (|), or a redirected file) and then displays any lines that contain *string*.

- You can type parameters and command-line options for the **find** command in any order.

- You can't use wildcards (**&#42;** and **?**) in file names or extensions that you specify while using this command. To search for a string in a set of files that you specify with wildcards, you can use this command within a **for** command.

- If you use **/c** and **/v** in the same command line, this command displays a count of the lines that don't contain the specified string. If you specify **/c** and **/n** in the same command line, **find** ignores **/n**.

- This command doesn't recognize carriage returns. When you use this command to search for text in a file that includes carriage returns, you must limit the search string to text that can be found between carriage returns (that is, a string that is not likely to be interrupted by a carriage return). For example, this command doesn't report a match for the string tax file if a carriage return occurs between the words tax and file.

#### Examples

To display all lines from *pencil.ad* that contain the string *pencil sharpener*, type:

```
find pencil sharpener pencil.ad
```

To find the text, "The scientists labeled their paper for discussion only. It is not a final report." in the *report.doc* file, type:

```
find ""The scientists labeled their paper for discussion only. It is not a final report."" report.doc
```

To search for a set of files, you can use the **find** command within the **for** command. To search the current directory for files that have the extension .bat and that contain the string PROMPT, type:

```
for %f in (*.bat) do find PROMPT %f
```

To search your hard disk to find and display the file names on drive C that contain the string CPU, use the pipe (|) to direct the output of the **dir** command to the **find** command as follows:

```
dir c:\ /s /b | find CPU
```

Because **find** searches are case-sensitive and **dir** produces uppercase output, you must either type the string CPU in uppercase letters or use the **/i** command-line option with **find**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [for command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/for.md)

---



MIT License. Copyright (c) 2020 Strontic.


