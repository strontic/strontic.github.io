---
title: choice.exe | Offers the user a choice
excerpt: What is choice.exe?
---

# choice.exe 

* File Path: `C:\Windows\SysWOW64\choice.exe`
* Description: Offers the user a choice

## Hashes

Type | Hash
-- | --
MD5 | `D2255B85CA041A1B59D2B245374EFD04`
SHA1 | `6C737FAA6B7DA3E605AF6612F92406526B1F1A68`
SHA256 | `58900C00BA169518386D4F114A91EDEF83C2CC1040CC1A0210449F86B1104453`
SHA384 | `1403BFA2D48D77732D6834FD23DC668A8AA81AB6084D85FD1C9F6DC42D6CED0520815D3F45637BEE60B94E45340A9DEF`
SHA512 | `2A0E484D9C7C37DD158261FA0ECDF079A9FBCCA136AA9AFEB4A60652A0CAE09618B6EE54E0A5EF61CBEB9DA510ACB8ED1BEDB38F0C83B1BF4E2E49E69A05BE0D`
SSDEEP | `768:1rfF0eHcc1s2U+AnDLzGiX75W59NDah9VCxGrdHkV:1rfF0e8EhB0PzGilWBDah94xiHkV`
IMP | `A445244C63114214072FAF6C3DCE1438`
PESHA1 | `49E48EB3AD533F34A2FC5D017D3BAF1556122ADF`
PE256 | `F8E0F458B7397A2C05A7C0614FB7C134C904E7CEBC93EF27518E2B1DEB332FB2`

## Runtime Data

### Usage (stdout):
```cmhg

CHOICE [/C choices] [/N] [/CS] [/T timeout /D choice] [/M text]

Description:
    This tool allows users to select one item from a list 
    of choices and returns the index of the selected choice.

Parameter List:
   /C    choices       Specifies the list of choices to be created.
                       Default list is "YN".

   /N                  Hides the list of choices in the prompt.
                       The message before the prompt is displayed
                       and the choices are still enabled.

   /CS                 Enables case-sensitive choices to be selected.
                       By default, the utility is case-insensitive.

   /T    timeout       The number of seconds to pause before a default 
                       choice is made. Acceptable values are from 0 to 
                       9999. If 0 is specified, there will be no pause 
                       and the default choice is selected.

   /D    choice        Specifies the default choice after nnnn seconds.
                       Character must be in the set of choices specified
                       by /C option and must also specify nnnn with /T.

   /M    text          Specifies the message to be displayed before 
                       the prompt. If not specified, the utility 
                       displays only a prompt.

   /?                  Displays this help message.

   NOTE:
   The ERRORLEVEL environment variable is set to the index of the
   key that was selected from the set of choices. The first choice
   listed returns a value of 1, the second a value of 2, and so on.
   If the user presses a key that is not a valid choice, the tool 
   sounds a warning beep. If tool detects an error condition,
   it returns an ERRORLEVEL value of 255. If the user presses 
   CTRL+BREAK or CTRL+C, the tool returns an ERRORLEVEL value
   of 0. When you use ERRORLEVEL parameters in a batch program, list
   them in decreasing order.

Examples:
   CHOICE /?
   CHOICE /C YNC /M "Press Y for Yes, N for No or C for Cancel."
   CHOICE /T 10 /C ync /CS /D y 
   CHOICE /C ab /M "Select a for option 1 and b for option 2."
   CHOICE /C ab /N /M "Select a for option 1 and b for option 2."

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "CHOICE /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: choice.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/58900c00ba169518386d4f114a91edef83c2cc1040cc1a0210449f86b1104453/detection/


## Possible Misuse

*The following table contains possible examples of `choice.exe` being misused. While `choice.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `Description: Change HKLM\Software\Microsoft\WAB\DLLPath and execute DLL of choice` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Maldoc choice flags command execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Maldoc choice flags command execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | - [Atomic Test #3 - Maldoc choice flags command execution](#atomic-test-3---maldoc-choice-flags-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | ## Atomic Test #3 - Maldoc choice flags command execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $macrocode = "  a = Shell(`"cmd.exe /c choice /C Y /N /D Y /T 3`", vbNormalFocus)" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) | - Try to run the script: "python runner.py interactive".  Try to run the technique of your choice. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x5 = "If one choice fails, you may want to try another." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "[-] Error: Exploit choice not supported for target OS!!" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_backnet.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_backnet.yar) | $s6 = "/C choice /C Y /N /D Y /T 4 & Del" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "if not \"%Choice%\"==\"\" set Choice=%Choice:~0,1%" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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


