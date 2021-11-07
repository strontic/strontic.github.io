---
title: Tracker.exe | Tracker
excerpt: What is Tracker.exe?
---

# Tracker.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\Tracker.exe`
* Description: Tracker

## Hashes

Type | Hash
-- | --
MD5 | `566303DFC036D3B99B62B158CE5636C5`
SHA1 | `5105E7EB421521C139F15D9E4175B7BAFDC253AE`
SHA256 | `5B97761C5C93FC7205EEED95BDA09CC48BD5511E3ECE91F107DC175B89BE8975`
SHA384 | `45FB9C85BC9597D5CC186F05260F194C2F22BBCE35FF2AA3DAFA9355CD18CB0DB6E4CCA52ADFECAD175ADEACD3DBC245`
SHA512 | `BE99E1D8A38256DF6D803DB6BF9000FFE932FE8A4BEAD1639AC0D4C20ADD66E4A7C0D258D54C4506DAA5B7CDFDE0221DC1F70D1072C182A9EB79013AE904D541`
SSDEEP | `3072:3IKUy2ssbzT385i0wrv2eJwJX/aqIvjusqfaU7t0WxpM1f2i4w:0T/85i0wKMuX1IPqVrU1um`
IMP | `C680C48710AC898A7A6D38020952E20D`
PESHA1 | `94FB4A22C3F0E4C85BBBC8EC5916E1D46EBE1B40`
PE256 | `4AAD9F492C5216285331D723848DF6762B03B7ADA267D56EA2A7DD5042D3A08D`

## Runtime Data

### Usage (stderr):
```cmhg
TRACKER : error TRK0000: Bad argument: --help
Microsoft (R) Build (MSBuild) File Tracker Version 4.0.30319
Copyright (C) Microsoft Corporation. All rights reserved.
Syntax:
    Tracker.exe [options] [@tracker-response-file] /c [command-line]

Switches:

 /d file.dll             : Start the process with the tracking dll file.dll.
                           (default: FileTracker.dll from the PATH)

 /i[f] <path>            : Intermediate directory for tracking log output.
                           (using /if will expand the path to full immediately)
                           (default: current directory in tracked process)

 /o                      : Track operations performed on each file

 /m                      : Include missing files in tracking logs
                           i.e. those that are deleted before process closes

 /u                      : Do not remove duplicate file operations from the
                           tracking log.

 /t                      : Track command lines (will expand response files
                           specified with the '@filename' syntax)

 /a                      : Enable extended tracking: GetFileAttributes,
                           GetFileAttributesEx

 /e                      : Enable extended tracking: GetFileAttributes,
                           GetFileAttributesEx, RemoveDirectory, CreateDirectory

 /k                      : Keep the full tool chain in tlog filenames.

 /r file1;file2;..;filen : Root primary input file(s) being tracked
                           (default: none)

 /c [command-line]       : Command to be tracked (must be the last argument).

 /?                      : This help text.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\Tracker.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Tracker.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 14.8.4084.0 built by: NET48REL1
* Product Version: 14.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/5b97761c5c93fc7205eeed95bda09cc48bd5511e3ece91f107dc175b89be8975/detection


## Possible Misuse

*The following table contains possible examples of `Tracker.exe` being misused. While `Tracker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_emotet_rudll32_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_emotet_rudll32_execution.yml) | `- '\tracker.exe' #When Visual Studio compile NodeJS program, it might use MSBuild to create tracker.exe and then, the tracker.exe fork rundll32.exe `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tracker_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tracker_execution.yml) | `title: DLL Injection with Tracker.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tracker_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tracker_execution.yml) | `description: This rule detects DLL injection and execution via LOLBAS - Tracker.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tracker_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tracker_execution.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tracker_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tracker_execution.yml) | `- '\tracker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tracker_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tracker_execution.yml) | `- 'Tracker'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `Name: Tracker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `Description: Use tracker.exe to proxy execution of an arbitrary DLL into another process. Since tracker.exe is also signed it can be used to bypass application whitelisting solutions.`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [rqz-dnsduvel_blocklist.json](https://github.com/eset/malware-ioc/blob/master/dnsbirthday/rqz-dnsduvel_blocklist.json) | `"tracker.marinsm.com",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `www2.dyn.tracker[.]com`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `ssl2.dyn-tracker[.]com`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_rtf_ole2link.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_rtf_ole2link.yar) | author = "@h3x2b <tracker _AT h3x.eu>" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


