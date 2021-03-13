---
title: HOSTNAME.EXE | Hostname APP
excerpt: What is HOSTNAME.EXE?
---

# HOSTNAME.EXE 

* File Path: `C:\Windows\system32\HOSTNAME.EXE`
* Description: Hostname APP

## Hashes

Type | Hash
-- | --
MD5 | `33AFAA43B84BDEAB12E02F9DBD2B2EE0`
SHA1 | `A57959CB3D0CEA955ACAA5DBA3D1197CD4C7E1A8`
SHA256 | `A90C3FB350A11C6F6A6EFA9607987D924D1DE65E09CA9FAF2E0E0E00531EE335`
SHA384 | `1E7F4D1DF1F887898A8AEA476AB836455B97CC21D8A9B217AFABFF5CD675CD5825FAB7B378C8F3BF2668D2EE3BF7CA16`
SHA512 | `9783343CD311B12860FBA232AFCE9651B6D528C97C532A9E5AD76BB813AFFB923224DC90E7F16D183DFC6990A93C337C584ED3F0BE9927DB293A0B1502110EC5`
SSDEEP | `384:+8ShT761G2Weh3rjhVwVab27enbtKWV6W:+8SqG27rfZK7sb3`
IMP | `5CD891320C666621E9783444DB8CBA78`
PESHA1 | `4724AFE177D3A0107C5FC9DA28C7BFD310EE2AD9`
PE256 | `8B856AF12D2CB9DD13BBCDF9BBF3D0A40AE6E6F36628203573B8DAD9F30C16C1`

## Runtime Data

### Usage (stdout):
```cmhg

Prints the name of the current host.

hostname


```

### Usage (stderr):
```cmhg
sethostname: Use the Network Control Panel Applet to set hostname.
hostname -s is not supported.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\HOSTNAME.EXE |
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

* Original Filename: hostname.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a90c3fb350a11c6f6a6efa9607987d924d1de65e09ca9faf2e0e0e00531ee335/detection


## Possible Misuse

*The following table contains possible examples of `HOSTNAME.EXE` being misused. While `HOSTNAME.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_downloader_v3.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_downloader_v3.yml) | `- '\hostname.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- hostname.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- hostname.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## hostname

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the host name portion of the full computer name of the computer.

>[!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network.

### Syntax

```
hostname
```

#### Parameters
| Parameter | Description |
| ------- | -------- |
| /? | Displays help at the command prompt. |

#### Examples

To display the name of the computer, type:

```
hostname
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


