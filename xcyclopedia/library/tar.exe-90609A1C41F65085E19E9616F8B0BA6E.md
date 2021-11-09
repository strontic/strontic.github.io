---
title: tar.exe | bsdtar archive tool
excerpt: What is tar.exe?
---

# tar.exe 

* File Path: `C:\WINDOWS\SysWOW64\tar.exe`
* Description: bsdtar archive tool

## Hashes

Type | Hash
-- | --
MD5 | `90609A1C41F65085E19E9616F8B0BA6E`
SHA1 | `E3DBFD1ADF3035E9126D9275E9FCE4B3917BBC37`
SHA256 | `894EC954E51362D38DAE5F359363B3C54540B2A57EF508B8F0317572E6C52396`
SHA384 | `A00C61D1042EFCDAE59D33DF8D4EF033665EF644098343656842905209B76428F0E09C7AE0728676C6B60E290037B210`
SHA512 | `05AA029D612B6A2D8E1D92188679CEB35A7A16A36527690C02B5FCECA827031BA031E0BCF1C80AA52BCEA2D6769CBF2FA627473DDE0502730A8E6A41BB94A372`
SSDEEP | `768:MRJTyHSDzDtS3Xe3d/xEuM/5GP3AmWmTPAxKfMe0eQqOVBIHtntRZOjI:QJy+LEZQPmmTm3e0e1OVB+tntjOjI`
IMP | `C79B7278C6B0D7DD86EFF45215E72276`
PESHA1 | `12778C5945D105D2C61F35C87E086C8CC1282911`
PE256 | `478727565CE6F502FD1DA5260D4C80F23D84879B1F7EAA288D45BA81DEC7B9CD`

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
bsdtar 3.4.3 - libarchive 3.4.3 zlib/1.2.5.f-ipp bz2lib/1.0.6 

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\tar.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bsdtar
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 3.4.3 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright: Copyright (c) libarchive authors
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/894ec954e51362d38dae5f359363b3c54540b2a57ef508b8f0317572e6c52396/detection





MIT License. Copyright (c) 2020-2021 Strontic.


