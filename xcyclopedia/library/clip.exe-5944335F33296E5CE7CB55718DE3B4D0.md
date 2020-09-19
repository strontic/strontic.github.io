---
title: clip.exe | Clip - copies the data into clipboard
---

# clip.exe 

* File Path: `C:\WINDOWS\SysWOW64\clip.exe`
* Description: Clip - copies the data into clipboard

## Hashes

Type | Hash
-- | --
MD5 | `5944335F33296E5CE7CB55718DE3B4D0`
SHA1 | `AC2EC0F5BD7421B3618E476C6339943D27A1A717`
SHA256 | `B1FC6760432BAD0591F5EEFC461F54592DE3BA7818B785B0DCF5128C0C6BF251`
SHA384 | `F98D8CA434A4193C8E79411CE16D91FC719B2CF6DCFBBFC59E8853C225A0CE8526E5FA5C958BA00EAB09AB49F437058F`
SHA512 | `8F75EDFFE9E0718BD274E9467E0E2DCEADBDD88BBE2B9E16B0AD16A9EDA4CA2C2D0DDC79993A8CAE9A26022577528C4CD1ADF0E5966ECB5C97D3F8068416A513`
SSDEEP | `384:c47OPcU1zF6Bl+DlVhXbG/QgHWoQYHq/xx1vveKTfUrb4qZsdnBQFojN1Gx+gnL8:rOP7NFW+DlVhXUQgDK/71vveKU3aBBQ9`

## Runtime Data

### Usage (stdout):
```cmhg

CLIP

Description:
    Redirects output of command line tools to the Windows clipboard.
    This text output can then be pasted into other programs.

Parameter List:
    /?                  Displays this help message.

Examples:
    DIR | CLIP          Places a copy of the current directory
                        listing into the Windows clipboard.

    CLIP < README.TXT   Places a copy of the text from readme.txt
                        on to the Windows clipboard.

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '-help'.
Type "CLIP /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clip.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


