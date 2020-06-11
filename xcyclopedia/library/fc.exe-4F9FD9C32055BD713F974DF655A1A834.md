
# fc.exe 

* File Path: `C:\Windows\system32\fc.exe`
* Description: DOS 5 File Compare Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4F9FD9C32055BD713F974DF655A1A834`
SHA1 | `B7DE142BDCF56551C4FA0F20AEF96428F4BEBD45`
SHA256 | `FD9E665C2CB62778A6E7AB2C9F3B78700F8C6E16B0555E3AE1E73F3996A23F07`
SHA384 | `865923343CE0D0633B490D8DA7AF913D6101EEBD7335F78F880084F9BC8490C23A9470BA31FE759ECAB0941793C64777`
SHA415 | `A2B5BA13D42EC3FCB28BAE9EEC38AF857EA9D5131C186C50996F00028E394E6F78A94B658617EE11ACA7D03FEFE342315447CE3169A32BFA4C5A4D15B6E5BD13`
SSDEEP | `384:uuZasabyl+bHLdPGNu59VpoVfO5HyfTC9A8ih8eWrqYW:nasa+l+l2u59oVkyLCFrq`

## Runtime Data

### Usage (stdout):
```Batchfile
Compares two files or sets of files and displays the differences between
them


FC [/A] [/C] [/L] [/LBn] [/N] [/OFF[LINE]] [/T] [/U] [/W] [/nnnn]
   [drive1:][path1]filename1 [drive2:][path2]filename2
FC /B [drive1:][path1]filename1 [drive2:][path2]filename2

  /A         Displays only first and last lines for each set of differences.
  /B         Performs a binary comparison.
  /C         Disregards the case of letters.
  /L         Compares files as ASCII text.
  /LBn       Sets the maximum consecutive mismatches to the specified
             number of lines.
  /N         Displays the line numbers on an ASCII comparison.
  /OFF[LINE] Do not skip files with offline attribute set.
  /T         Does not expand tabs to spaces.
  /U         Compare files as UNICODE text files.
  /W         Compresses white space (tabs and spaces) for comparison.
  /nnnn      Specifies the number of consecutive lines that must match
             after a mismatch.
  [drive1:][path1]filename1
             Specifies the first file or set of files to compare.
  [drive2:][path2]filename2
             Specifies the second file or set of files to compare.


```

### Usage (stderr):
```Batchfile
FC: Insufficient number of file specifications


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


