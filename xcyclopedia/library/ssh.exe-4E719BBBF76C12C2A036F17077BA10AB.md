---
title: ssh.exe | 
---

# ssh.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh.exe`

## Hashes

Type | Hash
-- | --
MD5 | `4E719BBBF76C12C2A036F17077BA10AB`
SHA1 | `352CBD32805CABBDE41BE8BFA1FD83FE26B54BFB`
SHA256 | `4C259BBBB1AB6C554C4AC65218740590B71603306D92552BDA41C951E5A6A962`
SHA384 | `0278298439B282BAA7C1F55BE9C8CB46FE18EEC46B3FF60A54089027028E13BC7DC3D33A1D4D2EADF55D57E57A1776D8`
SHA512 | `48B407C39A1191CCAF692FE7C945021A571542B78C82152B9D4508710B55645911765FB2099F303C5BEDC19069AB136E6BE11D113707C9037814FB901F79D526`
SSDEEP | `12288:GofjwKtpqCKrsKlgHCN79iHIBicblekIaZvg4fslSw:GMRtpqbaCT0aXpIaZvg4fslSw`

## Runtime Data

### Usage (stderr):
```cmhg
ssh: unknown option -- h
usage: ssh [-46AaCfGgKkMNnqsTtVvXxYy] [-B bind_interface]
           [-b bind_address] [-c cipher_spec] [-D [bind_address:]port]
           [-E log_file] [-e escape_char] [-F configfile] [-I pkcs11]
           [-i identity_file] [-J [user@]host[:port]] [-L address]
           [-l login_name] [-m mac_spec] [-O ctl_cmd] [-o option] [-p port]
           [-Q query_option] [-R address] [-S ctl_path] [-W host:port]
           [-w local_tun[:remote_tun]] destination [command]

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 


## Possible Misuse

*The following table contains possible examples of `ssh.exe` being misused. While `ssh.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - ssh.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


