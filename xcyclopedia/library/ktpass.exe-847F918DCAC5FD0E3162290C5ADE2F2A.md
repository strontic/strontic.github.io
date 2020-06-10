
# ktpass.exe 
* File Path: `C:\Windows\system32\ktpass.exe`
* Description: Kerberos keytab tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `847F918DCAC5FD0E3162290C5ADE2F2A`
SHA1 | `F4CDDF83A3EF0909B3569C256DBC96D3DF887728`
SHA256 | `2AF1FE66D0A9181F8BEDAF83DFF3AB7D58D36490355147A69047F240BCDBDACD`
SHA384 | `A5638F3FF10EBAF17244BE6CD882AC420CCD898296D682AF4F38B77CFD9B09BB94CF8C1E8B281910C5AFAB137FC7DF01`
SHA415 | `32CEDA70E9257BE9BFB1AA42810951691DA9A6927D8FD75B31414FA8CA1FADB28ED02F897EBE4D7EC6AF9E2BF05C39E5094C42515B60D8FA9584427524AC00A4`
SSDEEP | `768:a26UJ2jK/o47bxidpPfZbSvKz5XVvvSvIPRmFx6U2eFDw0LOhJVoUw:Uu7XoPsvyZQ4U2elRGJVjw`

## Runtime Data
### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
Command line options:

---------------------most useful args
[- /]          out : Keytab to produce
[- /]        princ : Principal name (user@REALM)
[- /]         pass : password to use
                     use '*' to prompt for password.
[- +]      rndPass : ... or use +rndPass to generate a random password
[- /]      minPass : minimum length for random password (def:15)
[- /]      maxPass : maximum length for random password (def:256)
---------------------less useful stuff
[- /]      mapuser : map princ (above) to this user account (default: don't)
[- /]        mapOp : how to set the mapping attribute (default: add it)
[- /]        mapOp :  is one of: 
[- /]        mapOp :        add : add value (default) 
[- /]        mapOp :        set : set value 
[- +]      DesOnly : Set account for des-only encryption (default:don't)
[- /]           in : Keytab to read/digest
---------------------options for key generation
[- /]       crypto : Cryptosystem to use
[- /]       crypto :  is one of: 
[- /]       crypto : DES-CBC-CRC : for compatibility 
[- /]       crypto : DES-CBC-MD5 : for compatibility 
[- /]       crypto : RC4-HMAC-NT : default 128-bit encryption 
[- /]       crypto : AES256-SHA1 : AES256-CTS-HMAC-SHA1-96 
[- /]       crypto : AES128-SHA1 : AES128-CTS-HMAC-SHA1-96 
[- /]       crypto :        All : All supported types 
[- /]    IterCount : Iteration Count used for AES encryption
                     Default: ignored for non-AES, 4096 for AES
[- /]        ptype : principal type in question
[- /]        ptype :  is one of: 
[- /]        ptype : KRB5_NT_PRINCIPAL : The general ptype-- recommended 
[- /]        ptype : KRB5_NT_SRV_INST : user service instance 
[- /]        ptype : KRB5_NT_SRV_HST : host service instance 
[- /]        ptype : KRB5_NT_SRV_XHST :   
[- /]         kvno : Override Key Version Number
                     Default: query DC for kvno. Use /kvno 1 for Win2K compat.
[- +]       Answer : +Answer answers YES to prompts. -Answer answers NO.
[- /]       Target : Which DC to use. Default:detect
[- /]      RawSalt : raw salt to use when generating key (not needed)
[- +]     DumpSalt : show us the MIT salt being used to generate the key
[- +]       SetUpn : Set the UPN in addition to the SPN. Default DO.
[- +]      SetPass : Set the user's password if supplied.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktpass.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


