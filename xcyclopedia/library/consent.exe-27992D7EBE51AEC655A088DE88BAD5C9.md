---
title: consent.exe | Consent UI for administrative applications
---

# consent.exe 

* File Path: `C:\Windows\system32\consent.exe`
* Description: Consent UI for administrative applications
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `27992D7EBE51AEC655A088DE88BAD5C9`
SHA1 | `9329B2362078DE27242DD4534F588AF3264BF0BF`
SHA256 | `8F112431143A22BAAAFB448EEFD63BF90E7691C890AC69A296574FD07BA03EC6`
SHA384 | `E42F693B1A7A4EE8E31FA033FEB4B05367A25C3AEC9835366985357D002BCC46C09C1EE7FA4C987CB51DFE06B5E97BF8`
SHA512 | `7D129C79A594D57DFB3C0726C8B51C263A551D991F47703BB06811E4AE68A7DD09F17476A540C16E51C0D9CA46527F399581A1A5F3A41C6FA73431F3A2E70ABC`
SSDEEP | `1536:nzWTXOK1vnpop7BIFFlUDKcCjXifIOAmQt/f4k7eDkXV+JEIuaikX4sVQbf/7X2r:ydKtTqyfumQF7NoJeSX4sC7mzkMv`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: consent.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `consent.exe` being misused. While `consent.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `description: Detects an explotation attempt in which the UAC consent dialogue is used to invoke an Internet Explorer process running as LOCAL_SYSTEM` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `        ParentImage: '*\consent.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | <blockquote>Adversaries may spoof the parent process identifier (PPID) of a new process to evade process-monitoring defenses or to elevate privileges. New processes are typically spawned directly from their parent, or calling, process unless explicitly specified. One way of explicitly assigning the PPID of a new process is via the <code>CreateProcess</code> API call, which supports a parameter that defines the PPID to use.(Citation: DidierStevens SelectMyParent Nov 2009) This functionality is used by Windows features such as User Account Control (UAC) to correctly set the PPID after a requested elevated process is spawned by SYSTEM (typically via <code>svchost.exe</code> or <code>consent.exe</code>) rather than the current user context.(Citation: Microsoft UAC Nov 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


