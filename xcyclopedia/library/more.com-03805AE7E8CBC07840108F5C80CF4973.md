---
title: more.com | More Utility
excerpt: What is more.com?
---

# more.com 

* File Path: `C:\Windows\SysWOW64\more.com`
* Description: More Utility

## Hashes

Type | Hash
-- | --
MD5 | `03805AE7E8CBC07840108F5C80CF4973`
SHA1 | `DD04DD9405E6446EB2A95FD91835D8409B637D9B`
SHA256 | `FE65540F70C1A4C7D9625F8DC8F81FC47BACD0FFB65CB4B147E20B27A7D5D709`
SHA384 | `51E3E5862D82902EBB55717B13916CAC89C246A6FAFAC472938BA756F192B9DD76D6E571CA3F7D3AC5CB2BA78EC887A9`
SHA512 | `39072E8F33EF2E5B909941B8AA6ECBE8EDC4BC4F8845D2460EEA32BE06E3E85E3F1C193CE7727FC07B3D8B43C288E6874CA0063544084C85C6335BE8BAFC25AD`
SSDEEP | `384:LOPYvR2NjqhKwQQwYRzLGv7BUT+g4w+AzCgHabZRnWMZWk6:Cgg1qhXTnZSFUyg4UCgaZRPq`
IMP | `0FECE6298CCD2180CC9F1B7C9F0969E2`
PESHA1 | `9A3198408A28ECA2019B35082EE00FE4F16D9711`
PE256 | `0A49FDEF1A86823253476FB1E0777209F41880A5B14816652DB267539BCBD251`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\more.com |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/fe65540f70c1a4c7d9625f8dc8f81fc47bacd0ffb65cb4b147e20b27a7d5d709/detection



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


