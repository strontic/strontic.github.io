---
title: comm.exe | 
excerpt: What is comm.exe?
---

# comm.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\comm.exe`

## Hashes

Type | Hash
-- | --
MD5 | `0E8F57A90F8852759B4E4D6273B82C2F`
SHA1 | `1EC56228851896AAAC2B98B9F1BF2B9980034BCB`
SHA256 | `D57E605AA33154855CBF9D418D96523D37503192263D374B7CA0B435C0927098`
SHA384 | `915A6E431A5CF52034D8E9D7CA531C04665F3ABD55A09611DE6AAB6B93D1438DC5DF5F8FFFAE62BD0D85C673BE12C3B2`
SHA512 | `EF507DCE53495C03A6D639D977FB7710D65B01D5DDC77D90484690187A130C9368D215D3BE5DC12044AA79CEE69A8869F06C3E4F36671671CB1C23A40C55ADBD`
SSDEEP | `768:ld5yDDKnZjG99DnsJ0628DdDvNiqboThqAWlMFbmDGVUf2hX:1yDqZjG9D8lujWlMFbDUfa`

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

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\comm.exe |
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


