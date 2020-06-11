
# ftp.exe 

* File Path: `C:\Windows\SysWOW64\ftp.exe`
* Description: File Transfer Program
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7223B4C2B0BDBFC4FE677E06AD8C9731`
SHA1 | `6CF73104128E65A4C5DA0AC345A7FAD2C1D0A490`
SHA256 | `B51BA41E045BC3CCED03BD690280958F6E79FA615C909CDE67A5E416824A342A`
SHA384 | `5B9427BD3E90CE90FE7F39011C670011442ECE97ECF534612156D4AA84F82D61FCA98872594C5A7264DCA341E5C6994F`
SHA415 | `4C31C9467EE6CAB99E7FC966AC334C2C9B665412C84B08EA71A3BB46883147DAAA58D165D119653E983BBD4864053B246B99646FCEC793DC67696DC3B54EC5FB`
SSDEEP | `768:/twleIP5pD63KwRtsido3UKct5zip4Tway+19vxMEfNGjWAKB:yltttidaLmEp4T9QiiWA`

## Runtime Data

### Usage (stdout):
```Batchfile

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ftp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


