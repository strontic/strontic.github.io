---
title: clip.exe | Clip - copies the data into clipboard
---

# clip.exe 

* File Path: `C:\Windows\system32\clip.exe`
* Description: Clip - copies the data into clipboard
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `50F2CF199F2EB26D37403C9D7268D81F`
SHA1 | `1DEAA1CDDCC528D30749DCA3CC410EBFE9ADE6C8`
SHA256 | `5AD606BCBBBDB95DDA19C955E4129B436295CAC249E2370FEE3D0285D387CF55`
SHA384 | `C42EF2CE3E5BBF6C4BF5262DD7CAFBB2085A9E39A1AD08F556507AF9DD3C7781A76334D83898AC748C41624D7205BCD4`
SHA512 | `594F89523886B2451222067D196F1A62CAC9EF784B633DF638DDDC0F0E53042FF94C4D0C69751BD352DE3A9D502C5E38115E7CAE32C5772310D2FA3C4906AE2C`
SSDEEP | `768:RKq1nys0lSb7jg4jY5yi+i359SMY1yGiaLefVv0r0x+gNcgs:RKq1BNLdi3scGiaLef+Ixfcg`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "CLIP /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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


