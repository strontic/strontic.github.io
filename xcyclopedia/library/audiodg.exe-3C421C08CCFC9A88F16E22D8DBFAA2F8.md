---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `3C421C08CCFC9A88F16E22D8DBFAA2F8`
SHA1 | `B711A3888001B4877CD8A3153B345B51C9C2C5A3`
SHA256 | `A6DA29989CC114B31CDE0F429D7DA73B5F2F2A422614610E94555520A06B2B1B`
SHA384 | `2C64342015F1E53FC62CB91B7A0598EDF8BAEDDC024447434EE430C203FFA9EED3E239F56355B17F55CEB3575E24240E`
SHA512 | `24A2ECA3F2CEA763CAAAC7E2E9D21D96F62B34C82816C2CB10EF99068E35995B9E69F7C8F11F78B03F8FF65F76A890AEC7FC2E31248338807F6749AE9262C3F7`
SSDEEP | `3072:ZuX80XHi6rBUxVxI7byV6pzjrSrwcLqsIgS3f/lIlrhIEitFJErirl+sbqcxs:ZuNq8zHSXG3GaFJl+UBxs`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


