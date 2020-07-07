---
title: choice.exe | Offers the user a choice
---

# choice.exe 

* File Path: `C:\windows\SysWOW64\choice.exe`
* Description: Offers the user a choice
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3BD56F470A31D10BAF438EDD33DE862A`
SHA1 | `71A6293B5BD8E8071812940175CB0EF8E147B7B2`
SHA256 | `6DC1433C83950AE8CF06FAE2248D9762B18F3D5B16B89B51750F5D87C625ABFB`
SHA384 | `55598A74351BC8306BF45A7A50A913946A3CF381BDBA4F7EA767C11FE77AE8781BDA60BF85C1868FA751101F932CCC4B`
SHA512 | `6F254DDDF7962A39F009A6C91C525C32509E4BF54E8CD0C0AF19B45BA665445453D95748D8F154267F175C8E575B760848E90B612A9DA40227244E561861FBB8`
SSDEEP | `768:+rfTk9wk24YUHBeZbEMs1sMLGxYHpndC:+rf0d9VHUBIsMaxYJnd`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\choice.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: choice.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `choice.exe` being misused. While `choice.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `    Description: Change HKLM\Software\Microsoft\WAB\DLLPath and execute DLL of choice` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #3: Maldoc choice flags command execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #3: Maldoc choice flags command execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | - [Atomic Test #3 - Maldoc choice flags command execution](#atomic-test-3---maldoc-choice-flags-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | ## Atomic Test #3 - Maldoc choice flags command execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $macrocode = "  a = Shell(`"cmd.exe /c choice /C Y /N /D Y /T 3`", vbNormalFocus)" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) | - Try to run the script: "python runner.py interactive".  Try to run the technique of your choice. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## choice

Prompts the user to select one item from a list of single-character choices in a batch program, and then returns the index of the selected choice. If used without parameters, **choice** displays the default choices **Y** and **N**.

### Syntax

```
choice [/c [<choice1><choice2><â€¦>]] [/n] [/cs] [/t <timeout> /d <choice>] [/m <text>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /c `<choice1><choice2><â€¦>` | Specifies the list of choices to be created. Valid choices include a-z, A-Z, 0-9, and extended ASCII characters (128-254). The default list is YN, which is displayed as `[Y,N]?`. |
| /n | Hides the list of choices, although the choices are still enabled and the message text (if specified by **/m**) is still displayed. |
| /cs | Specifies that the choices are case-sensitive. By default, the choices are not case-sensitive. |
| /t `<timeout>` | Specifies the number of seconds to pause before using the default choice specified by **/d**. Acceptable values are from **0** to **9999**. If **/t** is set to **0**, **choice** does not pause before returning the default choice. |
| /d `<choice>` | Specifies the default choice to use after waiting the number of seconds specified by **/t**. The default choice must be in the list of choices specified by **/c**. |
| /m `<text>` | Specifies a message to display before the list of choices. If **/m** is not specified, only the choice prompt is displayed. |
| /? | Displays help at the command prompt. |

### Remarks

- The **ERRORLEVEL** environment variable is set to the index of the key that the user selects from the list of choices. The first choice in the list returns a value of `1`, the second a value of `2`, and so on. If the user presses a key that is not a valid choice, **choice** sounds a warning beep.

- If **choice** detects an error condition, it returns an **ERRORLEVEL** value of `255`. If the user presses CTRL+BREAK or CTRL+C, **choice** returns an **ERRORLEVEL** value of `0`.

> [!NOTE]
> When you use **ERRORLEVEL** values in a batch program, you must list them in decreasing order.

### Examples

To present the choices **Y**, **N**, and **C**, type the following line in a batch file:

```
choice /c ync
```

The following prompt appears when the batch file runs the **choice** command:

```
[Y,N,C]?
```

To hide the choices **Y**, **N**, and **C**, but display the text **Yes**, **No**, or **Continue**, type the following line in a batch file:

```
choice /c ync /n /m Yes, No, or Continue?
```

> [!NOTE]
> If you use the **/n** parameter, but do not use **/m**, the user is not prompted when **choice** is waiting for input.

To show both the text and the options used in the previous examples, type the following line in a batch file:

```
choice /c ync /m Yes, No, or Continue
```

To set a time limit of five seconds and specify **N** as the default value, type the following line in a batch file:

```
choice /c ync /t 5 /d n
```

> [!NOTE]
> In this example, if the user doesn't press a key within five seconds, **choice** selects **N** by default and returns an error value of `2`. Otherwise, **choice** returns the value corresponding to the user's choice.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


