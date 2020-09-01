---
title: mktemp.exe | 
---

# mktemp.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\mktemp.exe`

## Hashes

Type | Hash
-- | --
MD5 | `10500D0547202DF4C5B30F2D16372E5F`
SHA1 | `F74726022EE25F1099A1D68DAA65FA7E5A26AE90`
SHA256 | `8887EA42F2CA1939C182F1BFF4FF14222E8FA5882AB74BF9A5381A3FB9DDB813`
SHA384 | `8422434AAAB755048FB46D8AF718221377AC0B7F0B2EDE8F788E97CC4DBAE0109365E447DE266A6435321796D886A7E1`
SHA512 | `199A293BCB39A0487A8EC9489A6135C4EB5E0F611F8D0D3895A933236F4EDDD81FFBAC14869A13E980CDD333A890E4A4B21D968FEE563AEE3BB84415AA376804`
SSDEEP | `768:Pkx6KsQTpMpEArYIEAovO0cyoGeib9Niqbo7dXhWoXIFUSDG9Uf2h:PkxQQTpMMw8cauhW+IFUPUf`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: /usr/bin/mktemp [OPTION]... [TEMPLATE]
Create a temporary file or directory, safely, and print its name.
TEMPLATE must contain at least 3 consecutive 'X's in last component.
If TEMPLATE is not specified, use tmp.XXXXXXXXXX, and --tmpdir is implied.
Files are created u+rw, and directories u+rwx, minus umask restrictions.

  -d, --directory     create a directory, not a file
  -u, --dry-run       do not create anything; merely print a name (unsafe)
  -q, --quiet         suppress diagnostics about file/dir-creation failure
      --suffix=SUFF   append SUFF to TEMPLATE; SUFF must not contain a slash.
                        This option is implied if TEMPLATE does not end in X
  -p DIR, --tmpdir[=DIR]  interpret TEMPLATE relative to DIR; if DIR is not
                        specified, use $TMPDIR if set, else /tmp.  With
                        this option, TEMPLATE must not be an absolute name;
                        unlike with -t, TEMPLATE may contain slashes, but
                        mktemp creates only the final component
  -t                  interpret TEMPLATE as a single file name component,
                        relative to a directory: $TMPDIR, if set; else the
                        directory specified via -p; else /tmp [deprecated]
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/mktemp>
or available locally via: info '(coreutils) mktemp invocation'

```

### Usage (stderr):
```Batchfile
mktemp: unknown option -- h
Try '/usr/bin/mktemp --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\mktemp.exe |
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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\mktemp.exe](mktemp.exe-10500D0547202DF4C5B30F2D16372E5F.md) | 100




MIT License. Copyright (c) 2020 Strontic.


