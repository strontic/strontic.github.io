---
title: find.exe | Find String (grep) Utility
---

# find.exe 

* File Path: `C:\WINDOWS\SysWOW64\find.exe`
* Description: Find String (grep) Utility

## Hashes

Type | Hash
-- | --
MD5 | `FCD02331FCF70114ACCD5BFEBE7E4155`
SHA1 | `58B1A3C1637C89374706C4AEE0B6532681D4C242`
SHA256 | `68EBDC30BCAB4A4773100267DB191454DEE42773D203C3516A56F4B61D96E9BD`
SHA384 | `5513AA7C555765FC450D628271E9581193C6BD311496F8F80A9BFD2BFD98B3BFEA46E07F13FCF6A20A93896744FB3122`
SHA512 | `BDDEECEB564C839EB8450E4A1C32429B2CDDA7A2ADC5D7F98DF0712BAA2FF44C92C2EC9AE1C1D2A4278E68C04BA572894FB5E5E72236143A5EB12980CB3BB235`
SSDEEP | `384:6+OKTP6CRc8BRUHPDQ2m9MeIcgn6LQ00DWDIWxR:VOKj6CRc8BRUbLm9MeIcXLf0cL`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
FIND: Parameter format not correct

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\find.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FIND.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


