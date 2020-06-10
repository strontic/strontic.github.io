
# auditpol.exe 
* File Path: `C:\Windows\system32\auditpol.exe`
* Description: Audit Policy Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `3F7C7B2CE3E905ED4868DEBB640A5234`
SHA1 | `9D0F2C4224F780847E0D1AC6C21C11A0CDCE7EEF`
SHA256 | `91278DA04F3A40DA84CD151D3E69A4F39EEF82BD7F7F3A238DD5E3C224CAA33A`
SHA384 | `36460CFBDB2ECCF1691C54A95DAD1222F028FB901C7FE55E39815275E3DDBA12BD3DF23468AC10AFAC51886FE5D446A2`
SHA415 | `8755396F0E01859C938D5D6E2B0155F0A86E52BE1B14742DA97C71B1A0C002FCCABD3C3628BC55E96E07E9B1320FE3465E7115F3B1295456B831C012954DD0E6`
SSDEEP | `768:k/5zR9nJTTUb0HRh03+pIh7zokpKLBSlLv0U0pv5ar:8RkQzy7zzpKLUlLcU0pv5ar`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUDITPOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


