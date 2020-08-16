---
title: Skype.exe | Skype
---

# Skype.exe 

* File Path: `C:\Program Files (x86)\Microsoft\Skype for Desktop\Skype.exe`
* Description: Skype

## Hashes

Type | Hash
-- | --
MD5 | `33BFBD4D3DA31EB63FF04A9C2C7E0949`
SHA1 | `CB038918070D0175AEA9D2E1729B9EDA7D1643E0`
SHA256 | `215A1ED35678346F100FDA21A84DF555EDA9FC3DA14290A74D19DFB3B85741FF`
SHA384 | `98A9712C8A7BB59E398E0A7B32E75FF4F911F33C356ED7666B94003C3108413082F71EFF9D660D7578FA3D5D12E7B097`
SHA512 | `6F2DC8E6D0277508C774DCD26991EDEA8F70F67CA59DEBEB744BE7D92458D6452D0E9C0087838DD793D6B9CEEB1DA0B4E8CD524FB2F519E5CA8F56FA01FEBE43`
SSDEEP | `1572864:jGGnP7IzXACVMPLEUuSDQ642d4fR6ChQzmha0efMBIDBWBDj3Ol4mKousFAzqEfd:TczXACVMPLEUuSDQ642SsSha06oI8j3z`

## Runtime Data

### Usage (stdout):
```Batchfile


```

### Child Processes:
Skype.exe Skype.exe Skype.exe Skype.exe

## Signature

* Status: Signature verified.
* Serial: `330000017BB47778D9105DF03500000000017B`
* Thumbprint: `BEEAE4260DF5E82B6339FC4E31EF525A26A17AD0`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Skype Software Sarl, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Skype.exe
* Product Name: Skype
* Company Name: Skype Technologies S.A.
* File Version: 8.63.0.76
* Product Version: 8.63
* Language: English (United States)
* Legal Copyright: (c) 2020 Skype and/or Microsoft


## Possible Misuse

*The following table contains possible examples of `Skype.exe` being misused. While `Skype.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_squirrel_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_squirrel_lolbin.yml) | `    - Skype` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [groundbait](https://github.com/eset/malware-ioc/blob/master/groundbait/README.adoc) | `=== Prikormka *SKYPE* modules` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [interception](https://github.com/eset/malware-ioc/blob/master/interception/README.adoc) | `C:\ProgramData\Skype\Skype.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) |       $s3 = "Skype Technologies S.A." fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


