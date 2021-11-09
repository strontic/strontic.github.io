---
title: ssh-add.exe | 
excerpt: What is ssh-add.exe?
---

# ssh-add.exe 

* File Path: `C:\WINDOWS\system32\OpenSSH\ssh-add.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F737665090DEB3F8DB4BD240C6D188D2`
SHA1 | `BF2A08C8398E2EE4772B078AE492DB89A9A92A90`
SHA256 | `220341822E9F85B1366A1E6D43734E81545BB88B3637CCD6065EA10445D7D52F`
SHA384 | `BEBBA89D21D6CAFE2E6F2CCA480B3FE8D506E113BE101424A2C88B4A6BA4898E06C7A1C543D94910F967DC66E83BF6A3`
SHA512 | `C711D8FE5EFAA3C94FBEE37866C2ACF0F604D6DC516F408F3EB20F6FC6FDC3BCA034916CD60AD5A3380AA73FBBF1F11FD77E538126E8FE3C0FBCCA033C4D198E`
SSDEEP | `6144:oj1Gp4yHEHh73fZ75bZaLOW5yMUI9q8aDb2O7fcCnDtpmzIhWR:oj1GaykB73fDdOhyY22zEe`
IMP | `F0552DF15B53703E80F368F4A31DD04E`
PESHA1 | `3C0BA5E31AABEF1C74178E8B90DF7841157FA6E4`
PE256 | `D75268988FC28642860E978B248904D32F5AC510CBFDB6F31037508ACF057BDF`

## Runtime Data

### Usage (stderr):
```cmhg
Error connecting to agent: No such file or directory

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\OpenSSH\ssh-add.exe |


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

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/220341822e9f85b1366a1e6d43734e81545bb88b3637ccd6065ea10445d7d52f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 35
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 38
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 36
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 30
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-85C9EEED657E96D6F44A564586685C99.md) | 97
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 30
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-66969AA56E77953E596470C73A9004E0.md) | 41
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 35
[C:\WINDOWS\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-DF26954F0BA019850708E2ED02A560B9.md) | 38
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 24
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 33
[C:\WINDOWS\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-5B511BD11B76AD1625D71FC29FD19DDC.md) | 33
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-C086D5B994B17F0602F5FA8F5CDBE70D.md) | 33

## Possible Misuse

*The following table contains possible examples of `ssh-add.exe` being misused. While `ssh-add.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`d1d7bc9ed506b364f7713e19a35692bad50c3304` \|ssh-add \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH add (ssh-add)"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `Trojanized `sshd`, `ssh`, `ssh-add` and the target of the `libkeyutils.so.1``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `* `575bb6e681b5f1e1b774fee0fa5c4fe538308814` - Linux/Ebury - Version 0.8.0 - ssh-add`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


