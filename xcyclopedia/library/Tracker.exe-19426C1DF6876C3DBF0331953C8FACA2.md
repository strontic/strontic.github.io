---
title: Tracker.exe | Tracker
excerpt: What is Tracker.exe?
---

# Tracker.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\Tracker.exe`
* Description: Tracker

## Hashes

Type | Hash
-- | --
MD5 | `19426C1DF6876C3DBF0331953C8FACA2`
SHA1 | `721DA7021D3F837CD9154F34614C324DB75935EC`
SHA256 | `63BB4ECF8C913B79473CC9AFB38FD77B63FBFDE3750EC1E937315631FB6E0D80`
SHA384 | `4884D828B4DC33A557422B59BC45D6674827CEDE95FD27BBAB679DD0DEC52A27F95DCE82180E634A023503A16A114873`
SHA512 | `52F724DCCE76BCDCE37030F71130CA5B65A57BF719A896047532344300E21187917762E2877ED85D9B8EF187B4464F185DE972098274DD82571BC8F69CB287BB`
SSDEEP | `3072:YQpnY7lL/+uDb38Bns1C4vAzE402o3ng5bHqrTu+dor/9ZWBiZK:YQpeL/+2T8BgZvAdLo3nD8/9kBis`
IMP | `05F2874F08228C142185ADBDAA336B88`
PESHA1 | `16458E16F10A14BE068FF5B7B465C4C7D44F55A4`
PE256 | `83C77820D44E6A5F2898AD579C5D0A73489E2462B40A2BCC286C9ACB9622C76B`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\Tracker.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/63bb4ecf8c913b79473cc9afb38fd77b63fbfde3750ec1e937315631fb6e0d80/detection


## Possible Misuse

*The following table contains possible examples of `Tracker.exe` being misused. While `Tracker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_emotet_rudll32_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_emotet_rudll32_execution.yml) | `- '\tracker.exe' #When Visual Studio compile NodeJS program, it might use MSBuild to create tracker.exe and then, the tracker.exe fork rundll32.exe `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `Name: Tracker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `Description: Use tracker.exe to proxy execution of an arbitrary DLL into another process. Since tracker.exe is also signed it can be used to bypass application whitelisting solutions.`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [rqz-dnsduvel_blocklist.json](https://github.com/eset/malware-ioc/blob/master/dnsbirthday/rqz-dnsduvel_blocklist.json) | `"tracker.marinsm.com",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `www2.dyn.tracker[.]com`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `ssl2.dyn-tracker[.]com`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_rtf_ole2link.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_rtf_ole2link.yar) | author = "@h3x2b <tracker _AT h3x.eu>" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


