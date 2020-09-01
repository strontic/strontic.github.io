---
title: basename.exe | 
---

# basename.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\basename.exe`

## Hashes

Type | Hash
-- | --
MD5 | `06A6BE1F6953444247863D2B556B8710`
SHA1 | `05BE799D8D941A9AE2388BDA9123C44795CD5202`
SHA256 | `87621206A44C50D742CB42EC55C35CFA9D9C1B9B93277E61F60D111E8B19BF38`
SHA384 | `BAF91D4949FF8FE046D9FEC2C91969B4F940BAD4AE6DA12B22697FA2454E9779094D0281197D2EB85222051C394EAECC`
SHA512 | `4147834AE56138B4B6A32F46656AFEACEBD41AEA4C1F119ED346F1E339FB14CA39C83DA84A45CC76D294C98FDC3948A1C763A9E48998B8021A5223AF651DC6C8`
SSDEEP | `768:r/FPyMIoeiJcN4KjGYrxgnNiqbo197WNeFMkDGbUf2hg:r/FRIoeiJbKWNeFMrUf`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: /usr/bin/basename NAME [SUFFIX]
  or:  /usr/bin/basename OPTION... NAME...
Print NAME with any leading directory components removed.
If specified, also remove a trailing SUFFIX.

Mandatory arguments to long options are mandatory for short options too.
  -a, --multiple       support multiple arguments and treat each as a NAME
  -s, --suffix=SUFFIX  remove a trailing SUFFIX; implies -a
  -z, --zero           end each output line with NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

Examples:
  /usr/bin/basename /usr/bin/sort          -> "sort"
  /usr/bin/basename include/stdio.h .h     -> "stdio"
  /usr/bin/basename -s .h include/stdio.h  -> "stdio"
  /usr/bin/basename -a any/str1 any/str2   -> "str1" followed by "str2"

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/basename>
or available locally via: info '(coreutils) basename invocation'

```

### Usage (stderr):
```Batchfile
basename: unknown option -- h
Try '/usr/bin/basename --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\basename.exe |
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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\basename.exe](basename.exe-06A6BE1F6953444247863D2B556B8710.md) | 100

## Possible Misuse

*The following table contains possible examples of `basename.exe` being misused. While `basename.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1556.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1556.002/T1556.002.md) | $passwordFilterName = (Copy-Item "#{input_dll}" -Destination "C:\Windows\System32" -PassThru).basename | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


