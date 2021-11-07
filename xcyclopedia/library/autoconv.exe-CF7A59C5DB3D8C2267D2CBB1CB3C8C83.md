---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\SysWOW64\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `CF7A59C5DB3D8C2267D2CBB1CB3C8C83`
SHA1 | `3CA9E43C1B10A3695E3306DC12896FA5F8FEBA22`
SHA256 | `86EE7446784D9AFBE3B44EC20825027BAA5D32A45D4EFAF137C360A102BEDC39`
SHA384 | `115B3BA157FFB627FF847C66164F4326E45C3C19D3CD13D55B0C1678FA6FEE05947710948A7C86380794973F977C4BB6`
SHA512 | `A250AB210640F685A21FB08B153E6F3F82E8DBAD84A2FB2F65F9E38CFB7991B79D55D5491D96B3AAF9DFD4479C8548BEA8B935E96E9FEA757B73423E9E96B49D`
SSDEEP | `24576:UAY+hdi0XCCQ9cFzELM7VOkKNjFUIGQ/Unp4xJbV:UkirnmxELMpOkKhNGQ/Q4xJb`
IMP | `5DF399086BF351F35499EE0E042BEE31`
PESHA1 | `677924614F3857A803C3AE64286228104FA8A269`
PE256 | `0C9379D5DFD1F81539DF432A5B195C9374FF574003C747E32E4434E5B91F72FD`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.662 (WinBuild.160101.0800)
* Product Version: 10.0.19041.662
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/86ee7446784d9afbe3b44ec20825027baa5d32a45d4efaf137c360a102bedc39/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


