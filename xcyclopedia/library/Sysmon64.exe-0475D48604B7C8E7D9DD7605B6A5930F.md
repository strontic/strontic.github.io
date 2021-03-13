---
title: Sysmon64.exe | System activity monitor
excerpt: What is Sysmon64.exe?
---

# Sysmon64.exe 

* File Path: `C:\SysinternalsSuite\Sysmon64.exe`
* Description: System activity monitor

## Hashes

Type | Hash
-- | --
MD5 | `0475D48604B7C8E7D9DD7605B6A5930F`
SHA1 | `851A0D2376AB2C161AE455AF632FB2097BFAC8CB`
SHA256 | `55BAD23D049A2FD801B8DECDC5D960D4E27D7F92541E8B37557B7495CA5561A2`
SHA384 | `76F1C2C62132DB214221B3CA0DB5277FF1501B554FDC60EF8AA5D7AC19513F3EFA34BD86CA9840D01AFB583780C174B9`
SHA512 | `7CD1D14C3337B927E6654B3111C01DC7064F9FBDAEA9B44DECB54A332CBB2E99A12EDA03F6119609833B25C79E6F91E0BCD572A187BBADED8539E3130F002799`
SSDEEP | `24576:KXS+xbQouAIfxvnsF2mHSgAhFxeQaTtOhdsQMCkBQcc2/X1fQa6pnZpm:KC+x8ouAIfSF24OhmfQ2X+Fdy`
IMP | `49AAA307415968B34D3FD1A72DEE6C71`
PESHA1 | `5EAB9987C785C374A064FF2C15E0B1AF378F64EA`
PE256 | `D90CBE876A8BB58E0F70CEFF72896492B2CB3D90FE22EAD82D8D89F3DCC2CAF8`

## Runtime Data

### Usage (stdout):
```cmhg

System Monitor v12.0 - System activity monitor
Copyright (C) 2014-2020 Mark Russinovich and Thomas Garnier
Sysinternals - www.sysinternals.com


```

### Usage (stderr):
```cmhg

Usage:
Install:                 C:\SysinternalsSuite\Sysmon64.exe -i [<configfile>]
Update configuration:    C:\SysinternalsSuite\Sysmon64.exe -c [<configfile>]
Install event manifest:  C:\SysinternalsSuite\Sysmon64.exe -m
Print schema:            C:\SysinternalsSuite\Sysmon64.exe -s
Uninstall:               C:\SysinternalsSuite\Sysmon64.exe -u [force]
  -c   Update configuration of an installed Sysmon driver or dump the
       current configuration if no other argument is provided. Optionally
       take a configuration file.
  -i   Install service and driver. Optionally take a configuration file.
  -m   Install the event manifest (done on service install as well).
  -s   Print configuration schema definition of the specified version.
       Specify 'all' to dump all schema versions (default is latest).
  -u   Uninstall service and driver. Adding force causes uninstall to proceed
       even when some components are not installed.

The service logs events immediately and the driver installs as a boot-start driver to capture activity from early in the boot that the service will write to the event log when it starts.

On Vista and higher, events are stored in "Applications and Services Logs/Microsoft/Windows/Sysmon/Operational". On older systems, events are written to the System event log.

Use the '-? config' command for configuration file documentation.More examples are available on the Sysinternals website.

Specify -accepteula to automatically accept the EULA on installation, otherwise you will be interactively prompted to accept it.

Neither install nor uninstall requires a reboot.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\Sysmon64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: Sysinternals Sysmon
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 12.0
* Product Version: 12.0
* Language: English (United States)
* Legal Copyright: Copyright (C) 2014-2020 Mark Russinovich and Thomas Garnier
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/55bad23d049a2fd801b8decdc5d960d4e27d7f92541e8b37557b7495ca5561a2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\Sysmon.exe](Sysmon.exe-6E515B8FF9F19DB5FFFBC1F9C9A8C612.md) | 60
[C:\Sysmon\Sysmon.exe](Sysmon.exe-6E515B8FF9F19DB5FFFBC1F9C9A8C612.md) | 60
[C:\Sysmon\Sysmon64.exe](Sysmon64.exe-0475D48604B7C8E7D9DD7605B6A5930F.md) | 100

## Possible Misuse

*The following table contains possible examples of `Sysmon64.exe` being misused. While `Sysmon64.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"sysmon64",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


