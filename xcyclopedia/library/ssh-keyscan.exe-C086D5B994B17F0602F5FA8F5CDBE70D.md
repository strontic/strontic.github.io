---
title: ssh-keyscan.exe | 
excerpt: What is ssh-keyscan.exe?
---

# ssh-keyscan.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-keyscan.exe`

## Hashes

Type | Hash
-- | --
MD5 | `C086D5B994B17F0602F5FA8F5CDBE70D`
SHA1 | `C374387D5B55E3283CD72EB56B2993D539D7B6E7`
SHA256 | `2BA00213F3E384CDC396DCCD5A58F17A9DADA923AE8DB5104ECF4AF972FE8FFE`
SHA384 | `D521201F730317EE3824B85380E3753A4DB2F027F8B7403A1B3DF2B2A4B91E61B70398001CE28AADF9DC83582C34921D`
SHA512 | `509B49EC44DB3E8AD96E3262310F0FE7CCA92ED1B91681103750556889E56799AB7CDE8B1DAD3D38345E075715DD07B49AD0C7EE523914CADC97EC7FF8C27DB0`
SSDEEP | `6144:TCQYoUvES8zncmaAKwtBWkla/f2bR2przpmaDb2O7fcCnDtmaTBF7z77aH++:FXUcIdAFtEkY/mgFzRoaT37zz+`
IMP | `4A0F801AC222681F5D8400903EE8A39D`
PESHA1 | `A9F7A15C87ADC24503C81AAA0CBD3E07857309FF`
PE256 | `03A20C9C2D58C580D06A1830D6D4E6FA9CFAAA75D68C8E8C53C386DA1843A678`

## Runtime Data

### Usage (stderr):
```cmhg
unknown option -- h
usage: ssh-keyscan [-46cDHv] [-f file] [-p port] [-T timeout] [-t type]
		   [host | addrlist namelist]

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\OpenSSH\ssh-keyscan.exe |


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
* VirusTotal Link: https://www.virustotal.com/gui/file/2ba00213f3e384cdc396dccd5a58f17a9dada923ae8db5104ecf4af972fe8ffe/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-166F0CE9CC00A55569794AF53E847039.md) | 32
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-34F9BFD01311EA9D88ACE80CA7CDF890.md) | 32
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-add.exe](ssh-add.exe-2A1DED146AD791D52F68B6F165BB11CC.md) | 35
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\ssh-agent.exe](ssh-agent.exe-AD232E2F6698E35DC4AF193CFCE7F331.md) | 32
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-85C9EEED657E96D6F44A564586685C99.md) | 32
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 30
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-66969AA56E77953E596470C73A9004E0.md) | 36
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 35
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-E7F2BA307D3C923709744745C25C9CB5.md) | 25
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 36

## Possible Misuse

*The following table contains possible examples of `ssh-keyscan.exe` being misused. While `ssh-keyscan.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`c4070d1ad35070c8df2914bf56ad554e18af4961` \|ssh-keyscan \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH keyscan (ssh-keyscan)"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


