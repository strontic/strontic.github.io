---
title: ReAgentc.exe | Microsoft Windows Recovery Agent
excerpt: What is ReAgentc.exe?
---

# ReAgentc.exe 

* File Path: `C:\Windows\SysWOW64\ReAgentc.exe`
* Description: Microsoft Windows Recovery Agent

## Hashes

Type | Hash
-- | --
MD5 | `67118D8D0AD2EFE5009C0B1414E02B1C`
SHA1 | `9F74EE3AFD81EBFAEE407FF4C57C03A3C3CB4F69`
SHA256 | `EF577D51307E12C4315C0504199B8A01175BF7E742D1CE4C4D41CAE4543D6AC4`
SHA384 | `760E7A1FF5D2A9E910122A35E948F88B2029DE10C51359599491AF47958D3AD053DB2A61410A9843A24513888D537F0B`
SHA512 | `0132C51FF958A50374BA23555FAB3573F0953E0391EB3BA80491FD1F0A474A57FC77E3D7945797A4E64B8F05118763E6090B479160DF3B4C0D8DDC6F215A1AC8`
SSDEEP | `384:/vPE/ltos9cPTPagDC46h+A3CE49mBkwPM+vwoAHw1w4DO04bl5+TuuNC+NpvqW9:/vPE/liCSA3MfHwnq+uEN5xyq`
IMP | `76D2AE3842F571E99D57B74E38981DD2`
PESHA1 | `686FD1507E2F29811D8953E1D6F7520485C5F6FD`
PE256 | `EA7333A16A5264E03FAAB1AF1FE9DE274F6C43881728920243F3D646819DC414`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ReAgentc.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/ef577d51307e12c4315c0504199b8a01175bf7e742d1ce4c4d41cae4543d6ac4/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\ReAgentc.exe](ReAgentc.exe-7CD65A4AF64192FD717FC651412B1C14.md) | 36




MIT License. Copyright (c) 2020 Strontic.


