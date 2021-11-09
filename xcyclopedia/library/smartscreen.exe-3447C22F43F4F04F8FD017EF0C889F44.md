---
title: smartscreen.exe | Windows Defender SmartScreen
excerpt: What is smartscreen.exe?
---

# smartscreen.exe 

* File Path: `C:\WINDOWS\system32\smartscreen.exe`
* Description: Windows Defender SmartScreen

## Hashes

Type | Hash
-- | --
MD5 | `3447C22F43F4F04F8FD017EF0C889F44`
SHA1 | `87B39A1F03C44BB2BF260D472975E2ECABD43F04`
SHA256 | `BE288C1C68FD64A0FACD30159AEB8F1D36892550725231AFEC2B4C2C354D861E`
SHA384 | `DA1D93C0F516B2F541C79DA5A8F2C6A43A16F261A70EEA70D7C1A54569ACB2FEE99F2BF34F28F9CA4A9E6415B1D96A4E`
SHA512 | `AA8D34828F4AC2BC155B4B10264F097763A7EB0C5332507F7BFFB609F584E5BA55405F89FC787FAA8D7E8B4B6DA6214341907BE7A66424352EE35EB876BB25E0`
SSDEEP | `49152:2QKGbYmMhh+RIF5mQeJGSZPhFS4o0heHtAtR3yraq5aPND+8r37UnI:DfpR3fN5r37`
IMP | `94AEA925992728159360435E36CB27FF`
PESHA1 | `0910A4B273921AA3745B509F78DA8A8994E7D9FE`
PE256 | `464557EBEC4AD0F010C69F429EDAA7703922586B43C8C134DC1F4E6CE428656B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\system32\smartscreen.exe |
C:\WINDOWS\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smartscreen.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/be288c1c68fd64a0facd30159aeb8f1d36892550725231afec2b4c2c354d861e/detection


## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\smartscreen.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1553.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1553.005/T1553.005.md) | <blockquote>Adversaries may abuse specific file formats to subvert Mark-of-the-Web (MOTW) controls. In Windows, when files are downloaded from the Internet, they are tagged with a hidden NTFS Alternate Data Stream (ADS) named <code>Zone.Identifier</code> with a specific value known as the MOTW.(Citation: Microsoft Zone.Identifier 2020) Files that are tagged with MOTW are protected and cannot perform certain actions. For example, starting in MS Office 10, if a MS Office file has the MOTW, it will open in Protected View. Executables tagged with the MOTW will be processed by Windows Defender SmartScreen that compares files with an allowlist of well-known executables. If the file in not known/trusted, SmartScreen will prevent the execution and warn the user not to run it.(Citation: Beek Use of VHD Dec 2020)(Citation: Outflank MotW 2020)(Citation: Intezer Russian APT Dec 2020) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


