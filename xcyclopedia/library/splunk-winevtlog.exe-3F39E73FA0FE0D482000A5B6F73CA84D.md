---
title: splunk-winevtlog.exe | Monitor windows event logs
excerpt: What is splunk-winevtlog.exe?
---

# splunk-winevtlog.exe 

* File Path: `C:\Program Files\SplunkUniversalForwarder\bin\splunk-winevtlog.exe`
* Description: Monitor windows event logs

## Hashes

Type | Hash
-- | --
MD5 | `3F39E73FA0FE0D482000A5B6F73CA84D`
SHA1 | `C6B7D8782C69A027C80B8F3E5AD39804FBFF5C58`
SHA256 | `E54380FE1578E1990C71F2AA8A98050BE96002019056216E17D831B898502F21`
SHA384 | `4B735700589E3EECBCEB8BE56939CADADD34BFD08974920AF5924A59DE1CE40C502A9E8CA13BD86C9B13BE8868B9AACA`
SHA512 | `6D4CC7AFF9F5DA2DBFA56B7741609A5D149D1CBA67346EC18AE1283756750162957D69C3D35BC0AC0ACFB4994006DDDC7C43A6289BAC45C371CC15A67A0961B0`
SSDEEP | `196608:zWqe6gpgzCBLpMy9gtzsUTW1rFQUNIFl8wDMRvxPRRUjwJEB:zY/mCBLtGPTWHJIF+P0jM0`
IMP | `2E1496526AAA190EABB9573D6C4DC049`
PESHA1 | `6040538C47C24FFF431542B948A5FBDFB9E83627`
PE256 | `99A134019B47A9DD6CFF72A3ECC1B718AF643E556EECE903C4BF1773850E361C`

## Runtime Data

### Usage (stderr):
```cmhg
Usage:
 splunk-winevtlog.exe -rm-checkpoint <log channel> /?
 splunk-winevtlog.exe -help | /?

 If there is no argument, run in modular input mode.
 -rm-checkpoint - Remove a specific checkpoint file given the log channel name.  If you don't
            specify a channel name, it will delete all of the checkpoint files belongin to event logs.

Options:



```

### Loaded Modules:

Path |
-- |
C:\Program Files\SplunkUniversalForwarder\bin\splunk-winevtlog.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `014E132916D610BB301B22ABBD994616`
* Thumbprint: `B8B4F0D3FD0571E184DEBB76A1F6DB73F30FA233`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Splunk, Inc.", O="Splunk, Inc.", L=San Francisco, S=California, C=US, SERIALNUMBER=4109614, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: splunk-winevtlog.exe
* Product Name: splunk Application
* Company Name: Splunk Inc.
* File Version: 8.2.3
* Product Version: 8.2.3 (Build cd0848707637)
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2021
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


