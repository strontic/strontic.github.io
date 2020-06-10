
# msg.exe 
* File Path: `C:\WINDOWS\system32\msg.exe`
* Description: Message Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `E70EB0CFABC4927A3A40E8738E173711`
SHA1 | `477C9AF2ED50133A5458242B9F3D233A126832F8`
SHA256 | `0157BD32C17BEDADEDD95C1FE59A33D0201F1C77422B40C05F2A81A5FF503F4F`
SHA384 | `BD39327C6B4E9649B34F79F7AC9920CB6FA0A5DEE8C9C5A86B6591B4D703C1901EA3E2259EC769748F30AD7366FC9E6D`
SHA415 | `8E2961176A05F3A612F42A1863D778F22C05D74C26FE7B16ECA72D571EC25A265BDDD4745B59479339CC9BE30CD932E019F4C2F1E180C2C13C5644AE03CDF13C`
SSDEEP | `384:zd2EwJxreLEQQ8oo9Z0pWPouQmjeeEETz5TwOK8j75ACMivFysnfK8TbIGSWeUW:zUEwLrJQgoPEmoupae3yOK8xfvUIy`

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
* Serial: 33000001C422B2F79B793DACB20000000001C4
* Thumbprint: AE9C1AE54763822EEC42474983D8B635116C8452
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


