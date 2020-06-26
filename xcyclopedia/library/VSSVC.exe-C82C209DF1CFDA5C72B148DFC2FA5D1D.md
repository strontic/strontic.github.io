---
title: VSSVC.exe | Microsoft Volume Shadow Copy Service
---

# VSSVC.exe 

* File Path: `C:\WINDOWS\system32\VSSVC.exe`
* Description: Microsoft Volume Shadow Copy Service
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C82C209DF1CFDA5C72B148DFC2FA5D1D`
SHA1 | `A104E195ADD6697FDFC2A73BFB79104BA99AE9C3`
SHA256 | `C4A4BB9B050D214D44119D6F39822E9E3B36EF7DA67471843C0856E090987B70`
SHA384 | `6AB22B9E5F30022D080EFF5344A9B68DF4164E661D3A9F3442DF21609292D38F38886BE5D35E4C3E531D90392EB3CE93`
SHA512 | `F70C5A5320C8AA59C6437BB2A0D7E48D5D24D29C82ED990A635E4C5B0D2F30FD2DBA560F5F72DAF0153741D586579FCDBDF0B3C0C0B2629FCDF394E6FEE66CBC`
SSDEEP | `24576:qFwNSS7SIfKLQHJ2ochrLlqMoy6nV925+P7:PXS5QH8om/lqMoy6nV99P`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


