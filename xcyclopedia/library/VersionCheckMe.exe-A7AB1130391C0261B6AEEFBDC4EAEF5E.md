---
title: VersionCheckMe.exe | VersionCheckMe Application
excerpt: What is VersionCheckMe.exe?
---

# VersionCheckMe.exe 

* File Path: `C:\program files (x86)\Common Files\Apple\Apple Application Support\VersionCheckMe.exe`
* Description: VersionCheckMe Application

## Hashes

Type | Hash
-- | --
MD5 | `A7AB1130391C0261B6AEEFBDC4EAEF5E`
SHA1 | `9393777E1C8C13F15CA9090BC2F7795ADC80A12C`
SHA256 | `0636F898482DEA1BD6AC86769A2D822B3E06A7B4B8235DEE452E06DBCC0BE7CD`
SHA384 | `EBA23CCF4C2B31DF6B6AA1F52D7E31D96EEE9756317358717F146543CE8E45DD25F122AB2C3D26F30836A766CC12A78F`
SHA512 | `44FE13721E1E2C09E78FA1BB80A656FA649E411BF52D4A5ABE8AE03952A25F967253D670A2AF852892C3F6B5517AF24B2EEADE4225347CE7321D151B817CDE4A`
SSDEEP | `384:QnKqbEEBmpJVD8nIs7uc1T471yMnYPLgqAzu8JN77hhTsd:QKXEBmpvD8nz7ucZ471tpqAzp3hxK`

## Runtime Data

### Usage (stdout):
```cmhg
Test: FAILED {MinVersion, version < bl version}
Test: PASSED {MinVersion, version == bl version}
Test: PASSED {Between MaxVersion and MinVersion}
Test: PASSED {MaxVersion, version == bl version}
Test: FAILED {MaxVersion, version > bl version}
Test: FAILED {Windows Version, Module Name Supplied, 1.0.0.1 < 1.2.0.0}
Test: FAILED {Windows Version, Nothing Supplied, 1.0.0.1 < 1.2.0.0}
Test: FAILED { Full path specified }
Test: FAILED {Failed to find other method test key/value set}

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Common Files\Apple\Apple Application Support\VersionCheckMe.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `4EF16586A2FF12D69C556EC4C91BAEE1`
* Thumbprint: `634A0D892E72161714861C178015AFE9C1832E14`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Apple Inc., O=Apple Inc., L=Cupertino, S=California, C=US

## File Metadata

* Original Filename: VersionCheckMe.exe
* Product Name: VersionCheckMe Application
* Company Name: Apple Inc.
* File Version: 22.0.0.125
* Product Version: 1.0.0.1
* Language: English (United States)
* Legal Copyright:  2020 Apple Inc. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Common Files\Apple\Apple Application Support\distnoted.exe](distnoted.exe-899CED92AB6A8B024568572CB2748126.md) | 36
[C:\program files (x86)\Common Files\Apple\Apple Application Support\plutil.exe](plutil.exe-7B40123D5C077F3BE9511A7507990A9C.md) | 38
[C:\Program Files (x86)\Common Files\Apple\Mobile Device Support\distnoted.exe](distnoted.exe-899CED92AB6A8B024568572CB2748126.md) | 36
[C:\program files\Common Files\Apple\Apple Application Support\VersionCheckMe.exe](VersionCheckMe.exe-220A1A86EC8E4B9159C075BC8B55B998.md) | 43
[C:\Program Files\Wireshark\dftest.exe](dftest.exe-049B4FA2F5ABEED3D65D516CE3BDC6FE.md) | 29
[C:\Program Files\Wireshark\mmdbresolve.exe](mmdbresolve.exe-71B469FE7134B36132D3AFE8164B32D7.md) | 32




MIT License. Copyright (c) 2020-2021 Strontic.


