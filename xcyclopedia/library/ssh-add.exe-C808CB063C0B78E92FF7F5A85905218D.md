---
title: ssh-add.exe | 
---

# ssh-add.exe 

* File Path: `C:\WINDOWS\system32\OpenSSH\ssh-add.exe`
* Description: 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C808CB063C0B78E92FF7F5A85905218D`
SHA1 | `911C6AFE8802F33076A551AD3E6DADEE0E2CCC5C`
SHA256 | `7E5D13C4B13BE142DA676FA5F533AA92D12F7C66AC04EC26066C271326B789E7`
SHA384 | `04BE6FBE1AE4FB5F571C9963D032995D7DD74454672D6C3A07EEF11A836FA07831A779F5B22BD7B2C3CA10D5B17F353B`
SHA512 | `3F7108CA89A7F57FE997F0440F885E5A88B33A2FC87919908E7977E34F179D1C82525EA922504457E1FE560D688270EE8D78E3798E42D84DEEB3646ACBC6B466`
SSDEEP | `6144:4NWN/DJLikLPPD4mv/uws3RrDDdgi2yZ8jiRPgaDb2O7fcCnDtS9LU9qDCLlC4F:4NWNrJPLMQ/uwypei2alOU9uCLlCq`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
Error connecting to agent: No such file or directory

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
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
[C:\WINDOWS\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 36
[C:\WINDOWS\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 21
[C:\WINDOWS\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 36

## Possible Misuse

*The following table contains possible examples of `ssh-add.exe` being misused. While `ssh-add.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`d1d7bc9ed506b364f7713e19a35692bad50c3304` \|ssh-add \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `        description = "Signature to match the clean (or not) OpenSSH add (ssh-add)"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `Trojanized `sshd`, `ssh`, `ssh-add` and the target of the `libkeyutils.so.1`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `* `575bb6e681b5f1e1b774fee0fa5c4fe538308814` - Linux/Ebury - Version 0.8.0 - ssh-add` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


