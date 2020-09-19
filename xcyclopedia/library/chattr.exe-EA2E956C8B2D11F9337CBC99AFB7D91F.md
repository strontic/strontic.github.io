---
title: chattr.exe | 
---

# chattr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\chattr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `EA2E956C8B2D11F9337CBC99AFB7D91F`
SHA1 | `FF6B87036556C804925458EE4698D3EF15013871`
SHA256 | `FDFFA6014B48A4CD9CEEAB7B9ABA6897C971473968D6460AFE29C01AF894A505`
SHA384 | `72ADAD219C41EB78D89C267474E8C242AAFFEC7DC368C919485A58C7F0912EEBFE47EC2A80AEA5FC7D5BD6A0D7BC6DB6`
SHA512 | `BBF342F57244198CACA5AA0309B546DC3AE18A35B5C7FC5D70C6F7785F7714BB754CD8AC158FE12ED1F9581280D412E0A145E11AF8005555CB8C67F673BA0EF8`
SSDEEP | `3072:QdOgpvCBwBWGbn1WymDSGPadReQRI2XhQtTA9iHCcGfEUupe:QdZpvCBoWGuDSGPOIOhQt0iFGs5pe`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: chattr [-RVfhv] [+-=mode]... [file]...

Change file attributes

  -R, --recursive     recursively list attributes of directories and their 
                      contents
  -V, --verbose       Be verbose during operation
  -f, --force         suppress error messages
  -h, --help          this help text
  -v, --version       display the program version

The format of 'mode' is {+-=}[acCehnrsSt]

The  operator '+' causes the selected attributes to be added to the
existing attributes of the files; '-' causes them to be removed; and
'=' causes them to be the only attributes that the files have.

Supported attributes:

  'r', 'Readonly':     file is read-only
  'h', 'Hidden':        file or directory is hidden
  's', 'System':        file or directory that the operating system uses
  'a', 'Archive':       file or directory has the archive marker set
  't', 'Temporary':     file is being used for temporary storage
  'S', 'Sparse':        file is sparse
  'c', 'Compressed':    file or directory is compressed
  'n', 'Notindexed':    file or directory is not to be indexed by the
                        content indexing service
  'e', 'Encrypted':     file is encrypted
  'C', 'Casesensitive': directory is handled case sensitive
                        (Windows 10 1803 or later, local NTFS only,
                         WSL must be installed)

```

### Usage (stderr):
```cmhg
chattr: Must use at least one of =, + or -

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\chattr.exe |
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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\chattr.exe](chattr.exe-EA2E956C8B2D11F9337CBC99AFB7D91F.md) | 100
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\lsattr.exe](lsattr.exe-79CAD508333971281125980F86FF1143.md) | 55

## Possible Misuse

*The following table contains possible examples of `chattr.exe` being misused. While `chattr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_chattr_immutable_removal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_chattr_immutable_removal.yml) | `        a0\|contains: 'chattr'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #9: chattr - Remove immutable file attribute [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) |   - Atomic Test #9: chattr - Remove immutable file attribute [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) |   - Atomic Test #9: chattr - Remove immutable file attribute [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | - [Atomic Test #9 - chattr - Remove immutable file attribute](#atomic-test-9---chattr---remove-immutable-file-attribute) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | ## Atomic Test #9 - chattr - Remove immutable file attribute | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | Remove's a file's `immutable` attribute using `chattr`. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | chattr -i #{file_to_modify} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


