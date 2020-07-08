---
title: regedt32.exe | Registry Editor Utility
---

# regedt32.exe 

* File Path: `C:\windows\system32\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `21A5E8E802DE750575AE1FE9EB4CCBFA`
SHA1 | `14B5F144402DD793958799EF9E0EB25F3C20597C`
SHA256 | `8E0AFE17637281A257CA5BCAE90CE4AA9EF4E9C2EC57B16DFDA08B27DCC6C72F`
SHA384 | `3D5BE37DA429158D35207C1C9BC814D911F7BACD144B44564D20D67DE29665D979400030DB554A3DD4869C0656E919F0`
SHA512 | `EC8316EC73DDF85C33E09A827F2B50FBA1DF371B7200F2EC44F6C89047E2939F36FB34D15D0E11A6B613177F14D555F28AD2732A4443C6C85589601B6C73405C`
SSDEEP | `192:E2ry5uafCNQdQ54r1yQ7CuMKzgNi6xtU/1EWQxW:E2ujS2RF7CucNi8tQEWQxW`

### Child Processes:
regedit.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: regedt32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\regedt32.exe](regedt32.exe-A7F7948EAA6287A29805FFD997E4016F.md) | 60

## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) |       $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


