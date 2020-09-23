---
title: Tutorial.exe | Synaptics Pointing Device Tutorial
excerpt: What is Tutorial.exe?
---

# Tutorial.exe 

* File Path: `C:\WINDOWS\system32\DriverStore\FileRepository\synpd.inf_amd64_b28b907efbdd0634\Tutorial.exe`
* Description: Synaptics Pointing Device Tutorial

## Screenshot

![Tutorial.exe](screenshots/Tutorial.exe-812B04DAA5E1288EDF4714E5D0FF0210.png)

## Hashes

Type | Hash
-- | --
MD5 | `FC772C0369945DD093E48522E72D5C48`
SHA1 | `47A36787EB86935195C38E1470BE35B99DCC2476`
SHA256 | `B9645AE5FF6C097D577A4435B4FFF80248F2DE69D1D5ECF2E02882FD493D2C70`
SHA384 | `3B6F3618A7D6475B9E253C6681F4730446D3B61B6FB6CB969A72EBACCE42C49DC0E899078BA1B4F37738114B08DDCD5C`
SHA512 | `0C7BAC63959AF61FCFB4B42F329235A223502776BEB0CC3D265E0DAC62CE1E0A6BBCCCCEADEA4746534D5AEBAD7E09FCB08236A80F6F07DDDBC0149B1055AF89`
SSDEEP | `6144:EIrcvYbJGlNv5HAwT3Js1XD5bPyLShsNlJYRV37wTyPzemA:PUNBgwT3K5bszJYj7wTsq`

## Signature

* Status: Signature verified.
* Serial: `610C2E31000200000014`
* Thumbprint: `6700495D48ED947225EC79804D391FD00DF8E842`
* Issuer: CN=Microsoft Windows Hardware Compatibility PCA, OU=Copyright (c) 2002 Microsoft Corp., O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Tutorial.exe
* Product Name: Synaptics Pointing Device Driver
* Company Name: Synaptics Incorporated
* File Version: 15.3.29 13Oct11
* Product Version: 15.3.29 13Oct11
* Language: English (United States)
* Legal Copyright: Copyright (C) Synaptics Incorporated 1996-2011



## Possible Misuse

*The following table contains possible examples of `Tutorial.exe` being misused. While `Tutorial.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_vssadmin_ntds_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_vssadmin_ntds_activity.yml) | `- https://www.trustwave.com/Resources/SpiderLabs-Blog/Tutorial-for-NTDS-goodness-(VSSADMIN,-WMIS,-NTDS-dit,-SYSTEM)/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_creation.yml) | `- https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/tutorial-for-ntds-goodness-vssadmin-wmis-ntdsdit-system/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


