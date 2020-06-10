
# auditpol.exe 
* File Path: `C:\WINDOWS\system32\auditpol.exe`
* Description: Audit Policy Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `538128A46A0D751E789A984A9E6E8BF8`
SHA1 | `E8DE077E9FB7AA7220A8F1343051CF2C9A7E12AE`
SHA256 | `643278719C680385D173588FDF2ACD752A65E12180D416D07C1BE79B49231D73`
SHA384 | `34EF8CBBB12F7F30D7A080D0D627971FA928E4AFCC8113F1E2DB1CE062143F1E3B0CB4BE43E50F1039F8D03E1087BA06`
SHA415 | `AD137387E7818673E0AFDD27F4204ED112E7666060D0920CACAAB2D512B3584704694D2C99EFDFE7C7126FBE212CA3766946FDDD0F56A49ED32DEA12DF736A7A`
SSDEEP | `768:1GLeL9hh30sNl3T/QeiTdfwhyYzCoIl0AH4dC3NR0oTeDppoTb+nMucN:7L9hh30oKl5fwioI+jdC3NR0oTeDppoP`

## Runtime Data
### Usage (stdout):
```Batchfile
Usage: AuditPol command [<sub-command><options>]


Commands (only one command permitted per execution)
  /?               Help (context-sensitive)
  /get             Displays the current audit policy.
  /set             Sets the audit policy.
  /list            Displays selectable policy elements.
  /backup          Saves the audit policy to a file.
  /restore         Restores the audit policy from a file.
  /clear           Clears the audit policy.
  /remove          Removes the per-user audit policy for a user account.
  /resourceSACL    Configure global resource SACLs


Use AuditPol <command> /? for details on each command

```

### Usage (stderr):
```Batchfile
Error 0x00000057 occurred:
The parameter is incorrect.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUDITPOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


