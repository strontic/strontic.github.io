---
title: chcp.com | Change CodePage Utility
excerpt: What is chcp.com?
---

# chcp.com 

* File Path: `C:\Windows\system32\chcp.com`
* Description: Change CodePage Utility

## Hashes

Type | Hash
-- | --
MD5 | `CA9A549C17932F9CAA154B5528EBD8D4`
SHA1 | `8168E58C6C297D0943CEF9B84A05B75476C1D9E5`
SHA256 | `1F29DA3086E3BCD9F191528FF7B47BD5070509199A63DAB7A19BF39D21A7F618`
SHA384 | `509B1853AF563A11E5AD5F0882284F9A8B5DE7FCB1A4302A798E0CDD74E6D2F985920112A99CF59710860AB89318362D`
SHA512 | `124CC7D4A4ACD9FDF445F3C90805F1CB60A995100DCC4A6EC701760CAA5D6539EF535BF37687D664D8DE3D45E4E6445184DA00852669D020029F8494619E7AF2`
SSDEEP | `192:6WKx09ZtMxrqFXldYLaJPW0rNvjCJZUCGdlkzRUiBBqU4lywmtPWpUW:6WB9ZtMp46LW5r12cCrNqUvtPWpUW`
IMP | `75FA51C548B19C4AD5051FAB7D57EB56`
PESHA1 | `D01926C54B3E2C1D82CB4818BF6CE0C687BBA413`
PE256 | `D22FDAC8D536664470BE6727F6ADD6C7E53986FCF9B21E23C5D4AD15258CBF85`

## Runtime Data

### Usage (stdout):
```cmhg
Displays or sets the active code page number.

CHCP [nnn]

  nnn   Specifies a code page number.

Type CHCP without a parameter to display the active code page number.

```

### Usage (stderr):
```cmhg
Parameter format not correct - --help

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\chcp.com |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CHCP.COM
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/1f29da3086e3bcd9f191528ff7b47bd5070509199a63dab7a19bf39d21a7f618/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## chcp

Changes the active console code page. If used without parameters, **chcp** displays the number of the active console code page.

### Syntax

```
chcp [<nnn>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<nnn>` | Specifies the code page. |
| /? | Displays help at the command prompt. |

The following table lists each supported code page and its country/region or language:

| Code page | Country/region or language |
| --------- | -------------------------- |
| 437 | United States |
| 850 | Multilingual (Latin I) |
| 852 | Slavic (Latin II) |
| 855 | Cyrillic (Russian) |
| 857 | Turkish |
| 860 | Portuguese |
| 861 | Icelandic |
| 863 | Canadian-French |
| 865 | Nordic |
| 866 | Russian |
| 869 | Modern Greek |
| 936 | Chinese |

##### Remarks

- Only the original equipment manufacturer (OEM) code page that is installed with Windows appears correctly in a Command Prompt window that uses Raster fonts. Other code pages appear correctly in full-screen mode or in Command Prompt windows that use TrueType fonts.

- You don't need to prepare code pages (as in MS-DOS).

- Programs that you start after you assign a new code page use the new code page. However, programs (except Cmd.exe) that you started before assigning the new code page will continue to use the original code page.

### Examples

To view the active code page setting, type:

```
chcp
```

A message similar to the following appears: `Active code page: 437`

To change the active code page to 850 (Multilingual), type:

```
chcp 850
```

If the specified code page is invalid, the following error message appears: `Invalid code page`

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


