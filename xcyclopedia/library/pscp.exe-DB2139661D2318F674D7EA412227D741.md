---
title: pscp.exe | Command-line SCP/SFTP client
excerpt: What is pscp.exe?
---

# pscp.exe 

* File Path: `C:\Program Files\PuTTY\pscp.exe`
* Description: Command-line SCP/SFTP client

## Hashes

Type | Hash
-- | --
MD5 | `DB2139661D2318F674D7EA412227D741`
SHA1 | `3B9FCEFDFE145D17083275B971BC58CB9AAAC7B4`
SHA256 | `4C6357EC1ACB0F318B256343879F9007A4C768C5B2FFD80FD903C71296A7742A`
SHA384 | `9B99D40A0EFEF62DE3D7618F7B49F916A5A12EA6308BA8F81C055C87873775221CE91E3E141CAB1EE6801F28A51B9407`
SHA512 | `DB638B280203DACB79DB272D1586E9BB3D40FE215E7BF09FAE56A5F74E278E9E0D570C540BCBB0DEBF56EE3C155DEC7BCCBF07562F1FF7C54E75D7FAE2FE9382`
SSDEEP | `12288:AxGmVggqdesf8EEB1JOUCJslaXWHYUxZI6MsErW:QGmCUgDJsuUxZI6DcW`
IMP | `93004CB2FBB3B1E5E7DCB1A2B9829D03`
PESHA1 | `B79E287A7C7C6CCFE13696E9404167996C3AA24A`
PE256 | `B863B77F7F2E19B4C5116E01854B11AAE3BCAB610801933857FAA7A0EE00110A`

## Runtime Data

### Usage (stdout):
```cmhg
PuTTY Secure Copy client
Release 0.76
Usage: pscp [options] [user@]host:source target
       pscp [options] source [source...] [user@]host:target
       pscp [options] -ls [user@]host:filespec
Options:
  -V        print version information and exit
  -pgpfp    print PGP key fingerprints and exit
  -p        preserve file attributes
  -q        quiet, don't show statistics
  -r        copy directories recursively
  -v        show verbose messages
  -load sessname  Load settings from saved session
  -P port   connect to specified port
  -l user   connect with specified username
  -pw passw login with specified password
  -1 -2     force use of particular SSH protocol version
  -ssh -ssh-connection
            force use of particular SSH protocol variant
  -4 -6     force use of IPv4 or IPv6
  -C        enable compression
  -i key    private key file for user authentication
  -noagent  disable use of Pageant
  -agent    enable use of Pageant
  -no-trivial-auth
            disconnect if SSH authentication succeeds trivially
  -hostkey keyid
            manually specify a host key (may be repeated)
  -batch    disable all interactive prompts
  -no-sanitise-stderr  don't strip control chars from standard error
  -proxycmd command
            use 'command' as local proxy
  -unsafe   allow server-side wildcards (DANGEROUS)
  -sftp     force use of SFTP protocol
  -scp      force use of SCP protocol
  -sshlog file
  -sshrawlog file
            log protocol details to a file
  -logoverwrite
  -logappend
            control what happens when a log file already exists

```

### Usage (stderr):
```cmhg
pscp: unknown option "-help"
      try typing just "pscp" for help

```

### Loaded Modules:

Path |
-- |
C:\Program Files\PuTTY\pscp.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `7C1118CBBADC95DA3752C46E47A27438`
* Thumbprint: `5B9E273CF11941FD8C6BE3F038C4797BBE884268`
* Issuer: CN=COMODO RSA Code Signing CA, O=COMODO CA Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN=Simon Tatham, O=Simon Tatham, L=Cambridge, S=Cambridgeshire, C=GB

## File Metadata

* Original Filename: PSCP
* Product Name: PuTTY suite
* Company Name: Simon Tatham
* File Version: Release 0.76
* Product Version: Release 0.76
* Language: English (United Kingdom)
* Legal Copyright: Copyright  1997-2021 Simon Tatham.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/4c6357ec1acb0f318b256343879f9007a4c768c5b2ffd80fd903c71296a7742a/detection


## Possible Misuse

*The following table contains possible examples of `pscp.exe` being misused. While `pscp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- pscp.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | description = "Tool used in Operation Cloud Hopper - pscp.exe cloaked as rundll32.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


