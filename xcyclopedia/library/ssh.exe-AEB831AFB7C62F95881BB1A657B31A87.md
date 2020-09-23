---
title: ssh.exe | 
excerpt: What is ssh.exe?
---

# ssh.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh.exe`

## Hashes

Type | Hash
-- | --
MD5 | `AEB831AFB7C62F95881BB1A657B31A87`
SHA1 | `164A5EDF43E62ACE4BC45933256E62AFC950A259`
SHA256 | `937F3317FAD790C1F3980CB12B31CA6D000698AB99E31839F1CFEC575E4193B7`
SHA384 | `1FA26EAB97DB6DCEB9B371FED199C0E22457D0839784A5B4AE01A9CF1A614199FFAA6FBCF62CE14B35F3406DDE74680D`
SHA512 | `9EAC505C9159A74FC499F80082C905C6063200AD15C694D1F42D50CC9ACD0F81A84535DD28BEDB06D942E7D18B367D20BA805E50DC6363FF6AD68AF1BD2BDBC5`
SSDEEP | `12288:XeE4ifbr/+wuWTqZXOF3UGMmCONFzS7ifsSZSJ:XZ4i2wiZ+Fam9FzS7ifsSZSJ`

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

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh.exe](ssh.exe-AEB831AFB7C62F95881BB1A657B31A87.md) | 100

## Possible Misuse

*The following table contains possible examples of `ssh.exe` being misused. While `ssh.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- ssh.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


