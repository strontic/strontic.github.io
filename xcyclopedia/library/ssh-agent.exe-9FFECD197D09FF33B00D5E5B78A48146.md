---
title: ssh-agent.exe | 
excerpt: What is ssh-agent.exe?
---

# ssh-agent.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-agent.exe`

## Hashes

Type | Hash
-- | --
MD5 | `9FFECD197D09FF33B00D5E5B78A48146`
SHA1 | `74F3580EC1374F5A7367E157ACD76AA03EE7F7CB`
SHA256 | `79C03E83B42E3C0402680B47A2493C3C506E2D212062859BD7C4EBACA46F3AD5`
SHA384 | `062C92AFE3DDD6CF63F575635036C84FF3311471D928FB2BC731D6023F67B4CE7DBF21754D22272888952966FF3A106B`
SHA512 | `6C1077035A534C51586CF4ADAF6F7387AB3411F0C0662A3331F238D2C1F4BA007D352324B9B901ECE8838C3C458EE3526A1F88471672F8451EC87B82F7A217D5`
SSDEEP | `6144:wE7PBeGGXEkgumpLL5szsz/uyNPgfdaDb2O7fcCnDto/HOvtBCrljcz:J7J1GlvQRSyVammkfCrljcz`
IMP | `C3450B747B22F2447BB5C3214451ADA3`
PESHA1 | `9F39153A279CFDFF7AB7DFAE1A83900ED6EF90B5`
PE256 | `FD6D1ECE2E8DAA5ADAD01E4E3CF1589F502A3BA62FEF25896C5FA58889BB9AD4`

## Runtime Data

### Usage (stderr):
```cmhg
unable to start ssh-agent service, error :1058

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\OpenSSH\ssh-agent.exe |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/79c03e83b42e3c0402680b47a2493c3c506e2d212062859bd7c4ebaca46f3ad5/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 38
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 38
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 35
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 33
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 36
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 25
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 40

## Possible Misuse

*The following table contains possible examples of `ssh-agent.exe` being misused. While `ssh-agent.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`191ab40fd464a5b80b287e848f1a4ad7fcd572ae` \|ssh-agent \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH agent (ssh-agent)"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


