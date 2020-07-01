---
title: fodhelper.exe | Features On Demand Helper
---

# fodhelper.exe 

* File Path: `C:\windows\system32\fodhelper.exe`
* Description: Features On Demand Helper
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F23BCF023D5039CCAB3AA40F6A07B817`
SHA1 | `4D0DE1C3121F202604A01C6DC6F6A36F4A0A4619`
SHA256 | `B1223B86D03C3583B84E46A9A6AD009D770FC4114640402EDE19793167593A8F`
SHA384 | `9558658080010B4C92BE066A6090AE7E6063D6899476FFB4B4183FA3067BA55341D666B67871F6FF1D2DF062BEDCB0FD`
SHA512 | `93249CCBF00B0CC62C9EB05535563C443A37830CE5EAB6EC068CA50EF544E9643F8C5E3E6EC484F6A1767F3D21894CD99D9329EC4BBF02FEE7BB895CC75BA394`
SSDEEP | `768:YqpZqknV+b+pvxg9JWSALQJnjpt6V3Glw1mHXrzg31TdavZZ7RRr:pqQApW3WOV3Gy1mHX61TSZZTr`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FodHelper.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `fodhelper.exe` being misused. While `fodhelper.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_process_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_process_creations.yml) | `            - '*\fodhelper.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `title: Bypass UAC via Fodhelper.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `description: Identifies use of Fodhelper.exe to bypass User Account Control. Adversaries use this technique to execute privileged processes.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `        ParentImage\|endswith: '\fodhelper.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `    - Legitimate use of fodhelper.exe utility by legitimate user` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #3: Bypass UAC using Fodhelper [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #4: Bypass UAC using Fodhelper - PowerShell [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #3: Bypass UAC using Fodhelper [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #4: Bypass UAC using Fodhelper - PowerShell [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #3 - Bypass UAC using Fodhelper](#atomic-test-3---bypass-uac-using-fodhelper) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #4 - Bypass UAC using Fodhelper - PowerShell](#atomic-test-4---bypass-uac-using-fodhelper---powershell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #3 - Bypass UAC using Fodhelper | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Bypasses User Account Control using the Windows 10 Features on Demand Helper (fodhelper.exe). Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | fodhelper.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #4 - Bypass UAC using Fodhelper - PowerShell | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | PowerShell code to bypass User Account Control using the Windows 10 Features on Demand Helper (fodhelper.exe). Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process "C:\Windows\System32\fodhelper.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


