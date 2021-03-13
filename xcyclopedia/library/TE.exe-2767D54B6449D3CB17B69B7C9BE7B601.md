---
title: TE.exe | Test Authoring and Execution Framework [v10.43k]
excerpt: What is TE.exe?
---

# TE.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\TE.exe`
* Description: Test Authoring and Execution Framework [v10.43k]

## Hashes

Type | Hash
-- | --
MD5 | `2767D54B6449D3CB17B69B7C9BE7B601`
SHA1 | `300DB2586498E561B5E040F3DFF35E7132D64638`
SHA256 | `538981E1D87081F1E6F2E1D6296AF604072DBFC65638540326DC537BA5F6263C`
SHA384 | `A6100DF47FA1FDA592A7B73DD5137988090F7D1A084439F97B6386AA675CFAD2733FD50C72DAEDDBE3160D178150DF3B`
SHA512 | `9E59F0EE8F3797432F8814D321BB8ECCB293DEDD5761807B8B2EA061728A2F9EDF75E6D14F7D9FEB8720A5C8B51E44606F3444234BE0FE29F5BB0EAD5EBA8167`
SSDEEP | `6144:lptbp+xB8m+6rvUs/wp/MSl+neMWmiPOuoareRk5l/:lptbp+xB8J6IXhMSl7MWLOLa5V`
IMP | `8268621D19CF595B5F33A4C3F8E3E0DD`
PESHA1 | `4CBC29BB5B74F0ADBFF45DC5DA5BCAC0CAC9C282`
PE256 | `6B959BC160D32B4B218C2918630A6C0EED55EE558E2BD470BF56897E388C614D`

## Runtime Data

### Usage (stdout):
```cmhg
Test Authoring and Execution Framework v10.43k for x64

[TE.exe] Executes one or more test binaries

Usage: TE <test_binaries> [/select:<query>] [/inproc] 
	  [/enablewttlogging] [/list] [/listProperties] 
	  [/!]

	test_binaries     Specify one or more test files to execute
			  (separated by spaces). Wild card selection is
			  supported.

	/select:<query>   The selection criteria to be used when selecting
			  tests from each test binary.  Selection criteria
			  is composed of one or more of the following:

			  @[property name] = [value as string]
			  @[property name] >= [value as float or integer]
			  @[property name] > [value as float or integer]
			  @[property name] <= [value as float or integer]
			  @[property name] < [value as float or integer]

			  - Property values as strings must be within single
			  quotes.

			  - You can specify a composite selection criteria
			  using "and", "or" and "not" (case insensitive).

			  - Property string values support wildcard searches
			  via "*" and "?" characters.

			  - For float and integer values, the "*" character
			  may also be used as 'exists', but may not be
			  used for partial matching.

			  For example: /select:"@Priority=*" is valid, but
			  /select:"@Priority=4*" is not.

			  - For detailed /select examples, run TE /!

	/name:<testname>  Alternative to "/select:@Name='<testname>'". The
			  <testname> can still contain wildcard characters, 
			  i.e. "*" and "?", but should not be contained 
			  within single quotes. 

	/inproc		  Execute all tests within the TE.exe process itself
			  rather than within TE.ProcessHost.exe.

	/enablewttlogging Enables WTT logging; Wttlog.dll must be available
			  in your path.

	/list		  Lists the names of all the test_binaries and the
			  classes and methods in them. If selection criteria
			  is specified, lists only the names of those which 
			  meet the criteria.

	/listproperties	  Lists the names and properties of all the 
			  test_binaries and the classes and methods in them
			  along with Setup and Teardown function names, if 
			  available. If selection criteria is specified, 
			  lists only the names of those which meet the 
			  criteria.

	/!		  Display detailed help and additional options in a 
			  browser window.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\TE.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TE.exe
* Product Name: Test Authoring and Execution Framework
* Company Name: Microsoft Corporation
* File Version: 10.43.1909.04003
* Product Version: 10.43.190904003-develop
* Language: English (United States)
* Legal Copyright: Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/538981e1d87081f1e6f2e1d6296af604072dbfc65638540326dc537ba5f6263c/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\MinTe\TE.exe](TE.exe-2767D54B6449D3CB17B69B7C9BE7B601.md) | 100
[C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\x64\MinTe\TE.exe](TE.exe-2767D54B6449D3CB17B69B7C9BE7B601.md) | 100
[C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\x64\TE.exe](TE.exe-2767D54B6449D3CB17B69B7C9BE7B601.md) | 100

## Possible Misuse

*The following table contains possible examples of `TE.exe` being misused. While `TE.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Te.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Te.yml) | `Name: te.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Te.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Te.yml) | `- Command: te.exe bypass.wsc`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


