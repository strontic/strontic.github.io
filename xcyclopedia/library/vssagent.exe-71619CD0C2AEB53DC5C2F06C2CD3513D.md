---
title: vssagent.exe | VssAgent, Volume Shadow Copy Service (VSS) support tool
excerpt: What is vssagent.exe?
---

# vssagent.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\vssagent.exe`
* Description: VssAgent, Volume Shadow Copy Service (VSS) support tool

## Hashes

Type | Hash
-- | --
MD5 | `71619CD0C2AEB53DC5C2F06C2CD3513D`
SHA1 | `3AD30E869C14B722BACF721F2014EE73B19A71B3`
SHA256 | `523B81599DDF819C5B89BC08C1E73F8ADA702C07A05D97AEB86C9353ECF9DF23`
SHA384 | `09F3989083447E0B826D6E360244F628245969CBBFABB48B1997385EFC35F2D0016F137BAA25EEEBDEA44332218444CF`
SHA512 | `05F26D15A6AD7CD096F41951B9DFE70276E6CD077C5283A1E554EA27815FD128C9F11BF938F31319892A9DCC59AC675B932C053C31B7B6E9D85611B306494B4D`
SSDEEP | `6144:v/y55MNVM8GLWk4Isi//qbFDKCVweIXsdU/sD5:v/y55eK8GJvqhKKlss9`
IMP | `C7DB862FDC42DCDF0D9E319687995651`
PESHA1 | `74582BF05056BA03B0A5CBCCBDE2899B0370504F`
PE256 | `8F54C66C039BFFA66AF57220086C86939A20A084DB1259469B07631EEE34FCD4`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\vssagent.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


