---
title: clip.exe | Clip - copies the data into clipboard
---

# clip.exe 

* File Path: `C:\windows\system32\clip.exe`
* Description: Clip - copies the data into clipboard

## Hashes

Type | Hash
-- | --
MD5 | `9CEE8395B3EBC0CC33D0FA54DC65CC61`
SHA1 | `F3EA5EA218D4D292F011FFEF73EDC384CF4F489E`
SHA256 | `E0A3648BCC1F0F0AA9AFD9E5031AFE0897BC5A10FED9A1B7984ADACD119B4F10`
SHA384 | `C12C6F70E55243F94D4FA4D272F6DC8FF3E4AF56815FBE2BD4430831430D0B53C9D13244A5C73B669053E788D34BFB15`
SHA512 | `1055807C06E65D833B5A87170EA662229C91A400B8323D6DDBDD42D151A71E14286FAA624FC6EE722EEFFDC85B1F788E11F1BFEC60C64B802D121120B9BB762C`
SSDEEP | `768:Ne/UiG8x3NB8jF0oD0eqsaXGPFokaVP+k2xwwL:Ne/UVab8xQG+kad+nxVL`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\clip.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\windows\system32\clip.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: clip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## clip

Redirects the command output from the command line to the Windows clipboard. You can use this command to copy data directly into any application that can receive text from the Clipboard. You can also paste this text output into other programs.

### Syntax

```
<command> | clip
clip < <filename>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<command>` | Specifies a command whose output you want to send to the Windows clipboard. |
| `<filename>` | Specifies a file whose contents you want to send to the Windows clipboard. |
| /? | Displays help at the command prompt. |

### Examples

To copy the current directory listing to the Windows clipboard, type:

```
dir | clip
```

To copy the output of a program called *generic.awk* to the Windows clipboard, type:

```
awk -f generic.awk input.txt | clip
```

To copy the contents of a file called *readme.txt* to the Windows clipboard, type:

```
clip < readme.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


