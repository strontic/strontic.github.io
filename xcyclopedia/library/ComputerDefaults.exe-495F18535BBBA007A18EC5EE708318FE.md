---
title: ComputerDefaults.exe | Set Program Access and Computer Defaults Control Panel
---

# ComputerDefaults.exe 

* File Path: `C:\WINDOWS\system32\ComputerDefaults.exe`
* Description: Set Program Access and Computer Defaults Control Panel
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `495F18535BBBA007A18EC5EE708318FE`
SHA1 | `991100111548B5CC7A09C65797543898DAB34FD3`
SHA256 | `64959878420834FFDF17823F1CC507261F1CEF286FF476777C4F3DA7D17AFA24`
SHA384 | `B7A78F8D1E754C809EDCAD5B21C93A7662ED7F0CDBC8CC58746E6A2D1149C0C28E12001EB2ACB70B134B5350D5BE086F`
SHA512 | `AB16974E135CC74C26A58D01820026DCBB57DD52C2DA143CE96AA4F6BC4CDDDA3926A1B07E9429C430F653503C7A8A679BC0DA4A6FB657057890D9FC4D752B4B`
SSDEEP | `1536:wFLvIy+SgFCoiFAono+AGbMAvy4URDoq4OZZZLlCIibe:wp7+X+oVgMTRRD68wbe`

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

* Original Filename: ComputerDefaults.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 54
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 50
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 49
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 54
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 55
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 52
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 54

## Possible Misuse

*The following table contains possible examples of `ComputerDefaults.exe` being misused. While `ComputerDefaults.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #5: Bypass UAC using ComputerDefaults (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #5: Bypass UAC using ComputerDefaults (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #5 - Bypass UAC using ComputerDefaults (PowerShell)](#atomic-test-5---bypass-uac-using-computerdefaults-powershell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #5 - Bypass UAC using ComputerDefaults (PowerShell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | PowerShell code to bypass User Account Control using ComputerDefaults.exe on Windows 10 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process "C:\Windows\System32\ComputerDefaults.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


