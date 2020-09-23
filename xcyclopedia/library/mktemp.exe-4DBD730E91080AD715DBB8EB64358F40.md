---
title: mktemp.exe | 
excerpt: What is mktemp.exe?
---

# mktemp.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\mktemp.exe`

## Hashes

Type | Hash
-- | --
MD5 | `4DBD730E91080AD715DBB8EB64358F40`
SHA1 | `C2AED06005D30058C9A278A45959E7A023A26A42`
SHA256 | `50882C11CC756C99A1EB36C5BDCDF1D60FA27FD0A4EDCE2EA612736F6EDDFE41`
SHA384 | `6F14FA1BC33DEFE5E0ABC30BE4A426D8469A69A9CBCC772A620600E553948C787BE6145723AAAA069AFDDA811A3BEAD0`
SHA512 | `298647C2285BDB3A54A8EBBC8A9688ED879D8A194D8FF8A5B53CF47A63D3A02D2CBA638FCA1508B45C6305A3F86864487D4B5774E04625D77C8A9AD0D2481A8A`
SSDEEP | `768:LnlPsT9hTkRTupJP4GvwjH+iLViqbojCccccccccccccccccccccccccccccccca:DlPs/TkRTugJHAWoVDFljUf`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
mktemp: unknown option -- h
Try '/usr/bin/mktemp --help' for more information.

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


