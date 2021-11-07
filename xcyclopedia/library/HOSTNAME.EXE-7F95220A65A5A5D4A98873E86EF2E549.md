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
MD5 | `7F95220A65A5A5D4A98873E86EF2E549`
SHA1 | `28BFFEA3033FDAED22759324FE691992FB533A9C`
SHA256 | `1BFF2907C456F99277F45F9B2A21B1B3F11F6C01587D9E6D6F0B2B5F1472FE92`
SHA384 | `FC43816F09F42FFA85EF1E0E6F9794D90DDB224F785100E991049BF098B652BE894EB7343FB3E1AF4013D460BAC07185`
SHA512 | `6F88603EE204D1131E37515D198D663549D73C0B5D2127CC88DCA1E5FD4DC7CC2EDBBD0E425AC330DAA746564578AF9344909B1C7B939D0762B9B9B38D31C42A`
SSDEEP | `192:OxyxH6lzKFcnrRYUvZfdsCEeQgEebGXgEXabtwlQNWa6W:GyUuFoFPvraNkg8bttWa6W`
IMP | `5CD891320C666621E9783444DB8CBA78`
PESHA1 | `ECCF136EB2AB43DF9F07D30F48533A0E284E2653`
PE256 | `5FC6E42C17DB2DC8F5F91CC2FFA6579F7B20FE01D27BC301586108E66019D5E9`

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

* Original Filename: hostname.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/1bff2907c456f99277f45f9b2a21b1b3f11f6c01587d9e6d6f0b2b5f1472fe92/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\HOSTNAME.EXE](HOSTNAME.EXE-612DBA11F1DFAD1998609A647B740B34.md) | 69

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


