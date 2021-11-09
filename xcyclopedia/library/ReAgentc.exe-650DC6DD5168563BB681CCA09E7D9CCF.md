---
title: ReAgentc.exe | Microsoft Windows Recovery Agent
excerpt: What is ReAgentc.exe?
---

# ReAgentc.exe 

* File Path: `C:\WINDOWS\system32\ReAgentc.exe`
* Description: Microsoft Windows Recovery Agent

## Hashes

Type | Hash
-- | --
MD5 | `650DC6DD5168563BB681CCA09E7D9CCF`
SHA1 | `5D368DBC3B79BC47496C0B6AF80674E9D9DEF603`
SHA256 | `7F5BA727C557A2AE96B82E00644C098212629A60739BC498D4BD7D374BDBEC75`
SHA384 | `38AB8FC83D8850DAB4F79D2F2A58C5DA55985A89BC70A556C6F24BE03BAB5207F9AF440A66A649FCE08E351160D849EA`
SHA512 | `B213B50C7589B0C46656095C88A7A367898FCD6B3CA8986DB96771015F451A4D42AA33620CEF76148EAF8997E572373CC6A3A5961346D053FE33ABAB3F987BCD`
SSDEEP | `768:v89qK2HsvXTk/q5ea0BUzgqEUiHBG/G812804tIq7vPFk/lmvntqPgO5UZ5N:v89W/aea0W03UiHe1NvtIj/lm/msZ5N`
IMP | `498A49F8301ECECE04F6A27C7229CA18`
PESHA1 | `8898A73967CC1BFD9A507FA2A67DF407D39EE62C`
PE256 | `E2C50F927527774FCA12B59DF18EE110591D7EAB9732FF2162DFCDE2E9897E95`

## Runtime Data

### Usage (stdout):
```cmhg

Configures the Windows Recovery Environment (Windows RE) and system reset.

REAGENTC.EXE <command> <arguments>

The following commands can be specified:

  /info             - Displays Windows RE and system reset configuration
                      information.
  /setreimage       - Sets the location of the custom Windows RE image.
  /enable           - Enables Windows RE.
  /disable          - Disables Windows RE.
  /boottore         - Configures the system to start Windows RE next time the
                      system starts up.
  /setbootshelllink - Adds an entry to the Reset and Restore page in the boot
                      menu.

For more information about these commands and their arguments, type
REAGENTC.EXE <command> /?.

  Examples:
    REAGENTC.EXE /setreimage /?
    REAGENTC.EXE /disable /?

REAGENTC.EXE: Operation Successful.
    

```

### Usage (stderr):
```cmhg

Configures the Windows Recovery Environment (Windows RE) and system reset.

REAGENTC.EXE <command> <arguments>

The following commands can be specified:

  /info             - Displays Windows RE and system reset configuration
                      information.
  /setreimage       - Sets the location of the custom Windows RE image.
  /enable           - Enables Windows RE.
  /disable          - Disables Windows RE.
  /boottore         - Configures the system to start Windows RE next time the
                      system starts up.
  /setbootshelllink - Adds an entry to the Reset and Restore page in the boot
                      menu.

For more information about these commands and their arguments, type
REAGENTC.EXE <command> /?.

  Examples:
    REAGENTC.EXE /setreimage /?
    REAGENTC.EXE /disable /?


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\ReAgentc.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/7f5ba727c557a2ae96b82e00644c098212629a60739bc498d4bd7d374bdbec75/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ReAgentc.exe](ReAgentc.exe-A109CC3B919C7D40E4114966340F39E5.md) | 27
[C:\Windows\system32\ReAgentc.exe](ReAgentc.exe-C6C0C06194B1F70B921E5A6414921D15.md) | 27




MIT License. Copyright (c) 2020-2021 Strontic.


