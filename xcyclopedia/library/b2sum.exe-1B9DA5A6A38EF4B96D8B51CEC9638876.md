---
title: b2sum.exe | 
---

# b2sum.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\b2sum.exe`

## Hashes

Type | Hash
-- | --
MD5 | `1B9DA5A6A38EF4B96D8B51CEC9638876`
SHA1 | `7AA9B5A21E83C17D5F4E050243CF24C3AB7528D4`
SHA256 | `CB35753603B8E62983E90E28F89F0BFBDAD78299B21B2A8E3E1C8F098DEC8665`
SHA384 | `6059DD9A051247D28B0F70A323595C0EFB3C7A970CEFA6FBBEC5FC98778B389F31FEE3A6D0224ECC0E6971BDAFDD2873`
SHA512 | `7B5FBE4B3D12ACFB174D247672419CCD1AFF512739FFA84157C83EF54ECB5A3CD749A067F122DEF403615902655AF476D375E629EDA1F91299D3DC0F6BF3F69B`
SSDEEP | `1536:XMVm2UMsfCk0AZe2Q6GkeeeeeeeeeeeeeeUeeeeeeeeeeeeeeeeeeeeeeeeJeeeC:XSUJfCnAZe2nGkeeeeeeeeeeeeeeUeeX`

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

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/b2sum>
or available locally via: info '(coreutils) b2sum invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/b2sum: failed to set file descriptor text/binary mode: Bad file descriptor

```

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





MIT License. Copyright (c) 2020 Strontic.


