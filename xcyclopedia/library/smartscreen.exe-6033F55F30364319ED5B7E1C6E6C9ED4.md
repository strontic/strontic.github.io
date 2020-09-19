---
title: smartscreen.exe | Windows Defender SmartScreen
---

# smartscreen.exe 

* File Path: `C:\WINDOWS\system32\smartscreen.exe`
* Description: Windows Defender SmartScreen

## Hashes

Type | Hash
-- | --
MD5 | `6033F55F30364319ED5B7E1C6E6C9ED4`
SHA1 | `4667A929AC9F824C7D240BE81A0AB9233237D71E`
SHA256 | `533A950B1B8A63226573E93604C11C241AB1AE34E1BE47D9919882A1681ACB42`
SHA384 | `0C7D7DD943C9DCF4661434CFE7C8661CE4B3E1758F53594598C3D313917684CB7FC0486A880AE7C0A0BB1900B15CEF43`
SHA512 | `3098162C62A5083323B5C35DC63A25F54D8ABD5F168C5835B811742D26B91E9AD7869DB4AE4F7579058D3A5871D2370F62B83EE555662682137082577A74A7BE`
SSDEEP | `49152:FkFfgfHzq9YKudUyiIWllo5hwHKAAdFpl9SdICBZgX5k8r37UnxNDg:ebsr37eN`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smartscreen.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\smartscreen.exe](smartscreen.exe-B75FA41284409A6134BF824BEAE59B4E.md) | 30

## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


