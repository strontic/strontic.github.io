
# cmdkey.exe 
* File Path: `C:\Windows\system32\cmdkey.exe`
* Description: Credential Manager Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `343E6DA0ADF3D528C54E1767254432A6`
SHA1 | `AD489907F7EE31329CC09E70E21FF70B8EF43DB1`
SHA256 | `89B6A8CB5CF989E3D999482CECF779BA295871A9C80C8CA151694942D5881114`
SHA384 | `861113EC543A92759B4A659F0027A6E1C2C0B91A35E7721C14A2793B4B0654A3A93A90187DD7335C8178F219BE1B947F`
SHA415 | `7BEA84928ED745BFDF9F22E11E2032168AF402B4BF76F35AB05CE2EE54CF1755385AAB74F2551CF74347FD212513DF15F7A08C9C4C9C3A2EA7211ACCA263D705`
SSDEEP | `384:uEpXrrS58wQb5Hm/D9LtkwkNdsHCybbm/rD1/D/8F62WQwW:7rSHQlH+YICmm/rD1b8Q4`

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
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


