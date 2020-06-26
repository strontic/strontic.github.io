---
title: sysprep.exe | System Preparation Tool
---

# sysprep.exe 

* File Path: `C:\WINDOWS\system32\Sysprep\sysprep.exe`
* Description: System Preparation Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C56186A475D4E1F077007B76F403C66B`
SHA1 | `289911F3472B8172AFABD34C8814E15644104ED1`
SHA256 | `A03A0D2C47163EE59ECCFF492BFA40367473B907065EEDCFC36EB5D94D9F78AE`
SHA384 | `51B76BD0478CD8C8CA7135E8EDE58FB167FB0A85916604E84ABBF5D6215B1EDAA9C014E523E1EBA86680CDFDDC8E0CC8`
SHA512 | `D00A3DD39D5006DCD8C8A07DB9E76F5D0FDD79F1C0549B3F8BFD8D47E502397BC2F9ECBDC61F326366642B8E47089B3BA8524061EE36B043D16B51F635A84A8D`
SSDEEP | `12288:THp7LMuRrE5+mQvI5c2I+QdxSlJGzNX5oieQ8yFWuy+PdIC+bXj:jxLMAa+mQvI598XxpFdv+bj`

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

* Original Filename: sysprep.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


