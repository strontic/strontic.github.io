
# ftp.exe 
* File Path: `C:\WINDOWS\system32\ftp.exe`
* Description: File Transfer Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `ECD4D5B9579F8D28662212DAE741929A`
SHA1 | `0C43673D6E2833186C4C6D769EA9C0AAFA67411A`
SHA256 | `F2E90D24AC7B15725750A7532CA52C596EAB980CA199F7580FD7FA4FB0C351B1`
SHA384 | `4211EB8CA5A7B0D6009E4707754836E40D11B5714000CF64D9868DC8DA4899F29C6D9D1FA4819C429911CCD3F08C2ABC`
SHA415 | `9292A78C962B13DF304AD348228BE0A1A16F10595D50BE68ACEE6EC1151E5C6CA162B09FB02D831558A502E7547FF5F7B46597E1DA96B00383E0E3B337587513`
SSDEEP | `1536:wJJs/XMsSn2hAIXLRAR5VQEGcL0lpiJRJ8ihg+eup9MXf:wJOcQuVQEGcL0bYR+jHv`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ftp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


