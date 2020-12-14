---
title: ru.exe | Registry size usage reporter
excerpt: What is ru.exe?
---

# ru.exe 

* File Path: `C:\SysinternalsSuite\ru.exe`
* Description: Registry size usage reporter

## Hashes

Type | Hash
-- | --
MD5 | `4F8F031E1D712E3DF9D4E4A4DFDFCF03`
SHA1 | `75BA8F746B10089F549ABD30A87B317403E1A0B9`
SHA256 | `85AA361EF398B441D0B95E46AD354EC734A2CF2B482ACF163807641D596A94AE`
SHA384 | `B4AFE02A9B38A24329C2D1C919681CAE8D9682F398CE6937D32184CDB0D1EB5BE0FD5C43EE5EBAF70443BD7AD16716B4`
SHA512 | `A213C7CD8264201AD14B5E91C80A13C320545AC9266D3BF2E2D911773CC609742CC492DCA3706BC3658EA76984DA13307A477DA4A409E18CC51BF836358FF6D2`
SSDEEP | `6144:dzf1Oj4dGhEfLbEf92CdrJRvDddfUlf7L7kgMAPeUYF085:dROyGhEf3EVHdjL2bnby5`
IMP | `754456476D1F9F89213E05AA2F4A558A`
PESHA1 | `F84FDE2A8A32B1C7A89BE30993B9D92F0137C2DC`
PE256 | `474F0B200CC1A5AF98DB1DDA08B21FDB507DCCC7A43866873E36E8CFBDECBCE2`

## Runtime Data

### Usage (stdout):
```cmhg

Ru v1.2 - Registry size usage reporter
Copyright (C) 2013-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: ru [-c[t]] [-l <levels> | -n | -v] [-q] <absolute path>
usage: ru [-c[t]] [-l <levels> | -n | -v] [-q] -h <hive file> [relative path]
   -c     Print output as CSV. Specify -ct for tab delimiting.
          Specify -nobanner to avoid banner being output to CSV
   -h     Load the specified hive file, perform the size calculation, then
          unload it and compress it.
   -l     Specify subkey depth of information (default is one level).
   -n     Do not recurse.
   -v     Show size of all subkeys.
   -nobanner
          Do not display the startup banner and copyright message.

CSV output is formatted as:
Path,CurrentValueCount,CurrentValueSize,ValueCount,KeyCount,KeySize,WriteTime


```

### Usage (stderr):
```cmhg
The Registry path specified is not valid: c:\temp\strontic-xcyclopedia\notepad.exe


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\ru.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Regsize1
* Product Name: Sysinternals Ru
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.2
* Product Version: 1.2
* Language: English (United States)
* Legal Copyright: Copyright (C) 2013-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/85aa361ef398b441d0b95e46ad354ec734a2cf2b482acf163807641d596a94ae/detection/


## Possible Misuse

*The following table contains possible examples of `ru.exe` being misused. While `ru.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt15.yar) | $s6 = "runexe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


