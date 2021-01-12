---
title: bcp.exe | BCP - SQL bulk copy tool
excerpt: What is bcp.exe?
---

# bcp.exe 

* File Path: `C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn\bcp.exe`
* Description: BCP - SQL bulk copy tool
* Comments: SQL


## Hashes

Type | Hash
-- | --
MD5 | `7AA08BDEF40632D26C957C0D02441C6A`
SHA1 | `1173D94349566014D7443E30A6A74E6C0C7BFB9C`
SHA256 | `06DF5C21A32B41279361F1E8E2809894DEC403B3168E11959EFEED734605AFDD`
SHA384 | `0CBA60361AFD1FF5FF252C1CEF203E31E9990E51BE90B93F126ED7442565FEE336CAE2E942DB7785645B78FF7090A2A9`
SHA512 | `405BC3C11279578BD4B4EAE8BAAE1054EB0180B2C8D1D95D88BD5557C95365262B8EFA9287CBA0998F2B5711482100D3299BEBC2C067EA1DE6EDDB0FBD66EC2F`
SSDEEP | `3072:91BLMuh57yd6bGXC6joQ5XBjJDpYzo2eI0eyiEe:aG2joeXBjJDp33e`
IMP | `3FA895B748E2AF8D3260E15F88A1C167`
PESHA1 | `E3FD82A7A59CE77FE11F64D5625523E8DF2D89AD`
PE256 | `DAFEF88663942F39863016AA39896ACEEF8DE7563283FBE22E128FDC51784BB4`

## Runtime Data

### Usage (stdout):
```cmhg
usage: C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn\bcp.exe {dbtable | query} {in | out | queryout | format} datafile
  [-m maxerrors]            [-f formatfile]          [-e errfile]
  [-F firstrow]             [-L lastrow]             [-b batchsize]
  [-n native type]          [-c character type]      [-w wide character type]
  [-N keep non-text native] [-V file format version] [-q quoted identifier]
  [-C code page specifier]  [-t field terminator]    [-r row terminator]
  [-i inputfile]            [-o outfile]             [-a packetsize]
  [-S server name]          [-U username]            [-P password]
  [-T trusted connection]   [-v version]             [-R regional enable]
  [-k keep null values]     [-E keep identity values][-G Azure Active Directory Authentication]
  [-h "load hints"]         [-x generate xml format file]
  [-d database name]        [-K application intent]  [-l login timeout]

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn\bcp.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001E47CFC029560FF84FB0002000001E4`
* Thumbprint: `E942D27A35DCBBE072872AD9E9E0AC4C948A7864`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BCP.exe
* Product Name: Microsoft SQL Server
* Company Name: Microsoft Corporation
* File Version: 2019.0150.2000.05 ((SQLServer).190924-2033)
* Product Version: 15.0.2000.5
* Language: English (United States)
* Legal Copyright: Microsoft. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/06df5c21a32b41279361f1e8e2809894dec403b3168e11959efeed734605afdd/detection


## Possible Misuse

*The following table contains possible examples of `bcp.exe` being misused. While `bcp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s9 = "bcp.exe <:schema:>.<:table:> out \"<:file:>\" -n -S <:server:> -U <:user:> -P <:" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


