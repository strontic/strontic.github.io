
# wevtutil.exe 

* File Path: `C:\Windows\SysWOW64\wevtutil.exe`
* Description: Eventing Command Line Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2AD0BFAAD4555FF42E81BAE334925CF8`
SHA1 | `63F0B5BD629402738669D895FF1B7C9DDAE412E7`
SHA256 | `18A73E6657479D255CAE83FABF8B080B7DEF50F5F5E4D20FEFD57D44678BBF48`
SHA384 | `79E45B41B6EB896EB6818F46D7E9BB444231EBE258221953FC4A6E36A6A18E6487BBA8D1F1CE40EDA6AFE719F91D2BB3`
SHA415 | `728CE2BFD0FF772DAE910E31E536DC73BA154517E02E9158EEECA65E534575823CFEF402B65FC26C9B33F36C64DFED9D2B057FBE3265F25C050B5389A1D936AA`
SSDEEP | `3072:C62QnDLHF84UeGUe3zU2CH1bDAvEHYEQkyhTxtdGlVvM4Rv5D:C61/WCs3zU2CVjHYEQkUdt4lVvh`

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

MIT License. Copyright (c) 2020 Strontic.


