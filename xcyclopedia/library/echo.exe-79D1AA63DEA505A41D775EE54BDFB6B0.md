---
title: echo.exe | 
excerpt: What is echo.exe?
---

# echo.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\echo.exe`

## Hashes

Type | Hash
-- | --
MD5 | `79D1AA63DEA505A41D775EE54BDFB6B0`
SHA1 | `41A19989292B8A48EBEFC64FA2F03ECA63BA9DBC`
SHA256 | `6DF23865009DC954FD238F68724AD12F76F5262D52CC36474D4662003C9427E2`
SHA384 | `7F63484F3A07CEC198097F035F3EA599C7F56A733D9E15A03B7B3716B557DB59653C55743D63A058835511F6C8C3A223`
SHA512 | `801D64FD8AF4284A4F9A7D8B4EADF5D60190BA55EED2F8651F1C951CAB82B7C967BE0D5C71BDDC44F62557D044C34ACB0E4D19C1D8CF6552EBD103D30E1229D3`
SSDEEP | `768:HcXy8B2HL7gm925p2Y89O5LNiqbolkWYQF2qDGKUf2h:HchB2rUS2zW9sTWYQF2oUf`

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

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\echo.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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


