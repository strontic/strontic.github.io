---
title: HOSTNAME.EXE | Hostname APP
excerpt: What is HOSTNAME.EXE?
---

# HOSTNAME.EXE 

* File Path: `C:\WINDOWS\SysWOW64\HOSTNAME.EXE`
* Description: Hostname APP

## Hashes

Type | Hash
-- | --
MD5 | `DE8182A97CDC78B2363923EDF2674768`
SHA1 | `995A147AA4FD5B15F8F0DEA631FF75CF9F2AA375`
SHA256 | `4411072B3153B90D45E368710E672992C7909F4D20AB1BAA6F0DD02C3821D2A1`
SHA384 | `339B14E44461DE22506D9698066F0AE72AAA4B847BB30A2BA232CBA3D527AEC589100D7D8CE2EB104C116EF840D8FFE4`
SHA512 | `3BDBAFE9169A0906E942D5C5EF77082FBCDACB93165A481A338554EF014B03BBB6F50B6636DAD8EF3183B479AD52F976EDBA4C6B64A755608101DF00D9CE8E46`
SSDEEP | `192:cmpQ5zhNb6T5dpvksk4lvXGgkwGQf0VjwrWG6WLfQ:zpQdDb6T5dBlvf7kVYWG6Wr`
IMP | `A4063DB4A815F52872CED059021A8B79`
PESHA1 | `83EBC0792CE349C9DF160A69B7EA606382D3320A`
PE256 | `65A0F5FC456B745DF6B4073E74AAE9AB1F67B68E13D3D252A8332F5FE424F682`

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\HOSTNAME.EXE |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hostname.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/4411072b3153b90d45e368710e672992c7909f4d20ab1baa6f0dd02c3821d2a1/detection


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

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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

Any parameter different than `/?` produces an error message and sets the errorlevel to 1.

#### Notes

- Environment variable `%COMPUTERNAME%` usually will print the same string as `hostname`, but in uppercase.
- If environment variable `_CLUSTER_NETWORK_NAME_` is defined, `hostname` will print its value.

#### Examples

- To display the name of the computer, type:

```shell
hostname
```

- To display the name of the computer in uppercase:

```shell
echo %COMPUTERNAME%
```

- To alter the hostname output:

```shell
set "_CLUSTER_NETWORK_NAME_=Altered Computer Name"
hostname
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


