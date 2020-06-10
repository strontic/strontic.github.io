
# cmdkey.exe 
* File Path: `C:\WINDOWS\system32\cmdkey.exe`
* Description: Credential Manager Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `A5390D2AECD60BDE25B85868FB7D1663`
SHA1 | `728D70C3ACF5179F6DD7F1A774C615F8326063EF`
SHA256 | `E6AD20EB41B82EB4211211522E3FA1E2ACF434766000A09B3F2BADE7A120411B`
SHA384 | `50055338A04B8DE28F5B1D50657E428BD9F83E32CD68BC042B54E29A2C0BAF7A68B766BBDC984EF14C2AECCFD4E3E567`
SHA415 | `3022BBB91384F1A66C0B48F60DCE0DA64B11C814975D94E03C75E8066EA1343A2A881B275E99868FC0095F274B5C437E5D74AC52ADC0F9F75CCA39ACF458FD87`
SSDEEP | `384:E3K4N9/4sTPWtvuKltPiEM5OUDdTXTlJ31Gp9WiwW:JoQrt6VtD3zGp3`

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

* Original Filename: cmdkey.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


