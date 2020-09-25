---
title: basenc.exe | 
excerpt: What is basenc.exe?
---

# basenc.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\basenc.exe`

## Hashes

Type | Hash
-- | --
MD5 | `728CBC35FD34F5B1755A5D8DF2663D2E`
SHA1 | `8AD998A683D58B91C517098EDFE1AA855FFE6713`
SHA256 | `F105F7976059EC4EF86B8BBDB9F5CB6A5281218D69450707560CB90F22F9480E`
SHA384 | `816DDC2B2955C4CD5391D8166411D0C03564CB4792630351ACE3BAE16480BCBE902F1859BD3029D95045D52FD02FCB12`
SHA512 | `5B9239FD57FF0BFC5415C78BA6E306CCAECD6CD8F018080366F333941E814F2635F3007D86A2BB0EEBB25EE2796BA51B4DA023DFE69DAEF2A76F37266DD5D1DF`
SSDEEP | `768:TnELrTVQbmCoLf8oEv1BZ2Q73BNK9NiqboQ0O59WvdomN4DG+Uf2hKJ:TELnVQbnoYTv5zANWvdomNiUfL`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/basenc [OPTION]... [FILE]
basenc encode or decode FILE, or standard input, to standard output.

With no FILE, or when FILE is -, read standard input.

Mandatory arguments to long options are mandatory for short options too.
      --base64          same as 'base64' program (RFC4648 section 4)
      --base64url       file- and url-safe base64 (RFC4648 section 5)
      --base32          same as 'base32' program (RFC4648 section 6)
      --base32hex       extended hex alphabet base32 (RFC4648 section 7)
      --base16          hex encoding (RFC4648 section 8)
      --base2msbf       bit string with most significant bit (msb) first
      --base2lsbf       bit string with least significant bit (lsb) first
  -d, --decode          decode data
  -i, --ignore-garbage  when decoding, ignore non-alphabet characters
  -w, --wrap=COLS       wrap encoded lines after COLS character (default 76).
                          Use 0 to disable line wrapping

      --z85             ascii85-like encoding (ZeroMQ spec:32/Z85);
                        when encoding, input length must be a multiple of 4;
                        when decoding, input length must be a multiple of 5
      --help     display this help and exit
      --version  output version information and exit

When decoding, the input may contain newlines in addition to the bytes of
the formal alphabet.  Use --ignore-garbage to attempt to recover
from any other non-alphabet bytes in the encoded stream.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/basenc>
or available locally via: info '(coreutils) basenc invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/basenc: missing encoding type
Try '/usr/bin/basenc --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\basenc.exe |
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






MIT License. Copyright (c) 2020 Strontic.


