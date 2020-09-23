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
MD5 | `A67F36BE763E063A94A7E9CC3EB00CF0`
SHA1 | `99E933D32A6562CE7A85AD66D6BEDF08179ED0B5`
SHA256 | `FA698E4B50CC76ABFBF99E5D27C81D19C26F2AF529EF4D2568A2F9ABA436E455`
SHA384 | `F6AD606F0830D5EAE3148FD5B0C076A23A133B6892FB11FD28D80571F70FE42AE9E42AB0D09EBF7F6F5FBC651C50A398`
SHA512 | `6A7B24B7B778571C03404C77D2888F4C6C51E1AF795AE7F5DEC57AB5E70198E6E42294EEE478F5AF25BA19129ACCD044ED872FBFC4115F06D0415C7D24F45E0F`
SSDEEP | `768:UCvPVU/lmwRXy/fvI6FrkYwzmL0+bfziuq+z:UV/lmoX2fvIoSmViu`
IMP | `5D57AB2744E9B68BCF69368EF0371E24`
PESHA1 | `1E4B048C59649AA93A1A76A1845B0969C1AE2B42`
PE256 | `3F7B044D457B3B6E47D5F930FF058B185269BD80CF5223EA53BC0DFF10BDDCBF`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/fa698e4b50cc76abfbf99e5d27c81d19c26f2af529ef4d2568a2f9aba436e455/detection/





MIT License. Copyright (c) 2020 Strontic.


