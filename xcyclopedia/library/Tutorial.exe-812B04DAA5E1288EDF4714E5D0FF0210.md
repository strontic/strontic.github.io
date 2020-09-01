---
title: Tutorial.exe | Synaptics Pointing Device Tutorial
---

# Tutorial.exe 

* File Path: `C:\WINDOWS\system32\DriverStore\FileRepository\synpd.inf_amd64_4e500223b4e4a9e4\Tutorial.exe`
* Description: Synaptics Pointing Device Tutorial

## Screenshot

![Tutorial.exe](screenshots/Tutorial.exe-812B04DAA5E1288EDF4714E5D0FF0210.png)

## Hashes

Type | Hash
-- | --
MD5 | `812B04DAA5E1288EDF4714E5D0FF0210`
SHA1 | `CA4ADFFBE1627C82115611731F9EF1760237BEF8`
SHA256 | `010E05E3C765C0823CFEE0D8B9C734969045807379C60BAE80480DD56B764758`
SHA384 | `F6283F1BADAA16E7040297E7170B5B822594904C58D187E06A3E53156F64244D53B1E45B4948E5E4C766BD83BA6D0D71`
SHA512 | `B4BA76D381B1DAD992196AFF467619B90230B39D99F3866BA29956B9E32079BA877E44BFDB72EA9979521ABC245F8947D753C1BE99D974F856F17096AE0D6D8B`
SSDEEP | `49152:kK5/2Emx3wO699I8OpTNpTGuG7YaAKSsGb6gg2k2fethA+IS:VOEmxw39/OpZpTGurKOb6gg2k2CQS`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tttracer.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000010D1EBBCBE1C4C7C49000100000010`
* Thumbprint: `C802CA01BC3064BFC0510CC762FFAA20BFE8EC61`
* Issuer: CN=Microsoft Windows Hardware Compatibility PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Tutorial.exe
* Product Name: Synaptics Pointing Device Driver
* Company Name: Synaptics Incorporated
* File Version: 19.0.12.95 06Jul15
* Product Version: 19.0.12.95 06Jul15
* Language: English (United States)
* Legal Copyright: Copyright (C) Synaptics Incorporated 1996-2015


## Possible Misuse

*The following table contains possible examples of `Tutorial.exe` being misused. While `Tutorial.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_vssadmin_ntds_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_vssadmin_ntds_activity.yml) | `    - https://www.trustwave.com/Resources/SpiderLabs-Blog/Tutorial-for-NTDS-goodness-(VSSADMIN,-WMIS,-NTDS-dit,-SYSTEM)/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_creation.yml) | `    - https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/tutorial-for-ntds-goodness-vssadmin-wmis-ntdsdit-system/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


