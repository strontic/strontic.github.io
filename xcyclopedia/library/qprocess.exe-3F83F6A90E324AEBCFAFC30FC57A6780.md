---
title: qprocess.exe | Query Process Utility
excerpt: What is qprocess.exe?
---

# qprocess.exe 

* File Path: `C:\windows\SysWOW64\qprocess.exe`
* Description: Query Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `3F83F6A90E324AEBCFAFC30FC57A6780`
SHA1 | `1D2FC35A90FFE1CE08EB628E95F4D4E8B5FC8A93`
SHA256 | `B9E673F60FD682B29A66AB3E819A8E1100F2A3621BEF102BA71AF66B072E9600`
SHA384 | `88E3ECA8A5F0761CC1654C7C3D022A92BA4D4C3878A1C17E73E54E9B6BCA0EDE3D6E23AE1C4B5B865C41B24D4F503BF0`
SHA512 | `CFD51292796BC73F70504576A3224A5EE1C1C3F6C6095B5540FE0458A7C089B4B1B02785422BE81D6FAC12931F62160B85D173693D67C3FC86EE1C4A8DE9657E`
SSDEEP | `384:il3sMgeIy0pL4k068i9h9Q5GDRTqGzjBakXJ+hBk2r+kZWLvE+2Wc:5Rx4k0I5b9kVF`

## Signature

* Status: The file C:\windows\SysWOW64\qprocess.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: qprocess.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `qprocess.exe` being misused. While `qprocess.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- qprocess` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $ = "qprocess" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qprocess

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about processes that are running on a Remote Desktop Session Host server. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


