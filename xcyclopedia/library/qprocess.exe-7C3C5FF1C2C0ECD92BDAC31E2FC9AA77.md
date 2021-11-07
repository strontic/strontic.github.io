---
title: qprocess.exe | Query Process Utility
excerpt: What is qprocess.exe?
---

# qprocess.exe 

* File Path: `C:\windows\system32\qprocess.exe`
* Description: Query Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `7C3C5FF1C2C0ECD92BDAC31E2FC9AA77`
SHA1 | `ADFDD872880B51D8EAF34663A0105A6AFBFB9E93`
SHA256 | `8C6E84197282F283347D8426E695BBDCFCD24E29EB49B077783F666891A1431D`
SHA384 | `CE6F81D46229F7E832B2504D7CC2A584100268514E051672D6925300173F9AF23A60A73917F2EB85D5BB57FEEA39FBFC`
SHA512 | `D7C73498CA513C848BA140629FA676FE1C511B541EBC7775C1A87EB04D0FF12717AA8404F2B76D86D68A75854132AC5A4D1B8F175F321759F6B436D1A9ECF94A`
SSDEEP | `384:O/Xk76DdPJ3Ukq7Cae5TddQrYpwDgZVwid7cTraEP55Ks63VkgszNhodGbASbGia:zmdPhdZ15dKU2DEQ/oz3VkpfyG0yrBF`

## Signature

* Status: The file C:\windows\system32\qprocess.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- qprocess`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $ = "qprocess" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qprocess

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about processes that are running on a Remote Desktop Session Host server. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


