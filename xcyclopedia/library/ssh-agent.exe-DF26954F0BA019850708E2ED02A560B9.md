---
title: ssh-agent.exe | 
excerpt: What is ssh-agent.exe?
---

# ssh-agent.exe 

* File Path: `C:\WINDOWS\system32\OpenSSH\ssh-agent.exe`

## Hashes

Type | Hash
-- | --
MD5 | `DF26954F0BA019850708E2ED02A560B9`
SHA1 | `B3912346D7C279817500F79E69F15BAC4833FB8B`
SHA256 | `1EA4BF3F1930E288362C6961DAF3C10BA1FAF72E7BD8085F6C965095EC9E792A`
SHA384 | `F64D88104B29E984BAB9E6C16753C16E27D58FDAA10DFCF233EE1EC829004780AA9B03572700F96FB4E7D7B9C371CA30`
SHA512 | `7D95DFF7F4BFB25B02C413F1D1AE2A8267B8BE314737C2A7F95B648D32C932E8588F2CA95A4D5ACE25776B693C278969EAD8707E6FF781241FDD2BB3ADD31B46`
SSDEEP | `6144:7GTfOEijwWAL4DfLOxYuaDb2O7fcCnDtYjvAgHv9MA:yOb3A4LWO+vAYFT`
IMP | `883B9C85AA02333EA08E2428BC2DEF05`
PESHA1 | `9E4DA9588EFDCB7FA87F27B695637BC7A7C52969`
PE256 | `3D2A9D42C00E1520926286750D1EDE027320C7D2544F02B372B9D1D81E40A81D`

## Runtime Data

### Usage (stderr):
```cmhg
unable to start ssh-agent service, error :1058

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\OpenSSH\ssh-agent.exe |


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

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/1ea4bf3f1930e288362c6961daf3c10ba1faf72e7bd8085f6c965095ec9e792a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 36
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 36
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 38
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 36
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-85C9EEED657E96D6F44A564586685C99.md) | 41
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 33
[C:\WINDOWS\system32\OpenSSH\ssh-add.exe](ssh-add.exe-F737665090DEB3F8DB4BD240C6D188D2.md) | 38
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-66969AA56E77953E596470C73A9004E0.md) | 96
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 43
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 22
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 36
[C:\WINDOWS\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-5B511BD11B76AD1625D71FC29FD19DDC.md) | 36
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-C086D5B994B17F0602F5FA8F5CDBE70D.md) | 36

## Possible Misuse

*The following table contains possible examples of `ssh-agent.exe` being misused. While `ssh-agent.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`191ab40fd464a5b80b287e848f1a4ad7fcd572ae` \|ssh-agent \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH agent (ssh-agent)"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


