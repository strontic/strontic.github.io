
# clip.exe 

* File Path: `C:\Windows\system32\clip.exe`
* Description: Clip - copies the data into clipboard
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `020308633CC047DB3026FE49ED9A8363`
SHA1 | `497E1981B6943E81E350AC6B8CD34E463F245B83`
SHA256 | `B57333B76E5CAABC4B8A8AE4264CD664E1EEEC3CC4A7F6BED76C23D53B5418DA`
SHA384 | `C9AF5A8C9AB9C0136822D35FD72C204FFDE29E573C2230633E28A28D84EA2F09E8760C270C84CD2677BB671997543F9E`
SHA512 | `578CBB625E9B29ABE9CD7002002E6FA3F132E53ACA9E712EDF7790FF832AFDC9F83160555D46A8403D5425F1A1B1A0D30C9E896DF6A2E95F3056C9B294B7B874`
SSDEEP | `768:ZtTxvqQ5ch96j6O3VRiSXALa3cAefgy6x5YCM:fT9vzpcAefwxCC`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# clip

Redirects the command output from the command line to the Windows clipboard. You can use this command to copy data directly into any application that can receive text from the Clipboard. You can also paste this text output into other programs.

## Syntax

```
<command> | clip
clip < <filename>
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<command>` | Specifies a command whose output you want to send to the Windows clipboard. |
| `<filename>` | Specifies a file whose contents you want to send to the Windows clipboard. |
| /? | Displays help at the command prompt. |

## Examples

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

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


