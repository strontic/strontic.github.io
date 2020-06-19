
# FXSSVC.exe 

* File Path: `C:\WINDOWS\system32\FXSSVC.exe`
* Description: Fax Service
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C6F56E6CF1822CFB9D8F85870453675E`
SHA1 | `672D31EC0BE5C5B89D82479644028FCA6E86DB7E`
SHA256 | `0257954D0C8978C7E163C918A79A5D35AA7626D9D5236BA55FEAA3EB5A44DBEF`
SHA384 | `30E1AB38E3C7447C4DD9F5A9D41EEBACE46C5A0EFE633793A524E449A1E74266621783A989A772787321A7AC951E6001`
SHA512 | `AB22367210F5E5741D92A4C10DE3E38577E34F31A9C1EEC1EF96C17EEAC57EE5EFD52EF4E8B61360A9D7D3992EC6FADF995759F1D476422292949512E7051B81`
SSDEEP | `12288:mJFox052yo03ypNIwZMNGQWk48QVwGe+ip6BvjNOCWkbIlDpV/h:KME/oAONd2NJ48QVwGe+ip6BJ9b+j/h`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FXSSVC.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `FXSSVC.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_fax_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_fax_dll.yml) | `      - fxssvc.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc config Fax binPath= "C:\WINDOWS\system32\fxssvc.exe" >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


