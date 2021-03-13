---
title: Dism.exe | Dism Image Servicing Utility
excerpt: What is Dism.exe?
---

# Dism.exe 

* File Path: `C:\windows\SysWOW64\Dism.exe`
* Description: Dism Image Servicing Utility

## Hashes

Type | Hash
-- | --
MD5 | `6C7FF8FC34A59342CEBDBFED54EC0C71`
SHA1 | `5794FACD4FB934E6334FEE5492F3D9C48A753E2B`
SHA256 | `4434D1DDB000B8014EE7A84D8DF27FFB53DBC2BEC2E9D9A06631A1D902F0D929`
SHA384 | `346672A7055D31EA5DA4CFBD9062C4B2ECAB19231C7A35939A343876E9C4F3AF6B494089DBCAE6511F9F7326B9A25CBF`
SHA512 | `306782DB3E32D2BD1B33D85C72323DB1B895900D2FA805B984CA17DBABD31881D6B5341ECC0728AF9D941797BD54BD573DB39083DAA2052C82FC88262C14E2D1`
SSDEEP | `3072:075RF52kMXQBVhGr7+nSAZiKMFskFai2UhMWvfhocaManrrE4Z:wXF52BXQpVSA0LOkFwafho5rrE4Z`

## Signature

* Status: The file C:\windows\SysWOW64\Dism.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: DISM.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17031 (winblue_gdr.140221-1952)
* Product Version: 6.3.9600.17031
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `Dism.exe` being misused. While `Dism.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\Dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


