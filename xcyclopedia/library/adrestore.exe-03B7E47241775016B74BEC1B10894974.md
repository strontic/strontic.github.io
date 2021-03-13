---
title: adrestore.exe | 
excerpt: What is adrestore.exe?
---

# adrestore.exe 

* File Path: `C:\SysinternalsSuite\adrestore.exe`

## Hashes

Type | Hash
-- | --
MD5 | `03B7E47241775016B74BEC1B10894974`
SHA1 | `6976B451B6FEDE627CF982A7556D4EA49BB9A02C`
SHA256 | `D6F2383412056BBFE4C0B2EAD055782008AD4BB5F758C0C582E91C9624F9B5EC`
SHA384 | `E86E65339E6BA5CD4EA49E1A589E26A0F20C69BD4077D12516C379E363CEC4D11C8BF5254BEC0E084DA62C51AD776033`
SHA512 | `23DB768DDB7A462E347CB0027FE13E24EE620A6B7CC9E794A69A11EB78922659A7A111C63B4219ECDEA72B9885BAE93717599BD06608C9DEF901E10D95E11D12`
SSDEEP | `1536:5RQOA+P4r3mbAWwUVYxtEdkmVnTA6uvnHaei:/NPaqAWwiYxtQnp`
IMP | `66A38E1024D19E37020AE76F47816FA4`
PESHA1 | `96FC3760783B25EA8E28125D3AD0E5352F505FC9`
PE256 | `4B7210C19AA9660284BDEE8A146F1C18BFDC7DC40974ACCCBC10281A3D2FA577`

## Runtime Data

### Usage (stdout):
```cmhg

AdRestore v1.1
by Mark Russinovich
Sysinternals - www.sysinternals.com

Usage: AdRestore [-r] [searchfilter]

   -r       Prompt to restore deleted objects found.

This command enumerates all objects with the string "comp" in the name.

     adrestore comp

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(---)   \Device\Mup\37AACD8D-548A-4\*\MAILSLOT\NET\NETLOGON | File
(R-D)   C:\Windows\SysWOW64\activeds.tlb | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.488_none_89e6152f0b32762e | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\adrestore.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `61469ECB000400000065`
* Thumbprint: `564E01066387F26C912010D06BD78D3CF1E845AB`
* Issuer: CN=Microsoft Code Signing PCA, OU=Copyright (c) 2000 Microsoft Corp., O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/d6f2383412056bbfe4c0b2ead055782008ad4bb5f758c0c582e91c9624f9b5ec/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\AccessEnum.exe](AccessEnum.exe-F4CD850FDAB64FFBBCC249374BA17F5B.md) | 47
[C:\SysinternalsSuite\Cacheset.exe](Cacheset.exe-99936EC7843663C081BA7AD33AAB9D17.md) | 49
[C:\SysinternalsSuite\ctrl2cap.exe](ctrl2cap.exe-C100EA4F0C45C916C795860FD1EB74CC.md) | 46
[C:\SysinternalsSuite\Diskmon.exe](Diskmon.exe-0942C078FE8941282372BB6B5D73E2C8.md) | 24
[C:\SysinternalsSuite\efsdump.exe](efsdump.exe-4CEF8412C762F4840349E5622A05A307.md) | 46
[C:\SysinternalsSuite\ldmdump.exe](ldmdump.exe-202119E519DD179DE64AFD195F0DDA42.md) | 50
[C:\SysinternalsSuite\pagedfrg.exe](pagedfrg.exe-24898BA51CBAAD01A046541CC0A8D26F.md) | 33

## Possible Misuse

*The following table contains possible examples of `adrestore.exe` being misused. While `adrestore.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y \\live.sysinternals.com\tools\adrestore.exe /d \\otherwebdavserver\webdav\adrestore.exe /o`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


