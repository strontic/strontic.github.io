
# ComputerDefaults.exe 

* File Path: `C:\WINDOWS\SysWOW64\ComputerDefaults.exe`
* Description: Set Program Access and Computer Defaults Control Panel
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `455CCBB47F4BEF02A9E0034859CE59E2`
SHA1 | `D68118C7635FAD7BDD83E1AEAEF08E277C0EF5F4`
SHA256 | `58BA527A7734600F3FF475A38A0CB233A883EFF4F09DFFE2B23686C9C8253F35`
SHA384 | `66F4C931577B17BCC67F69AF59E3ACBB6D69AA50D716BA57A4085EA7F924250758E34484F8E7040D0EC855AAB6B0EE45`
SHA512 | `58AA95D1CF3B058D61B094ECDE23D4BC9F9F2498A02EC9B1D30ED5DA74ABACE6CD810544F7E111FE1F050CFE8A0C14F74DA6ADF3B7564D660695F6B61FDD0705`
SSDEEP | `1536:05zu0Yg9vp+15SJrePojhZ7oyrURDoq4OZZZLlCIibe6:URBT+1gwRD68wbe`

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

* Original Filename: ComputerDefaults.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.267 (WinBuild.160101.0800)
* Product Version: 10.0.18362.267
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 54
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 54
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 44
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 49
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 52
[C:\WINDOWS\SysWOW64\PickerHost.exe](PickerHost.exe-FC004590CCAFF6A2DDFF20FEB2C663B2.md) | 25
[C:\WINDOWS\SysWOW64\UserAccountControlSettings.exe](UserAccountControlSettings.exe-C88891AC9FBC632FAC0ECB4D484D5798.md) | 30
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 50
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 46

## Possible Misuse

*The following table contains possible examples of `ComputerDefaults.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #5: Bypass UAC using ComputerDefaults (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #5: Bypass UAC using ComputerDefaults (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #5 - Bypass UAC using ComputerDefaults (PowerShell)](#atomic-test-5---bypass-uac-using-computerdefaults-powershell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #5 - Bypass UAC using ComputerDefaults (PowerShell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | PowerShell code to bypass User Account Control using ComputerDefaults.exe on Windows 10 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process "C:\Windows\System32\ComputerDefaults.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


