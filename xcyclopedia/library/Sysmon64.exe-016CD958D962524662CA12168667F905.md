---
title: Sysmon64.exe | System activity monitor
excerpt: What is Sysmon64.exe?
---

# Sysmon64.exe 

* File Path: `C:\WINDOWS\Sysmon64.exe`
* Description: System activity monitor

## Hashes

Type | Hash
-- | --
MD5 | `016CD958D962524662CA12168667F905`
SHA1 | `5F2F8DA866C401DC0D1C60EF10EBF1C69102590B`
SHA256 | `C8477524849148FFB52B1B597FC891B4833142DCB9ACA7947730F734E241E001`
SHA384 | `F4EDE479FFCA709F98AA53EC2B442088BE20212DED0D26C347867FBD62DC2A57CA0DFE48208CCC1D89C7C1934E355279`
SHA512 | `2D040EE6A0F74E2FDDE46F106EFE3736EA220C4CAA6A65A63C09F2B96EBDF1097D0F65A2A5FD45FCBAE4F2607B86C3932528BCE82E1771C08C3FB048ADA8748B`
SSDEEP | `24576:SOBRF+n9SDmKlWswHfrmQGPTQzmQBe2n6prjZRKvgsvC1fwz2p3014kbyqXBzAE2:L+n9smKl2C1oz+014kbyqXBnOb`

## Runtime Data

### Usage (stdout):
```cmhg

System Monitor v7.02 - System activity monitor
Copyright (C) 2014-2018 Mark Russinovich and Thomas Garnier
Sysinternals - www.sysinternals.com


```

### Usage (stderr):
```cmhg

Usage:
Install:    C:\WINDOWS\Sysmon64.exe -i [<configfile>]
              [-h <[sha1|md5|sha256|imphash|*],...>] [-n [<process,...>]]
              [-l [<process,...>]
Configure:  C:\WINDOWS\Sysmon64.exe -c [<configfile>]
              [--|[-h <[sha1|md5|sha256|imphash|*],...>] [-n [<process,...>]]
              [-l [<process,...>]]]
Uninstall:  C:\WINDOWS\Sysmon64.exe -u
  -c   Update configuration of an installed Sysmon driver or dump the
       current configuration if no other argument is provided. Optionally
       take a configuration file.
  -d   Specify the name of the installed device driver image.
       Configuration entry: DriverName.
       The service image and service name will be the same
       name of the Sysmon.exe executable image.
  -h   Specify the hash algorithms used for image identification (default
       is SHA1). It supports multiple algorithms at the same time.
       Configuration entry: HashAlgorithms.
  -i   Install service and driver. Optionally take a configuration file.
  -l   Log loading of modules. Optionally take a list of processes to track.
  -m   Install the event manifest (done on service install as well).
  -n   Log network connections. Optionally take a list of processes to track.
  -r   Check for signature certificate revocation.
       Configuration entry: CheckRevocation.
  -s   Print configuration schema definition of the specified version.
       Specify 'all' to dump all schema versions (default is latest).
  -u   Uninstall service and driver.

The service logs events immediately and the driver installs as a boot-start driver to capture activity from early in the boot that the service will write to the event log when it starts.

On Vista and higher, events are stored in "Applications and Services Logs/Microsoft/Windows/Sysmon/Operational". On older systems, events are written to the System event log.

If you need more information on configuration files, use the '-? config' command. More examples are available on the Sysinternals website.

Specify -accepteula to automatically accept the EULA on installation, otherwise you will be interactively prompted to accept it.

Neither install nor uninstall requires a reboot.


```

## Signature

* Status: Signature verified.
* Serial: `33000001797C2E574E52E1CAD6000100000179`
* Thumbprint: `5EAD300DC7E4D637948ECB0ED829A072BD152E17`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: Sysinternals Sysmon
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 7.02
* Product Version: 7.02
* Language: English (United States)
* Legal Copyright: Copyright (C) 2014-2018 Mark Russinovich and Thomas Garnier



## Possible Misuse

*The following table contains possible examples of `Sysmon64.exe` being misused. While `Sysmon64.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"sysmon64",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


