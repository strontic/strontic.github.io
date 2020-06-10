
# cmdkey.exe 
* File Path: `C:\WINDOWS\SysWOW64\cmdkey.exe`
* Description: Credential Manager Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `E33DB7B7EC84FA314E917FABD05312D1`
SHA1 | `7CC282DD87B8FEC197547C81A158B0A4B03DAF16`
SHA256 | `224999A92BF4108AB32BB06DEB7510A534431D41B86BC527B1028C70A15705EE`
SHA384 | `E4051F8C18479E146CDDADB8473D55B9066E520FE99A921FF85C70B4816ACBFED2B91800F90D69F31FE192D93F9196DE`
SHA415 | `9CD06D586FFB8328D30934FD83B3CBAEB55FDE83F0FE040F1B590A2085BDFF2B3233189D1BCBF83783B8DCB1EFE5984949F97B852753F89135F886986800D992`
SSDEEP | `384:sXDMrVrS2sXpdwDqudqL/XYzd/3YGllWiwWW5K:sXDbPwDLkYhAGlPI5K`

## Runtime Data
### Usage (stdout):
```Batchfile

Creates, displays, and deletes stored user names and passwords.

The syntax of this command is:

CMDKEY [{/add | /generic}:targetname {/smartcard | /user:username {/pass{:password}}} | /delete{:targetname | /ras} | /list{:targetname}]

Examples:

  To list available credentials:
     cmdkey /list
     cmdkey /list:targetname

  To create domain credentials:
     cmdkey /add:targetname /user:username /pass:password
     cmdkey /add:targetname /user:username /pass
     cmdkey /add:targetname /user:username
     cmdkey /add:targetname /smartcard
     
  To create generic credentials:
     The /add switch may be replaced by /generic to create generic credentials

  To delete existing credentials:
     cmdkey /delete:targetname

  To delete RAS credentials:
     cmdkey /delete /ras
     

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cmdkey.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


