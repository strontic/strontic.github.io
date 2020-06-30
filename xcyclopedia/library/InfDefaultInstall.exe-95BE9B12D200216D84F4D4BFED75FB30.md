---
title: InfDefaultInstall.exe | INF Default Install
---

# InfDefaultInstall.exe 

* File Path: `C:\Windows\SysWOW64\InfDefaultInstall.exe`
* Description: INF Default Install
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `95BE9B12D200216D84F4D4BFED75FB30`
SHA1 | `131C829F7E4C8F8040AF3A3EC0C31CEC04E5443B`
SHA256 | `0A07E8ABEDEA7406F4F1BD0A2A10CC46FD9461D464118D23E2845EB68AF26E1A`
SHA384 | `A4040315057F0B013D243A5AFB9A86664F2114B87793146A7209D425EBF9C1AB4FFF96D7F936103D717BD3A20A4C50FA`
SHA512 | `C0631A03FB5D4FCE8235342C2F1983A5A94EFDDFCCE62CF24BFC132342ADD2D944FE37820A81970277462C16642399BD2C289158BC9B50D322F914FD45D7CD1A`
SSDEEP | `192:v7sbtMNudIEpxpVW+3Dg/otbtmisZKW/GW:vQt/lpTVW+sAtRVoKW/GW`

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

* Original Filename: InfDefaultInstall.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.2.3668.0
* Product Version: 5.2.3668.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\InfDefaultInstall.exe](InfDefaultInstall.exe-3E9C81A60DEDC5FFFF1D8F1FC5D7908F.md) | 38
[C:\WINDOWS\SysWOW64\InfDefaultInstall.exe](InfDefaultInstall.exe-517E03BB228B5B32CE45C0C7C9D4370D.md) | 43
[C:\Windows\SysWOW64\InfDefaultInstall.exe](InfDefaultInstall.exe-85449C56339BFEF1AF92EA9E034D5D84.md) | 41

## Possible Misuse

*The following table contains possible examples of `InfDefaultInstall.exe` being misused. While `InfDefaultInstall.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `Name: Infdefaultinstall.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `  - Command: InfDefaultInstall.exe Infdefaultinstall.inf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `  - Path: C:\Windows\System32\Infdefaultinstall.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `  - Path: C:\Windows\SysWOW64\Infdefaultinstall.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #4: InfDefaultInstall.exe .inf Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #4: InfDefaultInstall.exe .inf Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #4 - InfDefaultInstall.exe .inf Execution](#atomic-test-4---infdefaultinstallexe-inf-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #4 - InfDefaultInstall.exe .inf Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Test execution of a .inf using InfDefaultInstall.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Reference: https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | \| inf_to_execute \| Local location of inf file \| string \| PathToAtomicsFolder&#92;T1218&#92;src&#92;Infdefaultinstall.inf\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | InfDefaultInstall.exe #{inf_to_execute} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Invoke-WebRequest "https://github.com/redcanaryco/atomic-red-team/raw/master/atomics/T1218/src/Infdefaultinstall.inf" -OutFile "#{inf_to_execute}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


