---
title: ssh-add.exe | 
excerpt: What is ssh-add.exe?
---

# ssh-add.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe`

## Hashes

Type | Hash
-- | --
MD5 | `2A1DED146AD791D52F68B6F165BB11CC`
SHA1 | `932A2388F11CBB0E34261D04C81050062507EB7A`
SHA256 | `1474FB75C3ED1F742CB34D13C870EB6EB934A6072F2A2373625B17F39B7FD4DA`
SHA384 | `6F485E9527FE3AF00D664C10DEADF9E14D4270C1EA0428C12D9028F1C41EAC629B1183B0AC05A9A75AA219FC75415C45`
SHA512 | `7212F6F6B4D038AEDBC481448962FAFAF6BADF9111117F83ABB2B6F484378E8F5DD7E7B03AFAD55755B992206CC0DB82818EB2099FA3699C2D963017F76EF446`
SSDEEP | `6144:f1kf4r82JLpm3UNS4xFBDb2O7fcCnDtie5N7Oxtzf5W9vt:f1kQfJLpm3UNjZTN7stzf5W9v`

## Runtime Data

### Usage (stderr):
```cmhg
Could not open a connection to your authentication agent.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe |
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
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 46
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 44
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 43
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 32
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 35
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 33

## Possible Misuse

*The following table contains possible examples of `ssh-add.exe` being misused. While `ssh-add.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`d1d7bc9ed506b364f7713e19a35692bad50c3304` \|ssh-add \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH add (ssh-add)"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `Trojanized `sshd`, `ssh`, `ssh-add` and the target of the `libkeyutils.so.1`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `* `575bb6e681b5f1e1b774fee0fa5c4fe538308814` - Linux/Ebury - Version 0.8.0 - ssh-add` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


