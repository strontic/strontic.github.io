---
title: chcp.com | Change CodePage Utility
excerpt: What is chcp.com?
---

# chcp.com 

* File Path: `C:\Windows\SysWOW64\chcp.com`
* Description: Change CodePage Utility

## Hashes

Type | Hash
-- | --
MD5 | `41146159AA3D41A92B53ED311EE15693`
SHA1 | `05BCF33046A36468E5616E34E4B96063A81F2482`
SHA256 | `5A8A9FAA296AC0CD9F0C384AD60D2EF532A7F6D424E43151528017E1EF309684`
SHA384 | `FF97ABE3B6FF68F6D016C5707E478D2BA769E3E1A73BC6E94F21B70EB2CAECFCC0FEF58083ACE5597196941A069AA29E`
SHA512 | `F6637DCC58C19FD68EB99B530B465E189FA3CD5F1791CCBAF2ABF67A1CE6E7FB319280CE66C1BCDE426C5FC2302C3E3C74E0D5F796E48AD3899672A00998BECA`
SSDEEP | `192:X5113wgb459umu6lDRXB3XBNt2CRsbgz6ktUcWpUWNkGd2:pL3rSQN6TJRsMZtPWpUWNk`
IMP | `0E3EF1D5AC4D1BB3E9EEE3EBCBE63648`
PESHA1 | `7F4234C81A6638D41F7E90F898459014A4458D12`
PE256 | `FB1CE9DBEDA6986E5D08E85A5E81BB1D4646F685DB606F2FE59A9449E994DE35`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\chcp.com |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/5a8a9faa296ac0cd9f0c384ad60d2ef532a7f6d424e43151528017e1ef309684/detection



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


