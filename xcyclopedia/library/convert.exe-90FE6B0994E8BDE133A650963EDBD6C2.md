---
title: convert.exe | File System Conversion Utility
---

# convert.exe 

* File Path: `C:\Windows\SysWOW64\convert.exe`
* Description: File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `90FE6B0994E8BDE133A650963EDBD6C2`
SHA1 | `3D77A83C69C603A4D09DB0EF5D183484EB62E38B`
SHA256 | `D280FF3983AF2B77EEEA7C5D1F021CCCD254444C30F65700DF097328B6E3AD2F`
SHA384 | `F5D0C798B5C26AE8E6181C582C7665CF226BC99618AFEBF0217398F1D6E6D037E56CCBEDE2CC33BCCC2FFAFC3B5C787A`
SHA512 | `E7E1A719F012A1DFF49B58FB68BEB76A8DB310E3914D0E72906E774704C2CFF935482CB8126C2E0A77F38D7CAB4E7B66B6AF3544E112324DB0C31D1387A04628`
SSDEEP | `384:5UXz59OBNRiActWgMgcMXKXHXZTac+7xNzW9qWl:5vPRxctWPJpx6xYZ`

## Runtime Data

### Usage (stdout):
```Batchfile
Converts a FAT volume to NTFS.

CONVERT volume /FS:NTFS [/V] [/CvtArea:filename] [/NoSecurity] [/X]


  volume      Specifies the drive letter (followed by a colon),
              mount point, or volume name.
  /FS:NTFS    Specifies that the volume will be converted to NTFS.
  /V          Specifies that Convert will be run in verbose mode.
  /CvtArea:filename
              Specifies a contiguous file in the root directory
              that will be the place holder for NTFS system files.
  /NoSecurity Specifies that the security settings on the converted
              files and directories allow access by all users.
  /X          Forces the volume to dismount first if necessary.
              All open handles to the volume will not be valid.

```

### Usage (stderr):
```Batchfile
Invalid drive specification.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONVERT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `convert.exe` being misused. While `convert.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_eda.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_eda.yml) | `            - '[Convert]::ToString($SYNOptions, 16)'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_invocation_specific.yml) | `            - '* -nop -w hidden -c * [Convert]::FromBase64String*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | $EncodedCommand =[Convert]::ToBase64String($Bytes) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | powershell.exe -Command "IEX ([Text.Encoding]::UNICODE.GetString([Convert]::FromBase64String((gp #{registry_key_storage} #{registry_entry_storage}).#{registry_entry_storage})))" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | iex ([Text.Encoding]::ASCII.GetString([Convert]::FromBase64String((gp 'HKCU:\Software\Classes\AtomicRedTeam').ART))) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | $Content = [System.Convert]::FromBase64String($key) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## convert

Converts a disk from one disk type to another.

### Syntax

```
convert basic
convert dynamic
convert gpt
convert mbr
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [convert basic command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-basic.md) | Converts an empty dynamic disk into a basic disk. |
| [convert dynamic command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-dynamic.md) | Converts a basic disk into a dynamic disk. |
| [convert gpt command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-gpt.md) | Converts an empty basic disk with the master boot record (MBR) partition style into a basic disk with the GUID partition table (GPT) partition style. |
| [convert mbr command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-mbr.md) | Converts an empty basic disk with the GUID Partition Table (GPT) partition style into a basic disk with the master boot record (MBR) partition style. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


