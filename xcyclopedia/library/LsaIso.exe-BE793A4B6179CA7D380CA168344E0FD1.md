---
title: LsaIso.exe | Credential Guard
excerpt: What is LsaIso.exe?
---

# LsaIso.exe 

* File Path: `C:\Windows\system32\LsaIso.exe`
* Description: Credential Guard

## Hashes

Type | Hash
-- | --
MD5 | `BE793A4B6179CA7D380CA168344E0FD1`
SHA1 | `A0CA299EB5904C03889CAE33C2B13007CC069F5C`
SHA256 | `06F7BD6FE8ECE75B38E6CDBFE8D7CA9767FE1AD638A82671D6A4C855FD538BB6`
SHA384 | `48DDCA0AC83252552405895C01ABAC8A69D1A047E8D7F41BC3ED0A751760A2CFE8B574B51933627A9A9172BA6836CF0E`
SHA512 | `E6AEDC6933727A5EA62EEF249DA6BDD481A0D407C8F701F6CC0C5BD02DB7B9F35BCCC4A913AFD3296B9DEAEF1108784C61D8F37B1A8AC83A0F24B06BF77A1195`
SSDEEP | `3072:aD0pGEPBmKdDxPPqmpax5FN27JzWpaQmTs3vIAqazg3o243NmaW9j+vS:aD04EPB9DEmsx5FWzWpvqyvIuB09n`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LsaIso.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.3659 (rs1_release_1.200410-1813)
* Product Version: 10.0.14393.3659
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `LsaIso.exe` being misused. While `LsaIso.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\lsaiso.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


