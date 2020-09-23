---
title: basenc.exe | 
excerpt: What is basenc.exe?
---

# basenc.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\basenc.exe`

## Hashes

Type | Hash
-- | --
MD5 | `91F0C9999CDE6BC192824476A1DA002B`
SHA1 | `E8E0792BFF4C736ACEC4F2228FCA068937503A6C`
SHA256 | `8CFBC85C184378F52E924852F31C6A26CA6325C81834F157FBF52010BCFC93A7`
SHA384 | `72DCB01AD91AC0DF91AE71E2CB512E185DD7708E5C8AD7D977F6EB2E496615DA1B94C6A0CC89730C0FA21D94F1CEEAA2`
SHA512 | `7F7FF663A67A1E59075294F03B3CC323CFCDED3CD073DA68DB55FB25F5CB129B110BE9215D948A1A81785AF91B3DC4BE68FCA6559A408967C93C0059464BD54D`
SSDEEP | `768:z95nlrUyaNHw2OqsiOGFmQ+A0Rmtr87GLViqboNRcccccccccccccccccccccccG:z95lrlaNQ7qsyFt+lgro3WB52omSZUfj`

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


