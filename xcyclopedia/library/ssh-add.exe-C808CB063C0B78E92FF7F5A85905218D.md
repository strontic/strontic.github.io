---
title: ssh-add.exe | 
excerpt: What is ssh-add.exe?
---

# ssh-add.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-add.exe`

## Hashes

Type | Hash
-- | --
MD5 | `C808CB063C0B78E92FF7F5A85905218D`
SHA1 | `911C6AFE8802F33076A551AD3E6DADEE0E2CCC5C`
SHA256 | `7E5D13C4B13BE142DA676FA5F533AA92D12F7C66AC04EC26066C271326B789E7`
SHA384 | `04BE6FBE1AE4FB5F571C9963D032995D7DD74454672D6C3A07EEF11A836FA07831A779F5B22BD7B2C3CA10D5B17F353B`
SHA512 | `3F7108CA89A7F57FE997F0440F885E5A88B33A2FC87919908E7977E34F179D1C82525EA922504457E1FE560D688270EE8D78E3798E42D84DEEB3646ACBC6B466`
SSDEEP | `6144:4NWN/DJLikLPPD4mv/uws3RrDDdgi2yZ8jiRPgaDb2O7fcCnDtS9LU9qDCLlC4F:4NWNrJPLMQ/uwypei2alOU9uCLlCq`
IMP | `5CE85084191BE301FA076E5F6FC85F6B`
PESHA1 | `B7595AA848AE9294EE43BC1EE822BFA8418E539A`
PE256 | `A7A76AB098186CDCDA291150D9347A055F2AF14270CAC3A2EB71E31560D758F7`

## Runtime Data

### Usage (stderr):
```cmhg
Error connecting to agent: No such file or directory

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\OpenSSH\ssh-add.exe |


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

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/7e5d13c4b13be142da676fa5f533aa92d12f7c66ac04ec26066c271326b789e7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 33
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 32
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 32
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 29
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-85C9EEED657E96D6F44A564586685C99.md) | 30
[C:\WINDOWS\system32\OpenSSH\ssh-add.exe](ssh-add.exe-F737665090DEB3F8DB4BD240C6D188D2.md) | 30
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-66969AA56E77953E596470C73A9004E0.md) | 33
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 36
[C:\WINDOWS\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-DF26954F0BA019850708E2ED02A560B9.md) | 33
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 21
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 36
[C:\WINDOWS\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-5B511BD11B76AD1625D71FC29FD19DDC.md) | 30
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-C086D5B994B17F0602F5FA8F5CDBE70D.md) | 30

## Possible Misuse

*The following table contains possible examples of `ssh-add.exe` being misused. While `ssh-add.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`d1d7bc9ed506b364f7713e19a35692bad50c3304` \|ssh-add \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH add (ssh-add)"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `Trojanized `sshd`, `ssh`, `ssh-add` and the target of the `libkeyutils.so.1``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `* `575bb6e681b5f1e1b774fee0fa5c4fe538308814` - Linux/Ebury - Version 0.8.0 - ssh-add`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


