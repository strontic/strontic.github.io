
# tscon.exe 
* File Path: `C:\WINDOWS\system32\tscon.exe`
* Description: Session Connection Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `DF63ED6744525C475CD9F347EF2A7ADC`
SHA1 | `026E0FE254F4976B05539434CB0B979F466C1039`
SHA256 | `EC0E8104CEC80F4503FC1776F03B20D124A83AB3268968F3F1DE54FAC443F0B0`
SHA384 | `876840C4DECAAEF7906C95CF4780B73AF988784CC7522C7EE37567910A7AE7D5E675CA4C7AC478C317804C92CF653F88`
SHA415 | `68069EEAA3EF1BDC351D1E5040B0E89446563B9B179376F6C387B450F5973160E909108DC6DA2A8B6B5C504556CFCDF36A3FDEFD133959F2F78632AA4822E0B5`
SSDEEP | `384:Ex4GaOjrQ0Vd5mIbhzELz58xYK8+JVbCODeub+xfQHc5ycZs3bWjsgW:oXAcd4UhaeYK82lCqezxZW3H`

## Runtime Data
### Usage (stdout):
```Batchfile
Attaches a user session to a remote desktop session.

TSCON {sessionid | sessionname} [/DEST:sessionname]
        [/PASSWORD:pw | /PASSWORD:*] [/V]

  sessionid          The ID of the session.
  sessionname        The name of the session.
  /DEST:sessionname  Connect the session to destination sessionname.
  /PASSWORD:pw       Password of user owning identified session.
  /V                 Displays information about the actions performed.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Attaches a user session to a remote desktop session.

TSCON {sessionid | sessionname} [/DEST:sessionname]
        [/PASSWORD:pw | /PASSWORD:*] [/V]

  sessionid          The ID of the session.
  sessionname        The name of the session.
  /DEST:sessionname  Connect the session to destination sessionname.
  /PASSWORD:pw       Password of user owning identified session.
  /V                 Displays information about the actions performed.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000001C422B2F79B793DACB20000000001C4
* Thumbprint: AE9C1AE54763822EEC42474983D8B635116C8452
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


