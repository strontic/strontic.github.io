---
title: SIHClient.exe | SIH Client
excerpt: What is SIHClient.exe?
---

# SIHClient.exe 

* File Path: `C:\WINDOWS\system32\SIHClient.exe`
* Description: SIH Client

## Hashes

Type | Hash
-- | --
MD5 | `04F2A4DD98816CAC2502A2D4AC57E4F2`
SHA1 | `395E3FBD73816E9C03509C3C93BC048E41A4AFCB`
SHA256 | `9344007D147845AAA177F3FB590AC3E5B09A6CDB1461F371568B7E2BFE1279BE`
SHA384 | `C06D6709B18F529BEE6F518C8CFB22236FCA85EBBE12F74B825E55F7BF3DC24F15C1668D8584D32BF25EF7250D43E5EC`
SHA512 | `1D5939B263FBDD4BD598A6A9D52FBDE42B20101889BCB6D2B72A8108555EBE6FD0AA2489B5436D3C69CCAF5C425C8007A619EFE22A8513D03B56830F03F68294`
SSDEEP | `12288:8run4XrdpQ4EchjwwjQOLZxb94AbOzhhFDBtFB:8run4XrQdc5QqvbLbejFDz`
IMP | `55F2B302A4E7C535368D06D731ADB8F8`
PESHA1 | `485AD4F8EF903A1C29B4207DD27A57B80E4E6739`
PE256 | `111E4598B3DB1E9BFFD6B69B895B2EEE7D5EC3C2915F27D052C9F4029AB21254`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9344007d147845aaa177f3fb590ac3e5b09a6cdb1461f371568b7e2bfe1279be/detection


## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\SIHClient.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


