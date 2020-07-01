---
title: ssh-agent.exe | 
---

# ssh-agent.exe 

* File Path: `C:\windows\system32\OpenSSH\ssh-agent.exe`
* Description: 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9FFECD197D09FF33B00D5E5B78A48146`
SHA1 | `74F3580EC1374F5A7367E157ACD76AA03EE7F7CB`
SHA256 | `79C03E83B42E3C0402680B47A2493C3C506E2D212062859BD7C4EBACA46F3AD5`
SHA384 | `062C92AFE3DDD6CF63F575635036C84FF3311471D928FB2BC731D6023F67B4CE7DBF21754D22272888952966FF3A106B`
SHA512 | `6C1077035A534C51586CF4ADAF6F7387AB3411F0C0662A3331F238D2C1F4BA007D352324B9B901ECE8838C3C458EE3526A1F88471672F8451EC87B82F7A217D5`
SSDEEP | `6144:wE7PBeGGXEkgumpLL5szsz/uyNPgfdaDb2O7fcCnDto/HOvtBCrljcz:J7J1GlvQRSyVammkfCrljcz`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
unable to start ssh-agent service, error :1058

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: OpenSSH for Windows
* Company Name: 
* File Version: 7.7.2.1
* Product Version: OpenSSH_7.7p1 for Windows
* Language: English (United States)
* Legal Copyright: 

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 36
[C:\WINDOWS\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 25
[C:\WINDOWS\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 40

## Possible Misuse

*The following table contains possible examples of `ssh-agent.exe` being misused. While `ssh-agent.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`191ab40fd464a5b80b287e848f1a4ad7fcd572ae` \|ssh-agent \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `        description = "Signature to match the clean (or not) OpenSSH agent (ssh-agent)"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


