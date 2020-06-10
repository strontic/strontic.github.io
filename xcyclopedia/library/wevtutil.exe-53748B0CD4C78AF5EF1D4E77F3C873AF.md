
# wevtutil.exe 
* File Path: `C:\WINDOWS\system32\wevtutil.exe`
* Description: Eventing Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `53748B0CD4C78AF5EF1D4E77F3C873AF`
SHA1 | `B326DA71B18EFE153F2EEA3B4DE864AC8AA0FC3E`
SHA256 | `E16B9D201EC1D7E29B3AD532A9AD8F1AE0CB5821BB916A79F6DBEB1C6E6B85FA`
SHA384 | `9A5B70374D9D709DF25C623C0289CCC8084122A7D2234563B745D4A2BC6381C3C4AEF1961102DCD95C72987CB2AC4E5B`
SHA415 | `092923F239E34036F3C858C6A21896306940264CB27530F256D3A9F797EC69BF2B198916BD57E2937068E21A357E4624CD583A0A202D3DF233EE5E6A969ABEF0`
SSDEEP | `3072:ErPhXZDqesxB+La1I6lOprqtXzQLxLiJvcIXSBPiJsLiyrDHzjlgOM/ADVqK8Rsc:E3u1YrqtjO9UkIBJei+a3Ih2/LItW/B`

## Runtime Data
### Usage (stdout):
```Batchfile
Windows Events Command Line Utility.

Enables you to retrieve information about event logs and publishers, install
and uninstall event manifests, run queries, and export, archive, and clear logs.

Usage:

You can use either the short (for example, ep /uni) or long (for example, 
enum-publishers /unicode) version of the command and option names. Commands, 
options and option values are not case-sensitive.

Variables are noted in all upper-case.

wevtutil COMMAND [ARGUMENT [ARGUMENT] ...] [/OPTION:VALUE [/OPTION:VALUE] ...]

Commands:

el | enum-logs          List log names.
gl | get-log            Get log configuration information.
sl | set-log            Modify configuration of a log.
ep | enum-publishers    List event publishers.
gp | get-publisher      Get publisher configuration information.
im | install-manifest   Install event publishers and logs from manifest.
um | uninstall-manifest Uninstall event publishers and logs from manifest.
qe | query-events       Query events from a log or log file.
gli | get-log-info      Get log status information.
epl | export-log        Export a log.
al | archive-log        Archive an exported log.
cl | clear-log          Clear a log.

Common options:

/{r | remote}:VALUE
If specified, run the command on a remote computer. VALUE is the remote computer 
name. Options /im and /um do not support remote operations.

/{u | username}:VALUE
Specify a different user to log on to the remote computer. VALUE is a user name
in the form domain\user or user. Only applicable when option /r is specified.

/{p | password}:VALUE
Password for the specified user. If not specified, or if VALUE is "*", the user 
will be prompted to enter a password. Only applicable when the /u option is
specified.

/{a | authentication}:[Default|Negotiate|Kerberos|NTLM]
Authentication type for connecting to remote computer. The default is Negotiate.

/{uni | unicode}:[true|false]
Display output in Unicode. If true, then output is in Unicode. 

To learn more about a specific command, type the following:

wevtutil COMMAND /?

```

### Usage (stderr):
```Batchfile
Command help is not supported.
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

* Original Filename: wevtutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


