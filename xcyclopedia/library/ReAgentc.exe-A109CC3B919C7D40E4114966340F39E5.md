---
title: ReAgentc.exe | Microsoft Windows Recovery Agent
excerpt: What is ReAgentc.exe?
---

# ReAgentc.exe 

* File Path: `C:\Windows\system32\ReAgentc.exe`
* Description: Microsoft Windows Recovery Agent

## Hashes

Type | Hash
-- | --
MD5 | `A109CC3B919C7D40E4114966340F39E5`
SHA1 | `56063A8458A9C2396D7E0C50877AA633548ADE72`
SHA256 | `125EE07FC9D013AA89A80B742326318E30EAEF40C5EDFF283C5FFDF41F93616B`
SHA384 | `315A0D46F51254E92CA9A61D130C19213689D861E4798B0D011347456D0A96ABEA9E36EBEC879D921CA9FA7D33E44C5A`
SHA512 | `D045AC6C83FCCF2F3E2D7F987443691D8300F3B688E4D148DD1E8BEFD0BA3259892B6DBC9D0E0E4F6813867482FC8585D7756EFA0846C0EAA34107D83E9D83C3`
SSDEEP | `768:dEf6TOIasJMBVsMHKlen6VR5E71x7RJINqk4vPFk/lmyVJMx5WzC1fH:dQ6TOIasJMte8jvINqkr/lmyjg5WEfH`
IMP | `9A64FB4189BC3B4D80589BCA6F1350F7`
PESHA1 | `BAC4D7E3DB56BA7D45AA33B28AF49ADFDD53C89A`
PE256 | `AD476DA7A6125961BE75C8998CCFCC12F19BFA6613D0836FB3006E42CF22B59F`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\ReAgentc.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/125ee07fc9d013aa89a80b742326318e30eaef40c5edff283c5ffdf41f93616b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ReAgentc.exe](ReAgentc.exe-C6C0C06194B1F70B921E5A6414921D15.md) | 40




MIT License. Copyright (c) 2020 Strontic.


