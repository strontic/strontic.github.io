---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
excerpt: What is WmiApSrv.exe?
---

# WmiApSrv.exe 

* File Path: `C:\WINDOWS\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `A7E5AE42982C429DB3E5E35EAAFD3CA2`
SHA1 | `AC0198DCE2723D2254276BDB36ACA35157478001`
SHA256 | `33558E742299D9CBDA7BE206731DFD90DF65DA7DECAE648AF8F573CE68FB2E41`
SHA384 | `1771807EE6ABCDF34D71B40D88B5635E79300E449B301FB0C0BF312C8850EC468D97547B21F13E66B370DCBB87BA2520`
SHA512 | `35D969FEFA00F395C638D7F26FDB4811E9310BA7FB04EAD7FAE2355B3DEC3B7BF713C33196666E0B22882CF80D26F29A229BD83EAFC922265509D1D2C4042A36`
SSDEEP | `3072:CUcreRyrWsoYE2TYBFouSbl+HhsPcx+7b+pVqORvdkc9ie:CUcreRyrWTYE2sBfmaaauORvdkc9i`
IMP | `4334F3348CCC03846956880F91FEC500`
PESHA1 | `D949479B6799951FC9D1CEDC1E5290BFD021E636`
PE256 | `D97EB03D56BD5CCF1324CB2733D385819FDF050D0A46B405DD788904B98ED378`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\system32\wbem\WmiApSrv.exe |
C:\WINDOWS\SYSTEM32\wbemcomn.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/33558e742299d9cbda7be206731dfd90df65da7decae648af8f573ce68fb2e41/detection


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiApSrv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


