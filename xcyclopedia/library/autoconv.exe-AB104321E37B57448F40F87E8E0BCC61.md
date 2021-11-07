---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\system32\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `AB104321E37B57448F40F87E8E0BCC61`
SHA1 | `25519383AF4B8026245576BA08A60E184374B268`
SHA256 | `A3172D37531665F5528E5B6831CC00644694B95CE3CCEDCB32F1F0997DE22465`
SHA384 | `BA734B979EC72458B599BFADB0D8C9930AB1AEB6B9386DBB9A3DE7329CB5408459E8968C28674F310A4011E0E873E57F`
SHA512 | `B0305C5F9E0454A7F3ACA12141179BADA0D3E40ADDDA5AFBB8943705E0B303043C62E3BC6FB243A9A0828A1C93F38EE59E74FF62E2677AA285A1F6EE5B0BE675`
SSDEEP | `12288:f1IOvjjGQg42skB3hI6CWbbLNCcDQfHeCJ0fXYxoIOJ21g3r:f1RWf42ss3FdbbLwcDQf+Cifwgb`
IMP | `918C8F06B30D99678E0281D170345BB8`
PESHA1 | `EFDC541EF8B2F83D126109DD081C4E6E26F0B60C`
PE256 | `B1A484D2CF5332D0A58398C4ADDF39EB8FF28E569F064C768DDEF2028EEF3341`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.662 (WinBuild.160101.0800)
* Product Version: 10.0.19041.662
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a3172d37531665f5528e5b6831cc00644694b95ce3ccedcb32f1f0997de22465/detection



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


