
# wevtutil.exe 
* File Path: `C:\Windows\system32\wevtutil.exe`
* Description: Eventing Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `91803E340A7E7AFDF95A8031F6EF3F3E`
SHA1 | `7673526B188C4012E53B0B436701C10AF256E2B8`
SHA256 | `DCFD99FE08A5D46C52E810FE2F9CC15AC82008975C0A731A11773B11ADE0F3CC`
SHA384 | `953D7E4073207DA5AE985BD6A2A899FBFF6B49A0F4303AC9276D6BD8584908F2AC0FBB6BF429F80656BB9C01E347B935`
SHA415 | `E4BBAB5A6444213F15F034A86CE4708BA58ACF42BE8BF78D0C893CC9D0F5AF57832832181F452420A19FB8FA1A639BA3206B8450AEDE4531607DD0B9FA02293C`
SSDEEP | `6144:4ZmJ1a5hEP2sQtsIyTM6IJfgieD8F16BcsGWptybsVvfqs:4ZmO5hEtIyngfgHkgpGWpImv`

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
Command help is not supported. The parameter is incorrect.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wevtutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


