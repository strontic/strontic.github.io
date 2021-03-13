---
title: tar.exe | bsdtar archive tool
excerpt: What is tar.exe?
---

# tar.exe 

* File Path: `C:\Windows\SysWOW64\tar.exe`
* Description: bsdtar archive tool

## Hashes

Type | Hash
-- | --
MD5 | `4B26D4CD5CD5F7B074E31793979F17C5`
SHA1 | `C627A94EFEFF9C105B0166A66AED6D7BD7D76047`
SHA256 | `2319A2F1313A4BF4CF5E009B7CD8A6E97B4C5B63B679F5BD4FEFA29CD7B3F319`
SHA384 | `74AF6149C1EC000030CB1384470FBD8DFB61FE1B9516C213420D60D875E67C6DE2B1410E7747808131C634D945A5DEA5`
SHA512 | `058CBCDACCA4B1E8927072D844DEFBD34370E687A7EAC5C0A8938CD13772102A572844182D03E626300F62C9BCA75B6F7EC219FDEDCDD97E3549EFFB9B8A0987`
SSDEEP | `768:Gkjt3SD9dqPu7MhObt7skjusX52HmbUV2S3p5OBKajbc:GkMZdqPN2tdtoGoVvpoBKaj`
IMP | `A529BDD6841E94B24C9B370AD975BD9B`
PESHA1 | `5640D50EEE50C9AAE5B894C493A8A0E8DE8FC889`
PE256 | `190F975C47B4BEFB3A820C2489C06DD30E48507EC3B13345AD537FE4D512B62E`

## Runtime Data

### Usage (stdout):
```cmhg
tar.exe(bsdtar): manipulate archive files
First option must be a mode specifier:
  -c Create  -r Add/Replace  -t List  -u Update  -x Extract
Common Options:
  -b #  Use # 512-byte records per I/O block
  -f <filename>  Location of archive (default \\.\tape0)
  -v    Verbose
  -w    Interactive
Create: tar.exe -c [options] [<file> | <dir> | @<archive> | -C <dir> ]
  <file>, <dir>  add these items to archive
  -z, -j, -J, --lzma  Compress archive with gzip/bzip2/xz/lzma
  --format {ustar|pax|cpio|shar}  Select archive format
  --exclude <pattern>  Skip files that match pattern
  -C <dir>  Change to <dir> before processing remaining files
  @<archive>  Add entries from <archive> to output
List: tar.exe -t [options] [<patterns>]
  <patterns>  If specified, list only entries that match
Extract: tar.exe -x [options] [<patterns>]
  <patterns>  If specified, extract only entries that match
  -k    Keep (don't overwrite) existing files
  -m    Don't restore modification times
  -O    Write entries to stdout, don't restore to disk
  -p    Restore permissions (including ACLs, owner, file flags)
bsdtar 3.3.2 - libarchive 3.3.2 zlib/1.2.5.f-ipp

```

### Usage (stderr):
```cmhg
Usage:
  List:    tar.exe -tf <archive-filename>
  Extract: tar.exe -xf <archive-filename>
  Create:  tar.exe -cf <archive-filename> [filenames...]
  Help:    tar.exe --help

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tar.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bsdtar
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 3.3.2 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright: Copyright (c) libarchive authors
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/2319a2f1313a4bf4cf5e009b7cd8a6e97b4c5b63b679f5bd4fefa29cd7b3f319/detection





MIT License. Copyright (c) 2020-2021 Strontic.


