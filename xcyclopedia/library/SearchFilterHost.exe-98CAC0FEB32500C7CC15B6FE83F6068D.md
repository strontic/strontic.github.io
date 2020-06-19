
# SearchFilterHost.exe 

* File Path: `C:\Windows\SysWOW64\SearchFilterHost.exe`
* Description: Microsoft Windows Search Filter Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `98CAC0FEB32500C7CC15B6FE83F6068D`
SHA1 | `04E8650294E3701EE648AEF55902D41F907FD40E`
SHA256 | `25A3403A8238DB8F6FD4B6DE4113334007707F08440C7D45FBDD58747AC5835B`
SHA384 | `D05A6122D8D3C6A79BAD09E5E0E66E5A0758379C968896B230B66C29147E11CEEAE07D83CE397230F35BE0F161CDE298`
SHA512 | `E5623E7B32899BE42ECF268180FA86C8BB02F8DD1ABE366F4905F7C0292E20899A064D606FD234D70EB00A9736822289825AE41C0EFD23F6AD3B495B10F39AE4`
SSDEEP | `3072:hN9okk47++EOGECRV3tGCVLtg1ihk6kvtfGq0ev3U5WNq4:Vozb+EpECr9GCVLTrkR10efUKq`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchFilterHost.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.14393.3564 (rs1_release.200303-1942)
* Product Version: 7.0.14393.3564
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\SearchFilterHost.exe](SearchFilterHost.exe-2296B4F9F71EFB1FCC195C85B8EA3ED9.md) | 47
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-32070FD581B3C13740432169F764F066.md) | 49
[C:\WINDOWS\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-2EF0A0531B2566153D9A3DF4160F650B.md) | 38
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-9350D231BEDC8A957F8CAA50E83BC446.md) | 38
[C:\WINDOWS\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-BDCF47F408DA7D42D97763D27405B773.md) | 50
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-3F2C5E10BCC7A67751F042FE148C1B0F.md) | 36
[C:\WINDOWS\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E318AF6C41ABF3FB889EC89164A36A37.md) | 35

## Possible Misuse

*The following table contains possible examples of `SearchFilterHost.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `        Image\|endswith: '\SearchFilterHost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


