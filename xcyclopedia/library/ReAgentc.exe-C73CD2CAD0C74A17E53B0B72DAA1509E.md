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
MD5 | `C73CD2CAD0C74A17E53B0B72DAA1509E`
SHA1 | `F39352192D6B901453DEEB50228DBDA9DB73C755`
SHA256 | `82B0A8EA592C68CA1F913E716A82D2BBE32A5A34654A836C35B1E7ADC77C9342`
SHA384 | `AF0DAB5384FE0F85DED93C34DB73119F1E194068D305E253E670F0F40FA5C71E0C561A46065AB0E068E49C6CE55629BC`
SHA512 | `280ECE6860043B5FF41F9391F8BA7BABC2BFE120C6013652B92B374708AB5E09979FE285AB90B580E97223F8C9C205F654D4FA194684B12DDEC49A12578A6ACC`
SSDEEP | `384:VvPVU/lmhoszrCl/0FFtdC1xbXbvOL1sL2H1WHwVt6fEn1/kkgPotHj2YWb/2CwH:VvPVU/lm5RHiHfvxwrSvAZWKQPv+z`
IMP | `D49693811FAE10A24C0FF7B2BE2B6CB4`
PESHA1 | `5815C3C02AD371D99D153157582BB4071FE5A83B`
PE256 | `87A5C337207B1A09311CB61D5766AFE8DB0F845FA608528E6FFDFAA102C89792`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.572 (WinBuild.160101.0800)
* Product Version: 10.0.19041.572
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/82b0a8ea592c68ca1f913e716a82d2bbe32a5a34654a836c35b1e7adc77c9342/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-1C8ED08C898D73964B98AAA5F06A0F63.md) | 65
[C:\Windows\SysWOW64\ReAgentc.exe](ReAgentc.exe-A67F36BE763E063A94A7E9CC3EB00CF0.md) | 41




MIT License. Copyright (c) 2020-2021 Strontic.


