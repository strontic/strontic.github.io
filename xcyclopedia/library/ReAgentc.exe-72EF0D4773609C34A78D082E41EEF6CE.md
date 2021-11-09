---
title: ReAgentc.exe | Microsoft Windows Recovery Agent
excerpt: What is ReAgentc.exe?
---

# ReAgentc.exe 

* File Path: `C:\WINDOWS\SysWOW64\ReAgentc.exe`
* Description: Microsoft Windows Recovery Agent

## Hashes

Type | Hash
-- | --
MD5 | `72EF0D4773609C34A78D082E41EEF6CE`
SHA1 | `F9983CEC86F12B3E37F5FEE604ED043D83D5E023`
SHA256 | `5517A4D7A5FD8CA91EC0065C3374616443A16DC2DB818089075A6EE3FED335C2`
SHA384 | `E0994547E71F1460E6A27507B0D8FD525A00F3965162A9B535F0B2EA297502C543B98759B4E3D4DCA4608106C2ABBC6E`
SHA512 | `E702F93569A572208AB52B2888FC5DE9FB8C2D3C7405A61C90E4390EE88AA38C454678C264ED5D7198B40EC9A8ED77998599ADB205A662D453FC70D32E338ED0`
SSDEEP | `768:qvPVU/lmfvSPyYCi2na7+ZVr5DdMicWAUfM/oYbVmC:N/lmvflnaOVr5Dddc7DVmC`
IMP | `7A70958FF8D97D94739B03DA52D18D2E`
PESHA1 | `E508032025DB5960AF2567E56CDB4D6CCE963382`
PE256 | `BEDEE8A4D66F56E07ECBDF970C3F97A24660C09ABFEB839C65B8F221FECA6CB3`

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\ReAgentc.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/5517a4d7a5fd8ca91ec0065c3374616443a16dc2db818089075a6ee3fed335c2/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-1C8ED08C898D73964B98AAA5F06A0F63.md) | 32
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-A67F36BE763E063A94A7E9CC3EB00CF0.md) | 32
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-C73CD2CAD0C74A17E53B0B72DAA1509E.md) | 35




MIT License. Copyright (c) 2020-2021 Strontic.


