---
title: tail.exe | 
---

# tail.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\tail.exe`

## Hashes

Type | Hash
-- | --
MD5 | `4FABD477F0F90991F827974BC3270B04`
SHA1 | `6928C3FBD7F504182678326102337755966E469C`
SHA256 | `89C72CF59CE357CEFC71128820831ECDEE75FF9DB00D56709C50510385888855`
SHA384 | `BC9121500FAAC970A7C93BC55311CEBE21712D4757A27305192C880B72E48ACB87F41F8CEDB35D71211B28F2D939F6D9`
SHA512 | `CF5A5D0BE5CEEAA9D3DBC364EB646CCA33E290DDF5B7D93D02AE86FA8F73D2E107DFC6876B8D22FC1975E21CCAF9592A99C10281B3145545541CAD33CEC5EE9E`
SSDEEP | `1536:JWo6Y6hXWG0uYPEcgWIQMCEuvSaWUVdo5ZxUfd:JZ6YMWG/yCCEuvoUVdo5ZA`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/tail [OPTION]... [FILE]...
Print the last 10 lines of each FILE to standard output.
With more than one FILE, precede each with a header giving the file name.

With no FILE, or when FILE is -, read standard input.

Mandatory arguments to long options are mandatory for short options too.
  -c, --bytes=[+]NUM       output the last NUM bytes; or use -c +NUM to
                             output starting with byte NUM of each file
  -f, --follow[={name|descriptor}]
                           output appended data as the file grows;
                             an absent option argument means 'descriptor'
  -F                       same as --follow=name --retry
  -n, --lines=[+]NUM       output the last NUM lines, instead of the last 10;
                             or use -n +NUM to output starting with line NUM
      --max-unchanged-stats=N
                           with --follow=name, reopen a FILE which has not
                             changed size after N (default 5) iterations
                             to see if it has been unlinked or renamed
                             (this is the usual case of rotated log files);
                             with inotify, this option is rarely useful
      --pid=PID            with -f, terminate after process ID, PID dies
  -q, --quiet, --silent    never output headers giving file names
      --retry              keep trying to open a file if it is inaccessible
  -s, --sleep-interval=N   with -f, sleep for approximately N seconds
                             (default 1.0) between iterations;
                             with inotify and --pid=P, check process P at
                             least once every N seconds
  -v, --verbose            always output headers giving file names
  -z, --zero-terminated    line delimiter is NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

NUM may have a multiplier suffix:
b 512, kB 1000, K 1024, MB 1000*1000, M 1024*1024,
GB 1000*1000*1000, G 1024*1024*1024, and so on for T, P, E, Z, Y.
Binary prefixes can be used, too: KiB=K, MiB=M, and so on.

With --follow (-f), tail defaults to following the file descriptor, which
means that even if a tail'ed file is renamed, tail will continue to track
its end.  This default behavior is not desirable when you really want to
track the actual name of the file, not the file descriptor (e.g., log
rotation).  Use --follow=name in that case.  That causes tail to track the
named file in a way that accommodates renaming, removal and creation.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/tail>
or available locally via: info '(coreutils) tail invocation'

```

### Usage (stderr):
```cmhg
tail: unknown option -- h
Try '/usr/bin/tail --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\tail.exe |
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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\tail.exe](tail.exe-4FABD477F0F90991F827974BC3270B04.md) | 100




MIT License. Copyright (c) 2020 Strontic.


