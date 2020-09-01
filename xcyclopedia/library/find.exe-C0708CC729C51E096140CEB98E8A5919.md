---
title: find.exe | Find String (grep) Utility
---

# find.exe 

* File Path: `C:\windows\SysWOW64\find.exe`
* Description: Find String (grep) Utility

## Hashes

Type | Hash
-- | --
MD5 | `C0708CC729C51E096140CEB98E8A5919`
SHA1 | `719E9E130B06D5F00EE254FD98B136572A667DD8`
SHA256 | `DFA180160E8D58FB471AC0C4602619852FFD74D6426464E0EB6C61C06AFE065B`
SHA384 | `E03D7B48350EB7E6E97EB84E78C366B7523670E87740EE84D4BF82DDD5AC7898F3569A4D4132599FEF453CCBAFC8D487`
SHA512 | `C0A3BF592175DB582DFB971A99FD931C4D02DAEFA8565E72E61105FD9B76FBFE4664C3F1BC373E003B9C411E31C0D9DCB99CBF1227E2DE3ED54D2300AA724BAD`
SSDEEP | `192:RssQ9pabJsiuGYWTXDKo9PTswLiDb/3oVZPZakVkhFWwIWvUZ:R9QKYWTGo9PxZPQkirWwIWvU`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\find.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\windows\SysWOW64\find.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: FIND.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `find.exe` being misused. While `find.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\find.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

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


