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
MD5 | `C6C0C06194B1F70B921E5A6414921D15`
SHA1 | `36CF9A889DA67B858C6962E9A054C56E5B4825A0`
SHA256 | `6ED3121E5A6299EE1030F52D800F3F1F2EE1AAB5C73C99E0DD34034A23F7D44C`
SHA384 | `AF8FF5C893426E9DF0D027F2572AA225309EABD1ADD3A310259A96003993F7494FE662E6D207000C882840596330EE69`
SHA512 | `E4AF93849E6F8C8AEDE2793A12C3927D3B2E9C476811A15E6856A544025EDDE6D4C860156A59DB76157591DD59B5CFABF7273305F51E03653E9FDB44815F5D6E`
SSDEEP | `768:pk6DuaaMKodXVsc8EKx05aav1hrE7IrhRp4NfqavPFk/lmKVdMN8s61IY2:a6DuaaMKMMzna9asVv4Nfq9/lmKbw8Qr`
IMP | `8EE3C5B237390A633C5114373C9B4C60`
PESHA1 | `2AAE494762A6F583D387B7B3E9E87D775EB92914`
PE256 | `3A17A4ED624A011BEBB18C0B62B66912ED093E859BB98DE898D10A2C64843390`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6ed3121e5a6299ee1030f52d800f3f1f2ee1aab5c73c99e0dd34034a23f7d44c/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\ReAgentc.exe](ReAgentc.exe-650DC6DD5168563BB681CCA09E7D9CCF.md) | 27
[C:\Windows\system32\ReAgentc.exe](ReAgentc.exe-A109CC3B919C7D40E4114966340F39E5.md) | 40




MIT License. Copyright (c) 2020-2021 Strontic.


