---
title: ssh.exe | 
excerpt: What is ssh.exe?
---

# ssh.exe 

* File Path: `C:\WINDOWS\system32\OpenSSH\ssh.exe`

## Hashes

Type | Hash
-- | --
MD5 | `1A3F4B4B3DD985287A3CDF97D9288F13`
SHA1 | `4A2B70ABF9A1DEE82B20B78D96CCF58BFAF2CA16`
SHA256 | `0D6B181EDC282E0F14B3DB6C59235290B1A5E7772F3FCF859FE7E92D57FEC9FC`
SHA384 | `ABF277BFC7D1F9686DDD0DA62EEF44E159F62EE01DD58187FE72B10FC9F4ED20B2192C917760BAA648BD572F64ECD3A5`
SHA512 | `8DD8367B0CF20E11B156B4F9060C84410DB078E7EB4A751AC7A014C3C71B85DB9EE11539462F249DDB6403C02A1CE6F30D64E9749C15AD8AF33A4738BA69FFCA`
SSDEEP | `24576:kv+JQpyx6rwQPa3VSCaKhitoCTwKee8Yy:o2QpRzPWSCatpToe8`
IMP | `91C272778494F545A220F3E427777252`
PESHA1 | `D9BBD54E0182679937A3F9FDF07B56A0104BEA50`
PE256 | `16D3E1FD162AADF12134C7E8A976C979AE175821C8FC5B822BD31CA80CEC44F6`

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
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\OpenSSH\ssh.exe |


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

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/0d6b181edc282e0f14b3db6c59235290b1a5e7772f3fcf859fe7e92d57fec9fc/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenSSH\ssh.exe](ssh.exe-C05426E6F6DFB30FB78FBA874A2FF7DC.md) | 96

## Possible Misuse

*The following table contains possible examples of `ssh.exe` being misused. While `ssh.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- ssh.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


