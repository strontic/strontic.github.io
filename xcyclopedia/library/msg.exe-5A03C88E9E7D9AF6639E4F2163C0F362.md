
# msg.exe 
* File Path: `C:\Windows\system32\msg.exe`
* Description: Message Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `5A03C88E9E7D9AF6639E4F2163C0F362`
SHA1 | `DDB85CDEBAA9ED9714F13C15494CAB08FC6C9A0C`
SHA256 | `D0BA68097E58029D22D9E7BAA07F124CF42189EE497465D126BD5A6A625A707C`
SHA384 | `2CA8FBD3A8ECB3E6D41C5E2C4290F2FD245DFAB508348CCDC3019E46C35B9FF3F7FFC6BA613AF434E181DA00E1711A9C`
SHA415 | `6BEEB65722D9CB458F840FCBD3B391B8E429F118C3669C7FA5BF41C40E2FE9BE37C57B8B4379D44E43823DA3A9C176D84E48B4C715717BA0454D3655270021A5`
SSDEEP | `384:zmPP5gSkFAk1phZ/c15RJjQ3stasvP7EK55jUSvK7RNVRJ+HWC4G5ctKOOBX+whQ:zmn5gbCEpbD8zPJeSvwVOFjdhw`

## Runtime Data
### Usage (stdout):
```Batchfile
Send a message to a user.

MSG {username | sessionname | sessionid | @filename | *}
    [/SERVER:servername] [/TIME:seconds] [/V] [/W] [message]

  username            Identifies the specified username.
  sessionname         The name of the session.
  sessionid           The ID of the session.
  @filename           Identifies a file containing a list of usernames,
                      sessionnames, and sessionids to send the message to.
  *                   Send message to all sessions on specified server.
  /SERVER:servername  server to contact (default is current).
  /TIME:seconds       Time delay to wait for receiver to acknowledge msg.
  /V                  Display information about actions being performed.
  /W                  Wait for response from user, useful with /V.
  message             Message to send.  If none specified, prompts for it
                      or reads from stdin.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Send a message to a user.

MSG {username | sessionname | sessionid | @filename | *}
    [/SERVER:servername] [/TIME:seconds] [/V] [/W] [message]

  username            Identifies the specified username.
  sessionname         The name of the session.
  sessionid           The ID of the session.
  @filename           Identifies a file containing a list of usernames,
                      sessionnames, and sessionids to send the message to.
  *                   Send message to all sessions on specified server.
  /SERVER:servername  server to contact (default is current).
  /TIME:seconds       Time delay to wait for receiver to acknowledge msg.
  /V                  Display information about actions being performed.
  /W                  Wait for response from user, useful with /V.
  message             Message to send.  If none specified, prompts for it
                      or reads from stdin.


```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


