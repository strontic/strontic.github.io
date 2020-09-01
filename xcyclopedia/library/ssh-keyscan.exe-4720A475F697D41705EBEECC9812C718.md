---
title: ssh-keyscan.exe | 
---

# ssh-keyscan.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-keyscan.exe`

## Hashes

Type | Hash
-- | --
MD5 | `4720A475F697D41705EBEECC9812C718`
SHA1 | `DD2F92FB532DFF61E3EEA3C2B9789D10208444E8`
SHA256 | `965ACD45BD7D44FD374D3E598E88148AFFD8C7C148EA846167FB04F7837A5503`
SHA384 | `48AE80576BDF525BB854B7D1051F028FBDF0024678F2C0742DD9C7DD5F6AB413D2A20092C122083A85A8BD7BB9C92097`
SHA512 | `285FEF404DDF66CD5CF77342C43FCF82F0E2E51405590DD0FC1CF558549576F605A9A3787DC694FDEDE5F02A104FE3B9E9E92574CC6AC7E3647E00B9C756DBD9`
SSDEEP | `6144:EM8cYMUe6/LztG7NFm7tUp/GXusKK2tiaDb2O7fcCnDtiZgcaGHCSlhoWksAYX:EcIztcexUp/TbXBSa2CSl6WX`

## Runtime Data

### Usage (stderr):
```Batchfile
unknown option -- h
usage: ssh-keyscan [-46cDHv] [-f file] [-p port] [-T timeout] [-t type]
		   [host | addrlist namelist]

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\Administrator\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


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
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 35
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 33
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 33
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 32
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 36
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 40
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 21

## Possible Misuse

*The following table contains possible examples of `ssh-keyscan.exe` being misused. While `ssh-keyscan.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`c4070d1ad35070c8df2914bf56ad554e18af4961` \|ssh-keyscan \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `        description = "Signature to match the clean (or not) OpenSSH keyscan (ssh-keyscan)"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


