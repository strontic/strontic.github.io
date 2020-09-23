---
title: echo.exe | 
excerpt: What is echo.exe?
---

# echo.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\echo.exe`

## Hashes

Type | Hash
-- | --
MD5 | `5645EBB27B220E7B78CE59835D5FB33F`
SHA1 | `C213D1005C75E97C4BD57F894E40980F1C0FB21F`
SHA256 | `AE82E9127AE0B578DB18EB920C19EF1B029B99737601A28C3F3001A0440B6ADD`
SHA384 | `C88E82107C9C4F299BA73199D2772CDB4986E03A3B7DFAA3E12964267F5EBE1938AF7DFA194753F640FBB3916C78ACA5`
SHA512 | `7E8915DDED521B40096BD57C0D9316814731D1EAF52C90EDE8D37191A33294758219122EC1784F9EEF622A2FD0C0EFF84351FB9C9A222BA51F89884391B94536`
SSDEEP | `768:tE/s/xIbVRfKBIbViqboqVccccccccccccccccccccccccccccc9AWZ3Fp1DG6Uu:tE/sqbVtcwWRFpvUf`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/echo [SHORT-OPTION]... [STRING]...
  or:  /usr/bin/echo LONG-OPTION
Echo the STRING(s) to standard output.

  -n             do not output the trailing newline
  -e             enable interpretation of backslash escapes
  -E             disable interpretation of backslash escapes (default)
      --help     display this help and exit
      --version  output version information and exit

If -e is in effect, the following sequences are recognized:

  \\      backslash
  \a      alert (BEL)
  \b      backspace
  \c      produce no further output
  \e      escape
  \f      form feed
  \n      new line
  \r      carriage return
  \t      horizontal tab
  \v      vertical tab
  \0NNN   byte with octal value NNN (1 to 3 digits)
  \xHH    byte with hexadecimal value HH (1 to 2 digits)

NOTE: your shell may have its own version of echo, which usually supersedes
the version described here.  Please refer to your shell's documentation
for details about the options it supports.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/echo>
or available locally via: info '(coreutils) echo invocation'

```

## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## echo

Displays messages or turns on or off the command echoing feature. If used without parameters, **echo** displays the current echo setting.

### Syntax

```
echo [<message>]
echo [on | off]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [on \| off] | Turns on or off the command echoing feature. Command echoing is on by default. |
| `<message>` | Specifies the text to display on the screen. |
| /? | Displays help at the command prompt. |

##### Remarks

- The `echo <message>` command is particularly useful when **echo** is turned off. To display a message that is several lines long without displaying any commands, you can include several `echo <message>` commands after the **echo off** command in your batch program.

- After **echo** is turned off, the command prompt doesn't appear in the Command Prompt window. To display the command prompt, type **echo on.**

- If used in a batch file, **echo on** and **echo off** don't affect the setting at the command prompt.

- To prevent echoing a particular command in a batch file, insert an `@` sign in front of the command. To prevent echoing all commands in a batch file, include the **echo off** command at the beginning of the file.

- To display a pipe (`|`) or redirection character (`<` or `>`) when you are using **echo**, use a caret (`^`) immediately before the pipe or redirection character. For example, `^|`, `^>`, or `^<`). To display a caret, type two carets in succession (`^^`).

#### Examples

To display the current **echo** setting, type:

```
echo
```

To echo a blank line on the screen, type:

```
echo.
```

> [!NOTE]
> Don't include a space before the period. Otherwise, the period appears instead of a blank line.

To prevent echoing commands at the command prompt, type:

```
echo off
```

> [!NOTE]
> When **echo** is turned off, the command prompt doesn't appear in the Command Prompt window. To display the command prompt again, type **echo on**.

To prevent all commands in a batch file (including the **echo off** command) from displaying on the screen, on the first line of the batch file type:

```
@echo off
```

You can use the **echo** command as part of an **if** statement. For example, to search the current directory for any file with the .rpt file name extension, and to echo a message if such a file is found, type:

```
if exist *.rpt echo The report has arrived.
```

The following batch file searches the current directory for files with the .txt file name extension, and displays a message indicating the results of the search:

```
@echo off
if not exist *.txt (
echo This directory contains no text files.
) else (
   echo This directory contains the following text files:
   echo.
   dir /b *.txt
   )
```

If no .txt files are found when the batch file is run, the following message displays:

```
This directory contains no text files.
```

If .txt files are found when the batch file is run the following output displays (for this example, assume the files File1.txt, File2.txt, and File3.txt exist):

```
This directory contains the following text files:
File1.txt
File2.txt
File3.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


