---
title: more.com | More Utility
excerpt: What is more.com?
---

# more.com 

* File Path: `C:\Windows\system32\more.com`
* Description: More Utility

## Hashes

Type | Hash
-- | --
MD5 | `EDB3046610020EE614B5B81B0439895E`
SHA1 | `91028DFE99684C06EA95E35DEDE206BFAF2125D7`
SHA256 | `9AD24FF20594B4DF37BFC87236868D905F51F13BF9C6F1474B1736C8E7BEFD24`
SHA384 | `62FC3A0AB0ED6587DD7E2E7864581EDC5C80752F458225F5E0946F0D6631994CAFE421A1F31A4B93B622DC8475637248`
SHA512 | `E21E83FD1BEBC9F1A5DA12BF232C7D3BF9ECCE113F3413C72449269D0A63600BCD7A6FDFF830C70B0E05A265A896AFC839FAAE2F6F50E654C2FF155578E60A5C`
SSDEEP | `768:8nSY3YHdMhk+5/06A7pi2xFX2NjNcSxrjAqCZuv:rY3ydEk+5/s7pi2xsNhlgZuv`
IMP | `0C997052163F246EEDF66BB131BFC0A3`
PESHA1 | `3C0AF4D020C56C870B87E942EBD0CBDA8541D1BF`
PE256 | `0785E6321EF31691984AD9C2AB65F09161EB17518C4D6477DFD862EE889F6590`

## Runtime Data

### Usage (stdout):
```cmhg
Displays output one screen at a time.

MORE [/E [/C] [/P] [/S] [/Tn] [+n]] < [drive:][path]filename
command-name | MORE [/E [/C] [/P] [/S] [/Tn] [+n]]
MORE /E [/C] [/P] [/S] [/Tn] [+n] [files]

    [drive:][path]filename  Specifies a file to display one
                            screen at a time.

    command-name            Specifies a command whose output
                            will be displayed.

    /E      Enable extended features
    /C      Clear screen before displaying page
    /P      Expand FormFeed characters
    /S      Squeeze multiple blank lines into a single line
    /Tn     Expand tabs to n spaces (default 8)

            Switches can be present in the MORE environment
            variable.

    +n      Start displaying the first file at line n

    files   List of files to be displayed. Files in the list
            are separated by blanks.

    If extended features are enabled, the following commands
    are accepted at the -- More -- prompt:

    P n     Display next n lines
    S n     Skip next n lines
    F       Display next file
    Q       Quit
    =       Show line number
    ?       Show help line
    <space> Display next page
    <ret>   Display next line

```

### Usage (stderr):
```cmhg
Cannot access file C:\Users\user\--help

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\more.com |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MORE.COM
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/9ad24ff20594b4df37bfc87236868d905f51f13bf9c6f1474b1736c8e7befd24/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## more

Displays one screen of output at a time.

> [!NOTE]
> The **more** command, with different parameters, is also available from the Recovery Console.

### Syntax

```
<command> | more [/c] [/p] [/s] [/t<n>] [+<n>]
more [[/c] [/p] [/s] [/t<n>] [+<n>]] < [<drive>:][<path>]<filename>
more [/c] [/p] [/s] [/t<n>] [+<n>] [<files>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<command>` | Specifies a command for which you want to display the output. |
| /c | Clears the screen before displaying a page. |
| /p | Expands form-feed characters. |
| /s | Displays multiple blank lines as a single blank line. |
| /t`<n>` | Displays tabs as the number of spaces specified by *n*. |
| +`<n>` | Displays the first file, beginning at the line specified by *n*. |
| `[<drive>:][<path>]<filename>` | Specifies the location and name of a file to display. |
| `<files>` | Specifies a list of files to display. Files must be separated using spaces. |
| /? | Displays help at the command prompt. |

##### Remarks

- The following subcommands are accepted at the **more** prompt (`-- More --`), including:

    | Key | Action |
    | --- | ------ |
    | SPACEBAR | Press the **SPACEBAR** to display the next screen. |
    | ENTER | Press **ENTER** to display the file one line at a time. |
    | f | Press **F** to display the next file listed on the command line. |
    | q | Press **Q** to quit the **more** command. |
    | = | Shows the line number. |
    | p `<n>` | Press **P** to display the next *n* lines. |
    | s `<n>` | Press **S** to skip the next *n* lines. |
    | ? | Press **?** to show the commands that are available at the **more** prompt.|

- If you use the redirection character (`<`), you must also specify a file name as the source.

- If you use the pipe (`|`), you can use such commands as **dir**, **sort**, and **type**.

#### Examples

To view the first screen of information of a file named *Clients.new*, type one of the following commands:

```
more < clients.new
type clients.new | more
```

The **more** command displays the first screen of information from Clients.new, and you can press the SPACEBAR to see the next screen of information.

To clear the screen and remove all extra blank lines before displaying the file *Clients.new*, type one of the following commands:

```
more /c /s < clients.new
type clients.new | more /c /s
```

To display the current line number at the **more** prompt, type:

```
more =
```

The current line number is added to the **more** prompt, as `-- More [Line: 24] --`

To display a specific number of lines at the **more** prompt, type:

```
more p
```

The **more** prompt asks you for the number of lines to display, as follows: `-- More -- Lines:`. Type the number of lines to display, and then press ENTER. The screen changes to show only that number of lines.

To skip a specific number of lines at the **more** prompt, type:

```
more s
```

The **more** prompt asks you for the number of lines to skip, as follows: `-- More -- Lines:`. Type the number of lines to skip, and then press ENTER. The screen changes to show that those lines are skipped.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Windows Recovery Environment (WinRE)](/windows-hardware/manufacture/desktop/windows-recovery-environment--windows-re--technical-reference)

---



MIT License. Copyright (c) 2020-2021 Strontic.


