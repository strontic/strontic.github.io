
# sort.exe 

* File Path: `C:\WINDOWS\SysWOW64\sort.exe`
* Description: Sort Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `033AC1BBA5FC910638B68887C4A7D8E8`
SHA1 | `57A56A323B7DBB6E4985C115790F7E14A94E71F5`
SHA256 | `ACF748F1F1B9CCA9CE63A2C5ED8619820C4F21D95BC3BCE3A5F466EADFA19C8F`
SHA384 | `EC3640C3CFAA652FD923D218C1B7E242BCE473922830D27D20443A1F4DF02B0E013DA99E6000BD1DB76EE8924BE93490`
SHA415 | `0C8DE51B207FAF39C4A0717B3AFF7777F88A14F9F2AD553E658030F5AF67B413FC42FBC727715E4D371CCC810A84FF1C90A46875151045EA5D1D1D184F856678`
SSDEEP | `384:3BeKs3+hUjP5qEuDYIeXxrC8iomc5r0eArFSZxgy0vqIOPWtnWRRkIup:3BJ+Q6Ie1NXmHrny0ityCkI`

## Runtime Data

### Usage (stdout):
```Batchfile
SORT [/R] [/+n] [/M kilobytes] [/L locale] [/REC recordbytes]
  [[drive1:][path1]filename1] [/T [drive2:][path2]]
  [/O [drive3:][path3]filename3]
  /+n                         Specifies the character number, n, to
                              begin each comparison.  /+3 indicates that
                              each comparison should begin at the 3rd
                              character in each line.  Lines with fewer
                              than n characters collate before other lines.
                              By default comparisons start at the first
                              character in each line.
  /L[OCALE] locale            Overrides the system default locale with
                              the specified one.  The ""C"" locale yields
                              the fastest collating sequence and is
                              currently the only alternative.  The sort
                              is always case insensitive.
  /M[EMORY] kilobytes         Specifies amount of main memory to use for
                              the sort, in kilobytes.  The memory size is
                              always constrained to be a minimum of 160
                              kilobytes.  If the memory size is specified
                              the exact amount will be used for the sort,
                              regardless of how much main memory is
                              available.

                              The best performance is usually achieved by
                              not specifying a memory size.  By default the
                              sort will be done with one pass (no temporary
                              file) if it fits in the default maximum
                              memory size, otherwise the sort will be done
                              in two passes (with the partially sorted data
                              being stored in a temporary file) such that
                              the amounts of memory used for both the sort
                              and merge passes are equal.  The default
                              maximum memory size is 90% of available main
                              memory if both the input and output are
                              files, and 45% of main memory otherwise.
  /REC[ORD_MAXIMUM] characters Specifies the maximum number of characters
                              in a record (default 4096, maximum 65535).
  /R[EVERSE]                  Reverses the sort order; that is,
                              sorts Z to A, then 9 to 0.
  [drive1:][path1]filename1   Specifies the file to be sorted.  If not
                              specified, the standard input is sorted.
                              Specifying the input file is faster than
                              redirecting the same file as standard input.
  /T[EMPORARY]
    [drive2:][path2]          Specifies the path of the directory to hold
                              the sort's working storage, in case the data
                              does not fit in main memory.  The default is
                              to use the system temporary directory.
  /O[UTPUT]
    [drive3:][path3]filename3 Specifies the file where the sorted input is
                              to be stored.  If not specified, the data is
                              written to the standard output.   Specifying
                              the output file is faster than redirecting
                              standard output to the same file.


```

### Usage (stderr):
```Batchfile
Invalid switch.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Sort.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


