
# wevtutil.exe 

* File Path: `C:\WINDOWS\SysWOW64\wevtutil.exe`
* Description: Eventing Command Line Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `253FBAC6CB4CDCE6341C5341A75A3ACB`
SHA1 | `03BEDFC1FFB54D3148BAD9C178D29313240E8180`
SHA256 | `8DAAD695CD42FE78FD7DF497EDEBC48F56C3CFA1D9025DF5580EDCD835AEF85D`
SHA384 | `5F8177E4BA1803A51F634089E21F3A497C1A6527B0893408694158FD6A594B421975FF27FEC6DD8476AADCC4AB1D643E`
SHA415 | `B9664AD1C7AEBE7DE9AC7F3B44B27967B1C6390DAF2692B8873A3CE00C4987F9A652EA6CA3E2CF9ED39DE2C3930BC2508A5DAFDEFC455AC59732BB75AEA19932`
SSDEEP | `3072:yD3DzFwwc00+024+53Mx7lrN41th7KEjEqmLDk5LUZRKffnNTNWlUBDtFyFfz+BN:CKN+024+Sx7lrNipKE4qmL4LUSffNTNT`

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

* Original Filename: wevtutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


