---
title: HOSTNAME.EXE | Hostname APP
excerpt: What is HOSTNAME.EXE?
---

# HOSTNAME.EXE 

* File Path: `C:\Windows\SysWOW64\HOSTNAME.EXE`
* Description: Hostname APP

## Hashes

Type | Hash
-- | --
MD5 | `5E616C9669D38258231AF5EECDE4E221`
SHA1 | `B99FABC8BA76828FCA672B6CB1B66DD719F95D2B`
SHA256 | `5FB2D17787FFEC622AB296775632F9B7A4BE42CC06D3DA92B4CD6BC288AD035C`
SHA384 | `E4FD0303478DB9C48E2DBDFD36B7001C1FC9A069E1FCD56BEEDBA6974581B2AB7973442955037BBBCC9070DBCF91CB25`
SHA512 | `64ABAF35019AF831ECC3DDC452626E6B7AEF00D07B4990C294C888336D114885E2675C339A752E641CC41DCEFE00D63B9D98C0BAFA2387EDD2E0AA1125EF5FD2`
SSDEEP | `192:9q00yPTs6Aqq6Nz1B1ZWWgfXabxwu7Wa6WEDB:A00GTszqqA1B1gWpbxHWa6WE`
IMP | `2177BAFF198B6BCDCF56F96FB63DD54C`
PESHA1 | `DF65F0A820B215B46F1362DB96A0E9D00CBD8C08`
PE256 | `39CEE0C1111380BE96561BF19AB8BDCF1A8E4CC815157617D4CF50994EAE75DB`

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

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hostname.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/5fb2d17787ffec622ab296775632f9b7a4be42cc06d3da92b4cd6bc288ad035c/detection/


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


