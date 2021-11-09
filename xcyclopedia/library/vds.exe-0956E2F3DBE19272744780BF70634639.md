---
title: vds.exe | Virtual Disk Service
excerpt: What is vds.exe?
---

# vds.exe 

* File Path: `C:\WINDOWS\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `0956E2F3DBE19272744780BF70634639`
SHA1 | `BE1EFC4C15DC7D53FEB978D59CC4F7827E11661D`
SHA256 | `25587D0E13F0B3DBBF7B72A239A9B104F4EEE0E90BE42C6973750CDD58AA7CFF`
SHA384 | `A58326471FAD6202C96C04A03387FABB42370A689A85E8117672F0BB583FFF8B75378A647B93B73D58A2FD6511DB5BB8`
SHA512 | `A0136D6AC3AEE787B1484AAB239AEC2C2137B807CE379BF19A6D5FEDCEB332A77DFA7BE9605FB32034E1EFAB62CEF15C94685C57CE126C08DB7C94A16CFCFFF5`
SSDEEP | `12288:nBcfG6fP+TyQGzu9gIVAazmZr7bz+K7Ko:nC+TyQIu93VAumZr7jm`
IMP | `6741B70098A1057A0E7AA9AA14DD175B`
PESHA1 | `EA6B3024F7AF2D3FBF275D637797EB090ECF67A0`
PE256 | `6A070BA9E90A1F272A7BFA9E573F8C84CCFE2FB77CE50F70D695CB383B183FF2`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\system32\vds.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/25587d0e13f0b3dbbf7b72a239a9b104f4eee0e90be42c6973750cdd58aa7cff/detection


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vds.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


