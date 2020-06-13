
# find.exe 

* File Path: `C:\Windows\system32\find.exe`
* Description: Find String (grep) Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1E16116CCE7317C0E87559DA23A4EAD3`
SHA1 | `5A27FC19C8D3650727766805E322923E9368D308`
SHA256 | `40C0EC6D7371D316BC1F0ABE80D0236F613C9FB88DCE2D9B5D5FD4A1A59E8B49`
SHA384 | `312B46906A6018EB473174ED861730201D14A5DDEA772A85563FF70B04339F47EF2E368301C1610CE84772D604DE9CCB`
SHA512 | `B208C44FC04033B7012D9B553DB244DC3B052E7166B36AA438324471FDD11FAC46CB310B4AD21D16B3F17141A3CBD18C1964EB95E39AECA6D2CB38EEDB73ED96`
SSDEEP | `384:RCWraD3RofPNirga9u0ODAa7geWFLW9IWf:R9GFofVFNCa7gem2l`

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

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FIND.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# find

Searches for a string of text in a file or files, and displays lines of text that contain the specified string.

## Syntax

```
find [/v] [/c] [/n] [/i] [/off[line]] <string> [[<drive>:][<path>]<filename>[...]]
```

### Parameters

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

#### Remarks

- If you don't use **/i**, this command searches for exactly what you specify for *string*. For example, this command treats the characters `a` and `A` differently. If you use **/i**, however, the search becomes non-case-sensitive, and it treats `a` and `A` as the same character.

- If the string you want to search for contains quotation marks, you must use double quotation marks for each quotation mark contained within the string (for example, ""This string contains quotation marks"").

- If you omit a file name, this command acts as a filter, taking input from the standard input source (usually the keyboard, a pipe (|), or a redirected file) and then displays any lines that contain *string*.

- You can type parameters and command-line options for the **find** command in any order.

- You can't use wildcards (**&#42;** and **?**) in file names or extensions that you specify while using this command. To search for a string in a set of files that you specify with wildcards, you can use this command within a **for** command.

- If you use **/c** and **/v** in the same command line, this command displays a count of the lines that don't contain the specified string. If you specify **/c** and **/n** in the same command line, **find** ignores **/n**.

- This command doesn't recognize carriage returns. When you use this command to search for text in a file that includes carriage returns, you must limit the search string to text that can be found between carriage returns (that is, a string that is not likely to be interrupted by a carriage return). For example, this command doesn't report a match for the string tax file if a carriage return occurs between the words tax and file.

### Examples

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

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [for command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/for.md)

---


MIT License. Copyright (c) 2020 Strontic.


