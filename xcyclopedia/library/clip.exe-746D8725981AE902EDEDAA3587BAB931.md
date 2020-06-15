
# clip.exe 

* File Path: `C:\Windows\SysWOW64\clip.exe`
* Description: Clip - copies the data into clipboard
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `746D8725981AE902EDEDAA3587BAB931`
SHA1 | `B6615758DC266790DF5B31AC40A3612826798B22`
SHA256 | `DD959663068E11CE7BB7ADA4AA0636879A9BB454D7C0FD3085081AD4B1A78D1B`
SHA384 | `534BD1387370350DA1DC544AA0C0E40D6281E11CFA3477CC4FBC42A686E5BF1763B515D569F7040D42E8A468813AE5FE`
SHA512 | `717C1B95D5D9482D445092C1D0163987C3B9F513302B317F326F0E5C8C4A739A2CBD77FC2ADEC405BB9FD25BD121853FF40FE41414D82C61BB7F8FEDED95397F`
SSDEEP | `384:ayjOPnJkDbdN2ORy8zPCHIcIFLTsocw8sCnXz5XxQztQTz9t9x+rt3NHWLTWd:VjOP8L2OR17PL/cw8sCDVxQztQ9nx23z`

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


