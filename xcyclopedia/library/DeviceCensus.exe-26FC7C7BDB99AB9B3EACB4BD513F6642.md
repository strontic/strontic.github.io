
# DeviceCensus.exe 

* File Path: `C:\Windows\system32\DeviceCensus.exe`
* Description: Device Census
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `26FC7C7BDB99AB9B3EACB4BD513F6642`
SHA1 | `23232E14346D850903001DC75E2BC08049658186`
SHA256 | `8210C4F78F6BEFFB8BE252988F80A34BC7F49D583C710E34611F0427FAF02C95`
SHA384 | `03AB5DFB0D5D479F077BCEFE514A33126584B48EA4E5B39DA79B61CFA6E843BF24B78828601D72E3281B0A2C60704EE9`
SHA512 | `549B74E464A4F1749912F6B23440A34CEBD727554A9D255647AB74674F80C728F42E375D38A293E64BAC9AF48906E8281CEE2362E5082DA03046547360EAA92C`
SSDEEP | `768:/rqp1ssuvWRCll0zrMF7G4i6Xf4r6wD1Pu:2jivW0+PO7GcfWPu`

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

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1035 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1035
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\DeviceCensus.exe](DeviceCensus.exe-AC7BD0E738FDE12FB29DA98D88C903EA.md) | 85

## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\DeviceCensus.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


