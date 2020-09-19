---
title: comm.exe | 
---

# comm.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\comm.exe`

## Hashes

Type | Hash
-- | --
MD5 | `EE98238E36DC7A742C00C05B5D600EDC`
SHA1 | `17232EF64A4D72BDD8C9BDB2ED12E23E7117DE70`
SHA256 | `7009CED568E04BDCB1D7E62B6DA396F349676067C239434E11F955490B2BDCAA`
SHA384 | `D110717DC3D4226FEF29194B1DA0C089B631D9B8BC932963EB4DD14894BB5E7EFB8C6F03558BC6A5EEE46403848F2495`
SHA512 | `5988816848E644A6DBEF5441EE9FC90635D30CF6EB8BDD9019E5AC78ABC234E3ED6D940119587120CB29A25082E033A40DA6C83AF7D0B0015BD54E94C3195193`
SSDEEP | `768:tTgFiCDsvDmZibQFeXRo/MBLViqboplccccccccccccccccccccccccccccccccM:tTEbDsS6GeXYMaWgFIJlUf`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/comm [OPTION]... FILE1 FILE2
Compare sorted files FILE1 and FILE2 line by line.

When FILE1 or FILE2 (not both) is -, read standard input.

With no options, produce three-column output.  Column one contains
lines unique to FILE1, column two contains lines unique to FILE2,
and column three contains lines common to both files.

  -1              suppress column 1 (lines unique to FILE1)
  -2              suppress column 2 (lines unique to FILE2)
  -3              suppress column 3 (lines that appear in both files)

  --check-order     check that the input is correctly sorted, even
                      if all input lines are pairable
  --nocheck-order   do not check that the input is correctly sorted
  --output-delimiter=STR  separate columns with STR
  --total           output a summary
  -z, --zero-terminated    line delimiter is NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

Note, comparisons honor the rules specified by 'LC_COLLATE'.

Examples:
  /usr/bin/comm -12 file1 file2  Print only lines present in both file1 and file2.
  /usr/bin/comm -3 file1 file2  Print lines in file1 not in file2, and vice versa.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/comm>
or available locally via: info '(coreutils) comm invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/comm: missing operand after 'help'
Try '/usr/bin/comm --help' for more information.

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


