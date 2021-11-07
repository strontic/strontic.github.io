---
title: createdump.exe | Microsoft .NET Runtime Crash Dump Generator
excerpt: What is createdump.exe?
---

# createdump.exe 

* File Path: `C:\Program Files\dotnet\shared\Microsoft.NETCore.App\5.0.11\createdump.exe`
* Description: Microsoft .NET Runtime Crash Dump Generator
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `2A8E34DC519359517C5867E22BB7807F`
SHA1 | `35E090EEC2F43BB4FA368603F921DACA3F45A1D9`
SHA256 | `C9E266C931C28D27EF0FA654C069F1B56339A818492245D15046D883B309B8B6`
SHA384 | `2BD16292C4AF7B41A24877BC530252B13CC3B97EBAC440616CD6A5B244A82BDF35B60A2A35437AC9DB64A29064BC76E9`
SHA512 | `1BAF6EF81BCBFBF07128856A34945C63F54D2AC00E9E59EA173C52857FFCD733690D7E9A21C5CABE7CC407A743B87B2B83404882F45BF5180F06A9B399C8B8E2`
SSDEEP | `768:YM+BqKtU0zYUzf2JdmwFAsCeHvJ5YevqQc3DZ2BfaIhYDvqpWYr:Yd84C8Hix7s2paiyvqAo`
IMP | `A59809C5C0D26EF15E2540AC3993C6E2`
PESHA1 | `51E42402BC39D165156081CF806AE7736C3BEA54`
PE256 | `C25C9A289C034B8CC7705026A4AA3BF621FDD608467AC8DE51C3BAF04882E953`

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
C:\Program Files\dotnet\shared\Microsoft.NETCore.App\5.0.11\createdump.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c9e266c931c28d27ef0fa654c069f1b56339a818492245d15046d883b309b8b6/detection


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


