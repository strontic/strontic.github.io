---
title: RuntimeBroker.exe | Runtime Broker
---

# RuntimeBroker.exe 

* File Path: `C:\windows\system32\RuntimeBroker.exe`
* Description: Runtime Broker
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C192FDE4036DAC07BF61B911B68777F2`
SHA1 | `4E65D9D92A8CA0E332D841C3650E089FBE1F7A98`
SHA256 | `C52BEE78658C897AB70714EE4600A4FD509C7362F4DDDFD1FC643FF52D6BA314`
SHA384 | `9FCFCA92FAF9A61D890BC8E9432C43B578D2DFD3E55FBD0AD1A762D3DF927AEF6D9BAE411B83CAC5A1FE2CFC260F97A8`
SHA512 | `202D224A2399F0F8FCE351C9842C4F2E7E0A9F9B124F693963347672653B9B5B754F2179313FBF073724FA9D85046996E5B69A25D36B60183097E96BD91E46DB`
SSDEEP | `768:vTMdmQVbubIFRK5LWtWtEZobxFOQ1i1PgfqH:LFQVuIFA5LW8iobxMQ1yPu4`

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
* Serial: `330000004EA1D80770A9BBE94400000000004E`
* Thumbprint: `DF3B9B7E5AEA1AA0B82EA25F542A6A00963AB890`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\RuntimeBroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\runtimebroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\RuntimeBroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\RuntimeBroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\runtimebroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


