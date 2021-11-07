---
title: createdump.exe | Microsoft .NET Runtime Crash Dump Generator
excerpt: What is createdump.exe?
---

# createdump.exe 

* File Path: `C:\Program Files (x86)\dotnet\shared\Microsoft.NETCore.App\5.0.11\createdump.exe`
* Description: Microsoft .NET Runtime Crash Dump Generator
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `0464C3912C3B38C27F5DD2D64E09B0BF`
SHA1 | `102F341E2AE956896E4D8149CAE1D1176213E77D`
SHA256 | `A29E03863F41CD76A9BBD7AA878E2FEFC8BE9C4D6E5C07D70B41E002FF66051E`
SHA384 | `67FEB3ADD007D950089D5ECDE35FF471D5D0154B18CAA62A2E786D14247DBAB727293F795ECD7CA072DCD9BF0102E96F`
SHA512 | `3F81F4E85BABD8A9C93E50E4BD9FD93CC8F57A27534A196960EB0C3CF043633789D07E32FD72CCCF992A944A5836329F53C96C61DE1F3ADC28FBFBD324078586`
SSDEEP | `768:FECAQYqex5UzM282fifHT0GXAWY9uSrbi78abXWPIDvv3:zkmYd2fwBXAd3bSbXW6vv3`
IMP | `B858C6FA922134CFA3B9744C3E711ED7`
PESHA1 | `DFA4BF165812A4BB1D230A739C119BCE05F8F037`
PE256 | `23BAF0A9F73E1C2EC6B3490A6DE535F616683287C57B4A37D79D8A425AC6680C`

## Runtime Data

### Usage (stderr):
```cmhg
createdump [options] pid
-f, --name - dump path and file name. The default is '%TEMP%\dump.%p.dmp'. These specifiers are substituted with following values:
   %p  PID of dumped process.
   %e  The process executable filename.
   %h  Hostname return by gethostname().
   %t  Time of dump, expressed as seconds since the Epoch, 1970-01-01 00:00:00 +0000 (UTC).
-n, --normal - create minidump.
-h, --withheap - create minidump with heap (default).
-t, --triage - create triage minidump.
-u, --full - create full core dump.
-d, --diag - enable diagnostic messages.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\dotnet\shared\Microsoft.NETCore.App\5.0.11\createdump.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001DF6BF02E92A74AB4D00000000001DF`
* Thumbprint: `ABDCA79AF9DD48A0EA702AD45260B3C03093FB4B`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FX_VER_INTERNALNAME_STR
* Product Name: Microsoft .NET
* Company Name: Microsoft Corporation
* File Version: 5,0,1121,47308 @Commit: f431858f8b1f1510723ace6343786c9194dbd7fc
* Product Version: 5,0,1121,47308 @Commit: f431858f8b1f1510723ace6343786c9194dbd7fc
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a29e03863f41cd76a9bbd7aa878e2fefc8be9c4d6e5c07d70b41e002ff66051e/detection


## Possible Misuse

*The following table contains possible examples of `createdump.exe` being misused. While `createdump.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #11: Dump LSASS with .Net 5 createdump.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #11: Dump LSASS with .Net 5 createdump.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | - [Atomic Test #11 - Dump LSASS with .Net 5 createdump.exe](#atomic-test-11---dump-lsass-with-net-5-createdumpexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | ## Atomic Test #11 - Dump LSASS with .Net 5 createdump.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | \| createdump_exe \| Path of createdump.exe executable \| Path \| C:&#92;Program Files&#92;dotnet&#92;shared&#92;Microsoft.NETCore.App&#92;5.*.*&#92;createdump.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | echo "Createdump Path #{createdump_exe}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | ##### Description: Computer must have createdump.exe from .Net 5 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | echo ".NET 5 must be installed manually." "For the very brave a copy of the executable can be found here: https://github.com/Scoubi/RedTeam-Tools/blob/main/createdump.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


