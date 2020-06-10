
# tscon.exe 
* File Path: `C:\Windows\system32\tscon.exe`
* Description: Session Connection Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `C016EB73D00753336161B7397DE4AA96`
SHA1 | `93C08CF77F7C5C8CCBE83499F3C0E01895404A40`
SHA256 | `BDC8ADA1C5F994A656A8B79BDB7A9F9935B5E49172FCD744B46CF78ED706D47B`
SHA384 | `4E8A84ADE5659FA21234015A45E0E6316D848D5834E678BDD8F6475106194BB356C4D9181A101757EF89FA2169FC04A5`
SHA415 | `A84908B06DD0202540B31D6A06413AE766437A598FE2CC4AF5815A749FE7DFFECCA27862D9395C4DC4F4F42FD9103B5FD62884ADEBB856C812C9379D2ABA782D`
SSDEEP | `384:MX122/6vmRvN4Cst5Qe9E/55nk4W6NNIdW/K+Q9f5hFHyIyrUIhzWjegW:MlzKFR/IZ5HqdCYx7IhB`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


