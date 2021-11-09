---
title: ssh-agent.exe | 
excerpt: What is ssh-agent.exe?
---

# ssh-agent.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-agent.exe`

## Hashes

Type | Hash
-- | --
MD5 | `66969AA56E77953E596470C73A9004E0`
SHA1 | `2F8B62377C8AD5CA10E6EFF6D46C81AF9D41DE4E`
SHA256 | `71F4CC7595C6D5E93AAA14259DF817C6C1D4BBCF285545FD980F6DBC86A30379`
SHA384 | `7A2DDDC3261DCA6C4D5C7E6130203CF993A832C769EF2E0C46A17CF94D607DFF313EBBB64155096369A874ADFD247D35`
SHA512 | `9E6076950D984301A650602B9475EEEE7D25D2EC72CFCFFE9A5160864B84F507918EAE0B9450E03EF272845A0D7FB7F0DEAE3CE7FB0211EDC83FD7B481750969`
SSDEEP | `6144:jGTfOEijwWAL4DfLOxYuaDb2O7fcCnDt+jvAgHv9MA:qOb3A4LWOsvAYFT`
IMP | `883B9C85AA02333EA08E2428BC2DEF05`
PESHA1 | `36E584904C81D119FF0CACFB0230B50FB7E4E55C`
PE256 | `2EF4DE3F2E792341E4FE554BC62287F5C6FBE3FC03162F1F2C646DA09FB22FBA`

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
* VirusTotal Link: https://www.virustotal.com/gui/file/71f4cc7595c6d5e93aaa14259df817c6c1d4bbcf285545fd980f6dbc86a30379/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 36
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 35
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 38
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 36
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-85C9EEED657E96D6F44A564586685C99.md) | 43
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 33
[C:\WINDOWS\system32\OpenSSH\ssh-add.exe](ssh-add.exe-F737665090DEB3F8DB4BD240C6D188D2.md) | 41
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 41
[C:\WINDOWS\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-DF26954F0BA019850708E2ED02A560B9.md) | 96
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 24
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


