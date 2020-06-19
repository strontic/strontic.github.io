
# SIHClient.exe 

* File Path: `C:\Windows\system32\SIHClient.exe`
* Description: SIH Client
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2BE0B7C0835F13C047E5DD00C5B5B909`
SHA1 | `C2CC2446255F1CBADE734595B85DAC8B40653B1B`
SHA256 | `89EF3C211E59258DC7242A71B4E4BB7E517DE253FD4F2FA5B1ADF3877CAFF081`
SHA384 | `9AB836CF2A320ACEB32BCF4C383008476DDA78B093C250E720A487A5A07EDBF5E520161CE3F5E199A827632D0EA5E381`
SHA512 | `E5F298B3B80B63348628B27466D99E87CC1A9616810613F5FFA7B45F3235190E0FB2840AED194A3E9B8233D05E3FA4744C531042B70AC7B74D048049C1B53C4B`
SSDEEP | `6144:A8RnN/1W1K6dkSgvDIFawwdw05OhfHUx:AgWVSVDIFKdb52f`

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

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


