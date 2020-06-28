---
title: sihost.exe | Shell Infrastructure Host
---

# sihost.exe 

* File Path: `C:\Windows\system32\sihost.exe`
* Description: Shell Infrastructure Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B19D63CBAF662531A3B9071372B86595`
SHA1 | `1D1AEDCFB4F5B05490084609B54908901B35BF54`
SHA256 | `C2194F45C7B614B4520ED551C88C2B32D2E0065EDCF3D7208086A1B0EC07D835`
SHA384 | `ECC0DA5C9DD4277348214DFFD82ED1E73012B23DD0C92949B70BEEC773856DF5B304736ABA6B277C1D6E22A3542303F2`
SHA512 | `F89366599D002AA16E59D76B05D43A7E2F15B5D358BD2DC417A2366BEA7554B8C51DA4F5F6001711C374DDB843AB15E9D6D0F02215149E6FA7774141D5BBEE08`
SSDEEP | `1536:teWBpMaPLTsVD5HRQdmM0YgNJfgJSSo1CTECC2s7SUyb76AgztlNm:tzBuaHsl5xm30fxTkECC2s7/yX6dlNm`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
explorer.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\sihost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\sihost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


