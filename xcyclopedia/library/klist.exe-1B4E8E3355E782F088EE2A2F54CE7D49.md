
# klist.exe 
* File Path: `C:\Windows\system32\klist.exe`
* Description: Tool for managing the Kerberos ticket cache
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `1B4E8E3355E782F088EE2A2F54CE7D49`
SHA1 | `0212B9B929CD5224B181081EEFAEAC5BE04038C4`
SHA256 | `4E05E47D6344D8693CF95B1B2F74FD0D372E054485924E8917E9A38A78505B11`
SHA384 | `914DB5757A25AE597B8F33B017A1790CD23F92B8452EBA7697997FE7F759C735DD98CC42A0C9D7705B32FC77E0277979`
SHA415 | `319601AF797016FCBAB56DDA173E5C610D9383D0059A9D71BE5AD93C4D31936455C9B7DBBA76FAD2625CD3476CBB5A89275E0D4AEBEE716032A449D02039E426`
SSDEEP | `768:3Kajkfz/QQCxSTDYlx0lSz4XNCLU4ZQ8Fci4n8D1cDxN6qvLmV/n:axfz4i4PLUVMqvaV/n`

## Runtime Data
### Usage (stdout):
```Batchfile

Usage: klist.exe [command]

Command list:
  [tickets] [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  tgt [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  purge [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  sessions [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  kcd_cache [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  get <SPN> [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
            [-kdcoptions <options>] [-cacheoptions <options>]
  add_bind <DOMAIN> <DC>
  query_bind
  purge_bind

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: klist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


