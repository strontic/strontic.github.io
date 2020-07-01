---
title: sysprep.exe | System Preparation Tool
---

# sysprep.exe 

* File Path: `C:\windows\system32\Sysprep\sysprep.exe`
* Description: System Preparation Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2C4DA745709076C61C11BE5B60B489EF`
SHA1 | `548F63F71A0E1852BA13556362BFA7B4DC8F1A90`
SHA256 | `71EF84A9A310E34483CE3D40D805743F2D59DE1D3ADAD3F1639A6CFDAAE08EFD`
SHA384 | `812A3B88C2C9CCEB2797670437A0C1729F2855C3952E7E3D56A46984CEFF690828D222BA4DA69081F7F2748C407B4DA5`
SHA512 | `06D08ABA7EB5568706C422DF2501112114C453AC6B899A2B8626D0B183A41578844C47F61CE34FB1A87281C1E5EDCF9DF37A602B88F49682FC45F07DE4B6AD3F`
SSDEEP | `12288:FHa9tyNNPsBzdhC8p82hnxa+Xoz4ztWYhaBTrGqdV/3z35oJnJgi:FHa9ty3PsNdhHp82JYv7NGqdd35o`

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

* Original Filename: sysprep.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sysprep.exe` being misused. While `sysprep.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `title: Sysprep on AppData Folder` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `description: Detects suspicious sysprep process start with AppData folder as target (as used by Trojan Syndicasec in Thrip report by Symantec)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `            - '*\sysprep.exe *\AppData\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `            - sysprep.exe *\AppData\\*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


