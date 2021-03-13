---
title: b2sum.exe | 
excerpt: What is b2sum.exe?
---

# b2sum.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\b2sum.exe`

## Hashes

Type | Hash
-- | --
MD5 | `8C5A2AFC76A80B1E384695672B295354`
SHA1 | `80252C8530D6117F3C60F0018FEDFC6AE891517E`
SHA256 | `30C907BFC35B62409CAFC3F71A603FF0261B109A26AFB7B133688A41BCE52006`
SHA384 | `56AB95F00F6253ADCFFF62496A2CB5D4AD6341FC2197556180765D66E9D863B86C1CAEEBE6327B3A379EF0F7D2C5E12F`
SHA512 | `4FF9A9286E8163607B0FEFB937FE633E88B5BF3BB11504440CD32382A0D9698DE366E14BC8203E1218D80CEF28A5BF2A278A10EDEAA358DEA4E8808C9588BE4A`
SSDEEP | `1536:AQ3ddlStzj2yMpNbFvjp1eJoU3SnsWDLoQLUfe:V3zlyJMp3vjpkJJ3SnJDLoQJ`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/b2sum [OPTION]... [FILE]...
Print or check BLAKE2 (512-bit) checksums.

With no FILE, or when FILE is -, read standard input.

  -b, --binary         read in binary mode (default unless reading tty stdin)
  -c, --check          read BLAKE2 sums from the FILEs and check them
  -l, --length         digest length in bits; must not exceed the maximum for
                       the blake2 algorithm and must be a multiple of 8
      --tag            create a BSD-style checksum
  -t, --text           read in text mode (default if reading tty stdin)
  -z, --zero           end each output line with NUL, not newline,
                       and disable file name escaping

The following five options are useful only when verifying checksums:
      --ignore-missing  don't fail or report status for missing files
      --quiet          don't print OK for each successfully verified file
      --status         don't output anything, status code shows success
      --strict         exit non-zero for improperly formatted checksum lines
  -w, --warn           warn about improperly formatted checksum lines

      --help     display this help and exit
      --version  output version information and exit

The sums are computed as described in RFC 7693.  When checking, the input
should be a former output of this program.  The default mode is to print a
line with checksum, a space, a character indicating input mode ('*' for binary,
' ' for text or where binary is insignificant), and name for each FILE.

Note: There is no difference between binary mode and text mode on GNU systems.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/b2sum>
or available locally via: info '(coreutils) b2sum invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/b2sum: failed to set file descriptor text/binary mode: Bad file descriptor

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\b2sum.exe |
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






MIT License. Copyright (c) 2020-2021 Strontic.


