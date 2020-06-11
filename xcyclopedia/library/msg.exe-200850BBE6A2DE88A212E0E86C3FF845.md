
# msg.exe 

* File Path: `C:\Windows\SysWOW64\msg.exe`
* Description: Message Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `200850BBE6A2DE88A212E0E86C3FF845`
SHA1 | `DB00AB745C637459B74AC5B4769D72F076472C3C`
SHA256 | `548856653546E145C32C1B0CC6C89DBACAA14FAF3BC7107AD332666DDD1CBD2D`
SHA384 | `DAACA78D88C563F034136AC6AAEF2852B16D6164F766AF0AD4F1B44C414D29C06B007F0DBADF60597CA786CC94A24342`
SHA415 | `3ABC8013A00A511802C6FFA33319350ADA319CA6562CCABB666456B6A06D5B4888E356BA44AEC9144D8B6C2848E8900E74E339B00BB5E6471B23738E93473ED4`
SSDEEP | `384:vvpXtYHHqGtCWY9L9I/irrEDKfaEX4inB2QDxaf0FiWcUW6:HRt94CWShIWg+BddF4`

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

MIT License. Copyright (c) 2020 Strontic.


