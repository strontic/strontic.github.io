---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\WINDOWS\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `DB4A2CE2B545AC7B89BF3C650C771172`
SHA1 | `722337CB7FA984BAE62272E96D5E3B43155F6613`
SHA256 | `44A2B3AF560873F8EC05935FC95F20A1DA08189C4A2F2CEFEEA0B87BF9E3B3BC`
SHA384 | `1C5F0E9A82F51EC65ED1DF8E09070926E200D0E94C5AC572B190D33AA7FA313E7581A599330015C8DDAF26F84C207E08`
SHA512 | `BF36831FE2B070D5635808B6A3A615D05724562D91C2F4578D64A0078FFB9C4FA0040053ABE6826E0AC25968BBCB59D325F1F0D0F5EF26B8F13CECB62945E350`
SSDEEP | `24576:4L41IYt5pgS97Ywob0Jv+jqJOF+2NqzxBrbPVR6vS+dLHNd4F6HMhiP62N9wP0Fl:4L41IYt5qS97Ywob0Jv+jqkE2NqzxBr4`
IMP | `99AD525953D937F005A947E10332773F`
PESHA1 | `5ADAC5ACDBE1274B16FF6995388D13BE8E88DF97`
PE256 | `E536CD6906DFEE3D7FA837A56B5A95441FEE6D968CBDC423B28773EFE025A386`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\audiodg.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/44a2b3af560873f8ec05935fc95f20a1da08189c4a2f2cefeea0b87bf9e3b3bc/detection


## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


