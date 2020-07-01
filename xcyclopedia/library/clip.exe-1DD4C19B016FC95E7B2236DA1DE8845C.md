---
title: clip.exe | Clip - copies the data into clipboard
---

# clip.exe 

* File Path: `C:\windows\SysWOW64\clip.exe`
* Description: Clip - copies the data into clipboard
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1DD4C19B016FC95E7B2236DA1DE8845C`
SHA1 | `6174686DF79FB5526668D45B17D607116BC681A3`
SHA256 | `3C677C3B2552414B11013DEAC07C80C12139F71D66064C8E0A255C92CC625E0C`
SHA384 | `AF19772900759F221B66B73C6D0AD5167E5318BA2F47921B45D6E76E27A9003516FB9CBFEE3E56C819B2B2657921C2A5`
SHA512 | `483EF5780B0F293522588047ECA949A5D73FF9560DB629F4EDE48DBC9C835EDFBFC99AB6B32998854E18E584FD5211A53C24E7D2E8D7A0A5C541DE171C8FC9BC`
SSDEEP | `384:1LOP0eBg+HfPdbo9NfFaoFoO+ufarg5E37Zq/twa1STXTddgQO55WFZxoxtBs7Nu:1LOPNBDYNfFv8h37Utwa18dkCLxox07w`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\clip.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


