---
title: clip.exe | Clip - copies the data into clipboard
excerpt: What is clip.exe?
---

# clip.exe 

* File Path: `C:\Windows\SysWOW64\clip.exe`
* Description: Clip - copies the data into clipboard

## Hashes

Type | Hash
-- | --
MD5 | `E40CB198EBCD20CD16739F670D4D7B74`
SHA1 | `E898A3B321BD6734C5A676382B5C0DFD42BE377D`
SHA256 | `6CDC8D3C147DCF7253C0FB7BB552B4AE918ABA4058CC072A2320A7297D4FBED7`
SHA384 | `EC95F7C7CC1D0F72AC9ABCF24C6BECA45B9B01F3E42945A308302311943064D237159AB647E535BB1BD039640DFCBFFA`
SHA512 | `1E5A68B2AE30C7D16A0A74807FA069BE2D1B8ADCFCBCDE777217B9420A987196AF13FB05177E476157029A1F7916E6948A1286CDB8957CDD142756DA3C42BEEF`
SSDEEP | `384:R7OPm5RmB6C+DlVbrb6IQhH48oOhQ76pXeEYfM3G8HIdkLWXKQAF900kdxLd73NV:R7OPQc+DlVbrvQhYWhQ+BeEYfyRHPcZl`
IMP | `2E4F8B6217B6FC3E22F837FF8337F26B`
PESHA1 | `5FDD96068858E1DFD8414A1B87589B2C0FE15FEC`
PE256 | `76A402561ADE86AA7E2C6D1850B8ACD5E779BDBAB2EA3AEA1F3F9DE52C3289AC`

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
ERROR: Invalid argument/option - '--help'.
Type "CLIP /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\clip.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clip.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/6cdc8d3c147dcf7253c0fb7bb552b4ae918aba4058cc072a2320a7297d4fbed7/detection/



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


