---
title: provtool.exe | Provisioning package runtime processing tool
---

# provtool.exe 

* File Path: `C:\Windows\system32\provtool.exe`
* Description: Provisioning package runtime processing tool

## Hashes

Type | Hash
-- | --
MD5 | `54C240067FD03376785CAB273CE07494`
SHA1 | `FF0B663DFB84EABC181C36E7B6D177E5E03BCDD4`
SHA256 | `CFFB7B74EE1F49C6C27B5CE5B72CD3D3BA455B98961DE6C3ADE9BB7A584A3BE2`
SHA384 | `688CA650017978487B76B3130AF79B20AE792D5DA7BEA94FB2C6CE404DACB75C1E8634349C8DABDE0A825FB8D07D5EBE`
SHA512 | `5A7BA21C65C9FA8764D9CE1FA770690ACD7884ECF0C918C2F34C1229806C1A7AB6BDF0E1F266C427DDBCC7CF09A70195A824496BCECA45BCB82DC1943664F64D`
SSDEEP | `1536:JdSSEqWBb3ZIbP58PK/U3zDxXmXoN9LK7KMOKF5NkFWhM7Ozg8c7bXoNKoB:ed3ZIbP58PKc3PxXmX8KrlD+gKOc8khS`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: provtool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.153 (WinBuild.160101.0800)
* Product Version: 10.0.19041.153
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `provtool.exe` being misused. While `provtool.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\provtool.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


