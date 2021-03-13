---
title: PackageInspector.exe | PackageInspector allows creation of a catalog containing all executable files laid down by an installer
excerpt: What is PackageInspector.exe?
---

# PackageInspector.exe 

* File Path: `C:\Windows\system32\PackageInspector.exe`
* Description: PackageInspector allows creation of a catalog containing all executable files laid down by an installer

## Hashes

Type | Hash
-- | --
MD5 | `13ED5BF602AA9FC2DDD673CC756E8463`
SHA1 | `E874CA3952F8CB00EE78E1FE681AA7E6C319F6C6`
SHA256 | `758D9E687DC94A11CEE15E4D415FB619C64E854A6D642E42CB83F4838E4E4C4F`
SHA384 | `F00AD0025917E86938DDDE52B179F731D70C5AE70C9F9B0CEC6AF9A7668096BA44A2830BC0044615D6757B449A922E21`
SHA512 | `C2EF1E8D6A82A940547EDBF2BDF463F22F2A29161A3E631BD5075AD14242772A0006D18A570ACEC4943272952F44846DD44988E45894B308746DCA28126E1D1A`
SSDEEP | `1536:43MYxS09QtinMKpk0iz0+Ni9k+ql+l4cPAWWJIVKRn:YZSGQtoMtK+Ni6j+l42xWJIVKB`
IMP | `78DC365E842607A715DB0094139A0709`
PESHA1 | `4CCEEF2B3CD06F3A8F227DC6889B6B2CE64B2E61`
PE256 | `2ACCA548F2F1346A2B9D0F76A3C05B46669DFA138172F422603DA430519D15C8`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
PackageInspector.exe <command> <DriveLetter or Path> [options]
PackageInspector.exe start <DriveLetter>: [-path <pathToInstaller>]
PackageInspector.exe stop <DriveLetter>: -out cdf|cat|list [-cdfPath <outputCdfPath>] [-name <nameOfCat>] [-resdir <directoryForCat>] [-ph true | false] [-en <encoding type>] [-ca1 <CATATTR1>] [-ca2 <CATATTR2>] [-listPath <pathToOutputList.txt>]
PackageInspector.exe scan <PathToScan> -out cdf|cat|list [-cdfPath <outputCdfPath>] [-name <nameOfCat>] [-resdir <directoryForCat>] [-ph true | false] [-en <encoding type>] [-ca1 <CATATTR1>] [-ca2 <CATATTR2>] [-listPath <pathToOutputList.txt>]

Valid Commands : 
	start   	--	Specifies that a user will start a scan
	stop    	--	Specifies that a scan is complete and one of the supported outputs it to be produced
	scan    	--	Specifies that PackageInspector is to directly scan the given path rather than monitor created files.  Takes same options as stop

Start Options : 
	path    	--	File path to the package being inspected

Stop/Scan Options : 
	out     	--	Specifies what the tool should output from the scan (CAT, CDF, or List)
	cdfPath 	--	Specifies the full path for output of CDF including filename
	name    	--	Specifies the name of the catalog to produce
	resdir  	--	Specifies the result directory of the catalog
	ph      	--	Specifies whether page hashes should be included in the catalog
	en      	--	Specifies the encoding type of the catalog
	ca1     	--	Specifies CATATTR1 in the CDF or CAT
	ca2     	--	Specifies CATATTR2 in the CDF or CAT
	listPath	--	Specifies location to output list of files laid down by installer (for -out list)

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PACKAGEINSPECTOR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 1.00 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/758d9e687dc94a11cee15e4d415fb619c64e854a6d642e42cb83f4838e4e4c4f/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


