---
title: LsaIso.exe | Credential Guard & Key Guard
excerpt: What is LsaIso.exe?
---

# LsaIso.exe 

* File Path: `C:\Windows\system32\LsaIso.exe`
* Description: Credential Guard & Key Guard

## Hashes

Type | Hash
-- | --
MD5 | `D9BF2CA0262F8F71556BAB579A871C34`
SHA1 | `857CA4B4235889ABA721671A1699FDBA0DB88C52`
SHA256 | `9610808D82A12F4227DF7CEAB1DD5172B120E0FB19F660B394185D1C17F297CC`
SHA384 | `5272D2A80ACC86A1B661842D84EAD7B455978EEA543453DF1AEF908224E5CC6C763C0B8178AD7C5080C271E539145A66`
SHA512 | `9492C4E95CBD65D8FA108AAD87363F689D85323584E85D9A1347671C8718F40AC28220161B724A3DD1F68797948C5BB2CE034843852998116207985FA9F240EC`
SSDEEP | `3072:HNn1cDVeN6CSi1rusmUQwPlZGtYsMpubpA9PeRRQEUN/nLnS+yhmwg4gzIeV8k:HNn1cDVepxKwv2MApEmRRINznSbpsPL`
IMP | `E20271694660EB17470CEE91AE53E0B4`
PESHA1 | `6602158D351196F59D471DD81434DF995C0E1A7B`
PE256 | `DAC519D5C4F5135AF8882F7750557C38BEF78D93D90889DD90DD84E65B263F1F`

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
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/9610808d82a12f4227df7ceab1dd5172b120e0fb19f660b394185d1c17f297cc/detection


## Possible Misuse

*The following table contains possible examples of `LsaIso.exe` being misused. While `LsaIso.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\lsaiso.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


