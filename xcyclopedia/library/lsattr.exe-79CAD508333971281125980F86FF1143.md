---
title: lsattr.exe | 
excerpt: What is lsattr.exe?
---

# lsattr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\lsattr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `79CAD508333971281125980F86FF1143`
SHA1 | `758BD72983B63D64222D7AA38EC3D00E25AD5331`
SHA256 | `CBFECF9F28B9E9AE97B48614F710E4C145B4DCF6ABF2C0C0254E9825773CDE93`
SHA384 | `FD87746A9C5534CB9D934661F7E193E3A343FB6BCEB0C5C0F062A2D3187E08E2B5DB7DDB4A28875B36601EC604FCC77B`
SHA512 | `CED2BA19D0F35D65356AFC6BC9A22CE3B529A15CA85563C13A78DD69F7A73DA93F3AE7A6687BAD341900501502BE8C8F3A6E443E705C8773F95FAB8E3D8BD0EB`
SSDEEP | `3072:CrUsgpvCBTWGorrZwxDSGPadReQRI1IhQtToaiIxWGfJ6K:kUHpvC1WGdDSGPOIWhQtnirGd`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: lsattr [-RVadhln] [file]...

List file attributes

  -R, --recursive     recursively list attributes of directories and their 
                      contents
  -V, --version       display the program version
  -a, --all           list all files in directories, including files that
                      start with '.'
  -d, --directory     list directories like other files, rather than listing
                      their contents.
  -l, --long          print options using long names instead of single
                      character abbreviations
  -n, --no-headers    don't print directory headers when recursing
  -h, --help          this help text

Supported attributes:

  'r', 'Readonly':      file is read-only, directory is system-marked
  'h', 'Hidden':        file or directory is hidden
  's', 'System':        file or directory that the operating system uses
  'a', 'Archive':       file or directory has the archive marker set
  't', 'Temporary':     file is being used for temporary storage
  'S', 'Sparse':        file is sparse
  'r', 'Reparse':       file or directory that has a reparse point
  'c', 'Compressed':    file or directory is compressed
  'o', 'Offline':       the data of a file is moved to offline storage
  'n', 'Notindexed':    file or directory is not to be indexed by the
                        content indexing service
  'e', 'Encrypted':     file is encrypted
  'C', 'Casesensitive': directory is handled case sensitive
                        (Windows 10 1803 or later, local NTFS only,
                         WSL must be installed)

```

### Usage (stderr):
```cmhg
lsattr: No such file or directory while trying to stat /h

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\lsattr.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\chattr.exe](chattr.exe-EA2E956C8B2D11F9337CBC99AFB7D91F.md) | 55
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\lsattr.exe](lsattr.exe-79CAD508333971281125980F86FF1143.md) | 100

## Possible Misuse

*The following table contains possible examples of `lsattr.exe` being misused. While `lsattr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "displaysecinfo(\"List of Attributes\",myshellexec(\"lsattr -a\"));" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


