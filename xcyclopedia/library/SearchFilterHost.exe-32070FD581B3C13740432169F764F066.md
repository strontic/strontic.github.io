
# SearchFilterHost.exe 

* File Path: `C:\Windows\system32\SearchFilterHost.exe`
* Description: Microsoft Windows Search Filter Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `32070FD581B3C13740432169F764F066`
SHA1 | `0721C333FEDD293255B3324C64E5354AF3AE4A20`
SHA256 | `AC1295DEBAF51D3562705376EEF6E8AC74DCD93DF53D30F5ECEACACBBC45C5F2`
SHA384 | `17F51E5F165B583A3A51749E24FE348B9AA95C40D3FBBC3EB6A139E659D3F2CBC914FB03CAB3D177C0ACDAD6AD232F16`
SHA512 | `DFD426FE196102C67903E4C63A8A33F378B7EA25FADCDFC18FC81719E109FBBDD901E1C09CC54C65F164F0FD5E172622FF519614A45BD9D9119A9DAB0A087EF9`
SSDEEP | `6144:G2YkMO2AEXE6h1BmnCUKGswLrkR10efUK:LYkMPAEVLnUKJwLQztf`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
[C:\WINDOWS\system32\SearchFilterHost.exe](SearchFilterHost.exe-2296B4F9F71EFB1FCC195C85B8EA3ED9.md) | 44
[C:\WINDOWS\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-2EF0A0531B2566153D9A3DF4160F650B.md) | 35
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-9350D231BEDC8A957F8CAA50E83BC446.md) | 33
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-98CAC0FEB32500C7CC15B6FE83F6068D.md) | 49
[C:\WINDOWS\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-BDCF47F408DA7D42D97763D27405B773.md) | 43
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-3F2C5E10BCC7A67751F042FE148C1B0F.md) | 35
[C:\WINDOWS\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E318AF6C41ABF3FB889EC89164A36A37.md) | 36

## Possible Misuse

*The following table contains possible examples of `SearchFilterHost.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `        Image\|endswith: '\SearchFilterHost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


