
# ktpass.exe 
* File Path: `C:\Windows\SysWOW64\ktpass.exe`
* Description: Kerberos keytab tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `08F6267765787E26A600D0105F4614A8`
SHA1 | `FEF4B97B981A19C213203F2FB382B7461A53006D`
SHA256 | `697C8D6E990CC234539836B572D4F45EF88F11D0257D92BE8B466D71359B6869`
SHA384 | `0C33850CA54B1FFB8857918FAEDCEE1C930BDBEF7860AE7B2444012334CA85464D8EA8A07AC7F23B0E5EC211CB6E233A`
SHA415 | `D710112A4D42D5822E5F9D1C6D8A2B05EC599DF76346FF137A6372909F976E9B30284A53E1D591E9C285715EB1CC68D44BE4A8570E7ED80F718A0406E1CC5BBB`
SSDEEP | `768:EQTgUrUqr+j0/A9gy/VHIsMGMdnQdi1BewE3UfJb8dPVSwV5z:5RD+j9gydmXQdijelUxgPVSw7z`

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


