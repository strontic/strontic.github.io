---
title: ssh.exe | 
excerpt: What is ssh.exe?
---

# ssh.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh.exe`

## Hashes

Type | Hash
-- | --
MD5 | `C05426E6F6DFB30FB78FBA874A2FF7DC`
SHA1 | `A0D1A4F068ED3ED585E5CEC6C787521B1C0D2D64`
SHA256 | `722BEE41CCF54B88660C0E67ADEB2C9612C18D739E5A8EB8C35C3D7066A95871`
SHA384 | `907E0B273EEE7EE1F6E3A2B0CD86868179F34F65EBBC14DCFCB50A5374715A9CE7B491AA5A210183FF4FDDEFA414405B`
SHA512 | `03772FCCA6171E8E0D4EB1661F9B3E26F5CFDCEC1961AE13B070CB9798F62453B55AA6E3484F0AA23943C6A6436D9FC65C8CBF074460C574A09AD3CDFAA66B01`
SSDEEP | `24576:Qv+JQpyx6rwQPa3VSCaKhitoCTwKee6Yy:U2QpRzPWSCatpToe6`
IMP | `91C272778494F545A220F3E427777252`
PESHA1 | `A7BC2C5C3E1A54CCC2395C96B467FAD2199E419A`
PE256 | `686480612FEC9023BF75C604F434D1B5A083AFDC427B58FC993AE1651A577EC2`

## Runtime Data

### Usage (stderr):
```cmhg
unknown option -- h
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

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\OpenSSH\ssh.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: OpenSSH for Windows
* Company Name: 
* File Version: 8.1.0.1
* Product Version: OpenSSH_8.1p1 for Windows
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/722bee41ccf54b88660c0e67adeb2c9612c18d739e5a8eb8c35c3d7066a95871/detection


## Possible Misuse

*The following table contains possible examples of `ssh.exe` being misused. While `ssh.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- ssh.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


