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
MD5 | `1C8ED08C898D73964B98AAA5F06A0F63`
SHA1 | `F9936495B64571A153AC76806E12891F025F0523`
SHA256 | `94D0026CF4D5AE83628DBDA51B9FBC720C91B5EA7E180428877B8C95F5998AF6`
SHA384 | `B82B5CFE1489837C1BB1EFDE39E990A399FB343EACE7BE6BB90485BC34AD4E39AF12509688DCB1F4EEF5856F3D3468DD`
SHA512 | `D35AF0F099634AF7418CEA53D2CDDD84B2EFB3C9FAF3415ABA42D25F6913CC049B0BE995196A0D110C946B40957E5E39569526D6C61C939B0F662C3EE5994EB8`
SSDEEP | `384:evPVU/lmhosFrCG/0F0V4io1ebXbvas1sL2H1WYwVa6c01CkByPNtHjsPWb/2CSd:evPVU/lmLeqVoUfvLwl98XIWQ8YI+`
IMP | `D49693811FAE10A24C0FF7B2BE2B6CB4`
PESHA1 | `F46E1D2C006A7714256497421B1BD3DBB7A7EF6D`
PE256 | `A51E012AF3EB0E4F48299887721740E90AFD7D85E4CCF42C07A15E3C6182A702`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ReAgentc.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/94d0026cf4d5ae83628dbda51b9fbc720c91b5ea7e180428877b8c95f5998af6/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\ReAgentc.exe](ReAgentc.exe-72EF0D4773609C34A78D082E41EEF6CE.md) | 32
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-A67F36BE763E063A94A7E9CC3EB00CF0.md) | 38
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-C73CD2CAD0C74A17E53B0B72DAA1509E.md) | 65




MIT License. Copyright (c) 2020-2021 Strontic.


