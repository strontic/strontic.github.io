
# auditpol.exe 
* File Path: `C:\WINDOWS\SysWOW64\auditpol.exe`
* Description: Audit Policy Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `29EE7196CC3449AB98EB4969BE64C1C5`
SHA1 | `58DA09E70E2D6EE47BFE3E2FA447F37E15ABEFBE`
SHA256 | `F2700C63442130158F3B685F99045198EA696497B23146391213574C17456DD5`
SHA384 | `B39BC40CCD5184F5FD77198C4CF017443C44E73DF502F5993C3F6759D00C638EA80559EF6D2F57F7E7DB9B3142794F4D`
SHA415 | `2446705C2636B6083FBB19D76169863DC5C44B6B1CBCC8E24C4B40183F23D35AA11105A06F59A24E8F22F9E283B105BC15A4602E3F38916389FC565B341D7910`
SSDEEP | `768:0OlUgG8shEgvlZ0iFu39j/WAyIpduD2NR9:L+pfhzvsQS97WHIXuD2NR9`

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

* Original Filename: AUDITPOL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


