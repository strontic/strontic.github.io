---
title: pscp.exe | Command-line SCP/SFTP client
---

# pscp.exe 

* File Path: `C:\Program Files\PuTTY\pscp.exe`
* Description: Command-line SCP/SFTP client

## Hashes

Type | Hash
-- | --
MD5 | `ED0F42E7985B4E9FF805EACEFDC19042`
SHA1 | `FED8575CA2D47CF40035456052B3A32F55D1C5FC`
SHA256 | `7076D74C383B34556F60007BB349AA8D2C17B32000500CE118DF5143C147A0FA`
SHA384 | `6B5C3C00724D9E54FF3BD7A27775D21C91DBF5CC31031958622847566000535457934FC092B4D20683603D3C1FE723D3`
SHA512 | `427F0E033B0A7B0DF4067E864DFBB7C8D89B57C5F3D21A547F7AE079E3CC12495DA16339921DB9AEDCA21C95E53CC2090EB9AF58C85BA5A6F5C49BB34FF58D13`
SSDEEP | `12288:HtEhCaM1f1xKTKNkO5IbKonRKqpTZKasgQOaX1:ujOKWpStnR1TZKasv`

## Runtime Data

### Usage (stdout):
```Batchfile
PuTTY Secure Copy client
Release 0.74
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
  -4 -6     force use of IPv4 or IPv6
  -C        enable compression
  -i key    private key file for user authentication
  -noagent  disable use of Pageant
  -agent    enable use of Pageant
  -hostkey aa:bb:cc:...
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

```

### Usage (stderr):
```Batchfile
pscp: unknown option "-help"
      try typing just "pscp" for help

```

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
* File Version: Release 0.74
* Product Version: Release 0.74
* Language: English (United Kingdom)
* Legal Copyright: Copyright  1997-2020 Simon Tatham.


## Possible Misuse

*The following table contains possible examples of `pscp.exe` being misused. While `pscp.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - pscp.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) |       description = "Tool used in Operation Cloud Hopper - pscp.exe cloaked as rundll32.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


