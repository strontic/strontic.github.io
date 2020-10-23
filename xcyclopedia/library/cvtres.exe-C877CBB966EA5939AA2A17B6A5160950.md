---
title: cvtres.exe | Microsoft Resource File To COFF Object Conversion Utility
excerpt: What is cvtres.exe?
---

# cvtres.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\cvtres.exe`
* Description: Microsoft Resource File To COFF Object Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `C877CBB966EA5939AA2A17B6A5160950`
SHA1 | `2A3249732F5AA4588A4A9895FFE217355041D663`
SHA256 | `1FE531EAC592B480AA4BD16052B909C3431434F17E7AE163D248355558CE43A6`
SHA384 | `9EAEBBED65AA851C355135492531E58F4547B1AB3E118BA41ED32EE80A52BDE7E832053CEB7B713CA3FFC33F392B485F`
SHA512 | `8D331C7D24BC5B790AFE565634843CDA0498C55A0BCB943EF5D22305871937887623849BBF75CC983E1CB6936766749B0EA627B069FD8B3F791B930CC2FC97D6`
SSDEEP | `768:akdac2JSz9RvzZFcmOUgMiMkRUop6nyMFsSLzmPQySlphYjkmE+iZMB4tF:ucXZFcmbcUyM2SnmdSlsjkmE+zBSF`
IMP | `55D76ADE7FFEA0F41FF2B55505C2B362`
PESHA1 | `DBBF02824C68E986F7901576CD060AAE93D717C0`
PE256 | `9DED0B484DAB4C855638FF211AA738AB5ACFE45E12331060A363F0FC33FA365C`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Windows Resource To Object Converter Version 14.10.25028.0
Copyright (C) Microsoft Corporation.  All rights reserved.

usage: CVTRES [options] [files]

   options:

      /DEFINE:symbol
      /FOLDDUPS
      /MACHINE:{ARM|EBC|IA64|X64|X86}
      /NOLOGO
      /OUT:filename
      /READONLY
      /VERBOSE

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\cvtres.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CVTRES.EXE
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.10.25028.0 built by: VCTOOLSD15RTM
* Product Version: 14.10.25028.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/1fe531eac592b480aa4bd16052b909c3431434f17e7ae163d248355558ce43a6/detection/


## Possible Misuse

*The following table contains possible examples of `cvtres.exe` being misused. While `cvtres.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\cvtres.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


