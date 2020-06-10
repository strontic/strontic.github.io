
# sort.exe 
* File Path: `C:\Windows\SysWOW64\sort.exe`
* Description: Sort Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `995F41569F595164CD60C8160C128D05`
SHA1 | `BC66C5F68BDD7C2D473786F472EDCCC10661F409`
SHA256 | `4529B7450EA09756EDC9EAE43C1DC4EDD29D1A7A19321BE810654997F26A0F8B`
SHA384 | `C522920FE923BD0F4244322D0C18D2A014DB72C9A698DE6FE4948B6CB2FE5413E6C6F482F736FECA027E69AE3A290E82`
SHA415 | `36D2D8F0F635B4C8585933E2E21613A300F1C8B9837F92D7889F51B8C0E3DEE29E16D0F3C0A1F10D7D76CE223227A21F5A7E1414164AC826E1D935884029D3A8`
SSDEEP | `384:i0RnTyULFfjVsEI+4e+lMAw1WjHKXRfa7ZbHWjnWoYwc5:i0tZZsP+3+lMp1k1bwhc5`

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
perfmon.exe

## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Sort.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


