
# ftp.exe 

* File Path: `C:\WINDOWS\SysWOW64\ftp.exe`
* Description: File Transfer Program
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8149085604E1B1D9C7872E619F5B0D52`
SHA1 | `B6DAB50D22BF997B37B25CD6C2EB95BC6332A455`
SHA256 | `A0A27B65B1359B659568ED59637F36F216377A7F2066D15DB5BE7024EB48863D`
SHA384 | `0F3D48CCC3B743C930C475B107B7D81658C09E70722557B33F565C19166060171FB977E38065078E416A76342A34539B`
SHA415 | `56F9B929F5D891112D3BFC9AA83279890FA15B8E36BD8EE2464D44EDC8C7895636262927B128E60C0427A37AFD7C8CD2839FB144956CA684B5DDDF4A03893E8C`
SSDEEP | `768:h0E/x9/S+KW2626a6tWZa2ZeNmrhRf3qjmVeD6f2/Dd7/BaB5BW3iI:SIrMKWZxZeNmEJtDdUB5Ep`

## Runtime Data

### Usage (stdout):
```Batchfile
Unknown host help.
ftp> 
```

### Usage (stderr):
```Batchfile

Transfers files to and from a computer running an FTP server service
(sometimes called a daemon). Ftp can be used interactively.

FTP [-v] [-d] [-i] [-n] [-g] [-s:filename] [-a] [-A] [-x:sendbuffer] [-r:recvbuffer] [-b:asyncbuffers] [-w:windowsize] [host]

  -v              Suppresses display of remote server responses.
  -n              Suppresses auto-login upon initial connection.
  -i              Turns off interactive prompting during multiple file
                  transfers.
  -d              Enables debugging.
  -g              Disables filename globbing (see GLOB command).
  -s:filename     Specifies a text file containing FTP commands; the
                  commands will automatically run after FTP starts.
  -a              Use any local interface when binding data connection.
  -A              login as anonymous.
  -x:send sockbuf Overrides the default SO_SNDBUF size of 8192.
  -r:recv sockbuf Overrides the default SO_RCVBUF size of 8192.
  -b:async count  Overrides the default async count of 3
  -w:windowsize   Overrides the default transfer buffer size of 65535.
  host            Specifies the host name or IP address of the remote
                  host to connect to.

Notes:
  - mget and mput commands take y/n/q for yes/no/quit.
  - Use Control-C to abort commands.

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

* Original Filename: ftp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


