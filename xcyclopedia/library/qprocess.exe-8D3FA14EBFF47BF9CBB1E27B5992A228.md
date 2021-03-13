---
title: qprocess.exe | Query Process Utility
excerpt: What is qprocess.exe?
---

# qprocess.exe 

* File Path: `C:\Windows\system32\qprocess.exe`
* Description: Query Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `8D3FA14EBFF47BF9CBB1E27B5992A228`
SHA1 | `7EAF631ECBE8258AFE32BFB890CEACA1D13737AA`
SHA256 | `7EE7A6FB1BDD972502D1EB23B7BD471A66CAD63CA3B57D787A173FB290808EB6`
SHA384 | `263838CE532FD563A7CC7887CA39668634858D50201B2FB03F0B966686D708A5705837D78D222140FB7F356989E707BC`
SHA512 | `DFF0CBDACCA1C850A3C5F8BB851647B60FDA6352F2FB486B90B0005F79E1D3A8651703EE0F634E967047DCB25E396CE2B5E235B3694D5B1C78D97E5B731F6153`
SSDEEP | `768:w8igjPq3JqPcvSphuU1EK8vB0MCYnvAMODDM:ZGZipYfB06InM`
IMP | `2C0AA5527727A67BD252EF9D0F3BEB31`
PESHA1 | `65E412C36503BCCE42A28F99245599158FBAFED2`
PE256 | `DFEC3B3D0DBA5EF66138F833A7A03F1FF28C3CA20BD8154C5CBE60F5820E72E4`

## Runtime Data

### Usage (stdout):
```cmhg
Displays information about processes.

QUERY PROCESS [* | processid | username | sessionname | /ID:nn | programname]
  [/SERVER:servername]

  *                  Display all visible processes.
  processid          Display process specified by processid.
  username           Display all processes belonging to username.
  sessionname        Display all processes running at sessionname.
  /ID:nn             Display all processes running at session nn.
  programname        Display all processes associated with programname.
  /SERVER:servername The Remote Desktop Session Host server to be queried.

```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Displays information about processes.

QUERY PROCESS [* | processid | username | sessionname | /ID:nn | programname]
  [/SERVER:servername]

  *                  Display all visible processes.
  processid          Display process specified by processid.
  username           Display all processes belonging to username.
  sessionname        Display all processes running at sessionname.
  /ID:nn             Display all processes running at session nn.
  programname        Display all processes associated with programname.
  /SERVER:servername The Remote Desktop Session Host server to be queried.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\browcli.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\logoncli.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\qprocess.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\samcli.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\system32\srvcli.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UTILDLL.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qprocess.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/7ee7a6fb1bdd972502d1eb23b7bd471a66cad63ca3b57d787a173fb290808eb6/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\qprocess.exe](qprocess.exe-B9512ABDF1F4982292DC60D11EDA20DF.md) | 69

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

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about processes that are running on a Remote Desktop Session Host server. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


