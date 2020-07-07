---
title: mspaint.exe | Paint
---

# mspaint.exe 

* File Path: `C:\WINDOWS\system32\mspaint.exe`
* Description: Paint
* Comments: 

## Screenshot

![mspaint.exe](screenshots/mspaint.exe-8A6A020DABFB0024BE80D988C59F8F2A-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `33A61F754D9433D6CC37388CE2711040`
SHA1 | `3489FDD20A7549246737EE842E545B89D8D2B13B`
SHA256 | `F1E3D8851C7B41E3838EAE69A95224C92ABD9A33117238EF9730233B5B14CDC2`
SHA384 | `BAA1FACA302AA68D33A9426698F4509E5A94BC4AFC6018A48908DB8324963E4B4C48EA30975278A00A6BC06ACBE1E04A`
SHA512 | `8FE75D720A438AB215F22B5EE873E4476DDD7D9758D2E03D0A3A9D64197F0215B40ADF399993762A737A9F3359F9C37B667EF1DE0E8A58BD6FD85C97D979D808`
SSDEEP | `24576:biXTjcorgEoNwxqhWuzjNXx5zmbGyF8m:eTzoaIhVFmbG1`

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

* Original Filename: MSPAINT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `mspaint.exe` being misused. While `mspaint.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\mspaint.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe (a 2009 file)`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


