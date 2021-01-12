---
title: vssagent.exe | VssAgent, Volume Shadow Copy Service (VSS) support tool
excerpt: What is vssagent.exe?
---

# vssagent.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\vssagent.exe`
* Description: VssAgent, Volume Shadow Copy Service (VSS) support tool

## Hashes

Type | Hash
-- | --
MD5 | `D7C2815B92C3D38673558BDBE0F40164`
SHA1 | `DB7FE0CFA64C5D7F0DF35886C17CC4668AE5A653`
SHA256 | `A25C2879F596110967C11DB1CB433271BC2F342BCB16A884AFBFC784A2416F51`
SHA384 | `8677571ED31B61885FA989A97B02154E9A856D459133112A459D350A44BBE2DC8509645C24A7144554A372E856C1DA93`
SHA512 | `B65B8483E7C14302A7FAD2EC5F20621C4A7109CD11206E6922C0A5DEFA751DA79F49B9213A72BA25DADB4FC499C472F663DE6AB109A4239168D7FC07526CCED1`
SSDEEP | `6144:36PWPW/OmPr+NJoBjDd7SdnCCJyq/74pcLFrOe5iKzWk955MtH73BNW99Wn4:KeuPyN8NSdn14pmr55N955Obw`
IMP | `A534F8D8F5661B16D014BE792F84B051`
PESHA1 | `00E5DF2D341C85D503DE30B1BD9BE33FFEF75FA9`
PE256 | `9F3CBAEC7EF2B48CE362725C9632FF5E992B24CE20393D489C5553F2DF0AE6C3`

## Runtime Data

### Usage (stdout):
```cmhg

VSSAGENT application, version 10.0.19041.1 (WinBuild.160101.0800)


--------------- Print supported commands ------------


Usage:
  * Monitor the given HW provider
    VSSAGENT -monitor <provider_id> <xml_file>

  * Monitor the disk/volume PNP messages
    VSSAGENT -pnpmonitor <xml_file>

  * Gather diagnose data
    VSSAGENT -gather <xml_file>

  * Enable lightweight VSS diagnose mode
    VSSAGENT -enablediag

  * Disable lightweight VSS diagnose mode
    VSSAGENT -disablediag

  * Stop VSSAGENT
    VSSAGENT -stop

  * Cleanup if VSSAGENT abnormally terminates
    VSSAGENT -cleanup <provider_id>

  * Make an analysis summary while monitoring
    VSSAGENT -makesummary

  * Set parameters for VSS diagnose
    VSSAGENT -setparam <param_name> <param_value>

  * List all vss diagnose parameters
    VSSAGENT -listparams



```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\vssagent.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vssagent.exe
* Product Name: VssAgent
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


