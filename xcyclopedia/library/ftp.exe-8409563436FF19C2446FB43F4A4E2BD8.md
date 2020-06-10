
# ftp.exe 
* File Path: `C:\Windows\system32\ftp.exe`
* Description: File Transfer Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `8409563436FF19C2446FB43F4A4E2BD8`
SHA1 | `089D7DED75D46350C8277A06777F3EB3AC870E25`
SHA256 | `4D30F463695D25CE3AAF9C51E9B7BE4823FBB79B6E31847DEB2BA1111755B2D6`
SHA384 | `5D7510D6E1F531764E38D061FD90BDFFD6A72F86EE46FB2CCFFEF99A4E3D64DDB3E29889D7A967C4F476AED62182B8A7`
SHA415 | `60768843E9B62D09F32FB831251D1548EE9112D15ED9CDA377D845B5A37A4225C10D493B585D8B74F3061F236469739A5FBC36F8EA94522C1B5B2DAA8FD23002`
SSDEEP | `768:a4pERzH1GacDuC58ggyVWwP1LDq9euFkWlJsnfk7pqe0t1KCJZSVuQqpwT4Bu9T:lpUKJ5TzrdQB2Ht1ZSV/44`

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


