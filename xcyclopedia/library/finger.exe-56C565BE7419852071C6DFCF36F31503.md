
# finger.exe 

* File Path: `C:\WINDOWS\system32\finger.exe`
* Description: TCPIP Finger Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `56C565BE7419852071C6DFCF36F31503`
SHA1 | `A97EB0BD11BAA5DE960BBB0839F1B5B584B52E38`
SHA256 | `DE0AADB972BC256FDBB234B8CDB5427D8318A91EDFC180D138BEB3358161B2EA`
SHA384 | `D920DA6FAD52A33DA00EAE230B5F4B464128C7F6358165D7776B8F5557B6224123D71C4CD533B5A776C363F60A8BAA7E`
SHA415 | `882C55EA96E9A54028E1065C29B2A7565CC8F9E17DAD4D413EDABABA6C047DECB3853EF6E6D91076A6241CEBC75DF47D84621C32EE81A3851D96C81A5D317CEB`
SSDEEP | `192:0T+V81sDF09kycvbhY+u6pePFzoyrAf992kATG9EUjNEwL7GaWU0W:0T+VCUF09FcDiEpedzeKTIjNbzWU0W`

## Runtime Data

### Usage (stdout):
```Batchfile

[default-pc]

```

### Usage (stderr):
```Batchfile

Displays information about a user on a specified system running the
Finger service. Output varies based on the remote system.

FINGER [-l] [user]@host [...]

  -l        Displays information in long list format.
  user      Specifies the user you want information about. Omit the user
            parameter to display information about all users on the
            specifed host.
  @host     Specifies the server on the remote system whose users you
            want information about.


```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


