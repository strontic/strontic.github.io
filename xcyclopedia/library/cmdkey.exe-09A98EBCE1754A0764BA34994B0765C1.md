
# cmdkey.exe 

* File Path: `C:\Windows\SysWOW64\cmdkey.exe`
* Description: Credential Manager Command Line Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `09A98EBCE1754A0764BA34994B0765C1`
SHA1 | `5667887B8B3D7E02B0087AFAA7A679D456B673E2`
SHA256 | `091421E30FC90F6596BACEF7AD874384D8044FC6C1487F351196BACD2D10C4FF`
SHA384 | `FB99FFF082FAF36BF5741964BABC8B0E2A71C197888B87F61B92CC2D65B5AE237A7CB7F45AFB9DFF8FBA74141CEECB61`
SHA415 | `3C6FC2DEA578A9C67C709C42A97590B0AD2466B2DB6272C9C88B26384F31B0DC9945D56780DC6A2E108B381EC16725E18DB4BA505E6F86444241553BB9DAE37D`
SSDEEP | `384:D51DJX8QjkjC8S5LCXddFkYhDO8AWeWQwWdQD:N1DzjkjHDBM81Q3k`

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

MIT License. Copyright (c) 2020 Strontic.


