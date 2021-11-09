---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\Windows\SysWOW64\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `ED73F0253A4C10F6B7C221FF6E8BD8B4`
SHA1 | `406D6704061A52559F056D94BD2F452F93A32897`
SHA256 | `BA242DBD6C86655291BBDC01AFEFB0A9C880265B837442AB4C210666EF07B925`
SHA384 | `6B5E058F03A8DCCD036950FF09A44FAAC521C3A74A4C0BC1EF86A4B35D578C283AFF31FA48922C6AECB8CFA7E9E5C6E0`
SHA512 | `2306B5DF02E851D1BFE756F9F2E7A09C49F1E6EF98798A2AD1E36909802B998283448F92D9B24E2792AA07B7402AB20D0A69A76F4EFDB2D8EB24310B2A805BDC`
SSDEEP | `96:lxyZeX932JnXvk7Cc1uDWPTQ+fpH7NHWW2MrTtDJdMi2bKveLrxuJRdFEWFOWwj6:lieXZ2JOT5lWW2MrTFPuxu/sWFOWq`

## Runtime Data

### Child Processes:
wordpad.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\write.exe](write.exe-E87C6A38E61A712C48025A6AD54C1113.md) | 36
[C:\windows\SysWOW64\write.exe](write.exe-1EFA647F97009893CC54BD677751A958.md) | 54
[C:\Windows\SysWOW64\write.exe](write.exe-3D6FDBA2878656FA9ECB81F6ECE45703.md) | 49
[C:\WINDOWS\SysWOW64\write.exe](write.exe-6F738A98257D152943A9E5DFAE1FBC44.md) | 47
[C:\WINDOWS\SysWOW64\write.exe](write.exe-7FBA1268E8C8AEC66A7BF9420F54A745.md) | 47

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \write.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


