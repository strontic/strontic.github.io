---
title: ntoskrnl.exe | NT Kernel & System
excerpt: What is ntoskrnl.exe?
---

# ntoskrnl.exe 

* File Path: `C:\windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System

## Hashes

Type | Hash
-- | --
MD5 | `F8995F4F142CC71009B2101BB5807B10`
SHA1 | `5E1BBFBABE25F97E95F9B83E4C98A79C217422F0`
SHA256 | `474A3FBA47AA1505036D12C329787D85C175E5CB53A90FFD06C0DB4B1864EE17`
SHA384 | `BBC699235B545B9466283406EA0FDB1E0360C4A7232E01F621431745B88796DE86A6EC7F9143D13FABE98494F8973DFB`
SHA512 | `1AE138398B74191ABA738DC082147E1AC9E2BE38791B6F6E46E68A103418AF059254526CC5E5CF2E84CB87193338BCC04D90BB6043B356E9F1976E34740C687F`
SSDEEP | `98304:USxYBKmf+iRsG552utpOBtCD4ZBF/Ez6/MQYzMz4Y6KXq:wVqGKkQO4ZBF/Ez6/Du+2`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntkrnlmp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.19724 (winblue_ltsb_escrow.200519-1914)
* Product Version: 6.3.9600.19724
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $x4 = "C:\\\\Windows\\\\Sysnative\\\\ntoskrnl.exe" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $s17 = "NTOSKRNL.EXE" fullword wide /* Goodware String - occured 4 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a5 = "ntoskrnl.exe" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a3 = "%SystemRoot%\\System32\\ntoskrnl.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_hdroot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_hdroot.yar) | $s1 = "\\system32\\ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_querty_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_querty_fiveeyes.yar) | $s3 = "ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s4 = "ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


