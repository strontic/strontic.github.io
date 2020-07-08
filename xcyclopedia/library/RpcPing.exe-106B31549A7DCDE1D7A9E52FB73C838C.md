---
title: RpcPing.exe | RPC Ping Utility
---

# RpcPing.exe 

* File Path: `C:\Windows\system32\RpcPing.exe`
* Description: RPC Ping Utility

## Hashes

Type | Hash
-- | --
MD5 | `106B31549A7DCDE1D7A9E52FB73C838C`
SHA1 | `B0CBDF0F2375950F87AB346B043F3CE85009E811`
SHA256 | `B26CA32A7EEE65B90658EACAEB3589E69E9EFB5686CE6CEC7D20C1766DA34F32`
SHA384 | `24105E4CF81EEE31F6F2620FA9E9E6208D35F47B280D4A5E24A797069B178ABAE1E719B8ABBC051791436F1E7CB5E639`
SHA512 | `3EF2B4603908C010B1439DF821622D267AB6C1476753458944528E1B1C992915AFF93D4877C44F99B4A99A1790CAF65D3E1170832D46F636FDC2D4E84CA7E2C9`
SSDEEP | `768:DN3YTAR6SQ7EW0HuqSJRtVtjovmEO9t8lulQt:B3A63yEF9SJRtLjovdO9ClUQt`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: 
rpcping [-t <protseq>] [-s <server_addr>] [-e <endpoint>            
        |-f <interface UUID>[,MajorVer]] [-O <Interface Object UUID]
        [-i <#_iterations>] [-u <security_package_id>] [-a <authn_level>]                             
        [-N <server_princ_name>] [-I <auth_identity>] [-C <capabilities>]
        [-T <identity_tracking>] [-M <impersonation_type>]
        [-S <server_sid>] [-P <proxy_auth_identity>] [-F <RPCHTTP_flags>]
        [-H <RPC/HTTP_authn_schemes>] [-o <binding_options>]
        [-B <server_certificate_subject>] [-b] [-E] [-q] [-c]
        [-A <http_proxy_auth_identity>] [-U <HTTP_proxy_authn_schemes>]
        [-r <report_results_interval>] [-v <verbose_level>] 

Pings a server using RPC. Options are:

-t <protseq> - protocol sequence to use. Can be one of the standard
    RPC protocol sequences - ncacn_ip_tcp, ncacn_np, ncacn_http, etc.
    If not specified, default is ncacn_ip_tcp.
    
-s <server_addr> - the server address. If not specified, the local
    machine will be pinged. E.g. server, server.com, 157.59.244.141
        
-e <endpoint> - the endpoint to ping. If none is specified, the endpoint
    mapper on the target machine will be pinged. This option is mutually
    exclusive with the interface (-f) option.

-o <binding_options> - the binding options for the RPC ping. See the
    MSDN for more details (RpcStringBindingCompose and RPC over HTTP).
    
-f <interface UUID>[,MajorVer] - the interface to ping. This option is
    mutually exclusive with the endpoint option. The interface is specified
    as a UUID. If the MajorVer is not specified, version 1 of the interface
    will be sought. When interface is specified, rpcping will query the
    endpoint mapper on the target machine to retrieve the endpoint for the
    specified interface. The endpoint mapper will be queried using the
    options specified in the command line.
    
-O <Object UUID> - Object Uuid if the interface registerd one.

-i <#_iterations> - number of calls to make. The default is 1. This
    option is useful for measuring connection latency if multiple
    iterations are specified.
    
-u <security_package_id> - the security package (security provider) RPC
    will use to make the call. The security package is identified as a
    number or a name. If a number is used it is the same number as in the
    RpcBindingSetAuthInfoEx API. The table below gives the names and
    numbers. Names are not case sensitive:
        Negotiate - 9 or one of nego, snego or negotiate
        NTLM - 10 or NTLM
        SChannel - 14 or SChannel
        Kerberos - 16 or Kerberos
        Kernel - 20 or Kernel
    If you specify this option you must specify authentication level other
    than none. There is no default for this option. If it is not specified,
    RPC will not use security for the ping.
    
-a <authn_level> - the authentication level to use. Possible values are
    connect, call, pkt, integrity and privacy. If this option is
    specified, the security package id (-u) must also be specified. There
    is no default for this option. If this option is not specified, RPC
    will not use security for the ping.

-N <server_princ_name> - specifies a server principal name. Same semantics
    as the ServerPrincName argument to RpcBindingSetAuthInfoEx. See the
    MSDN for more information on RpcBidningSetAuthInfoEx. This field can be
    used only when authentication level and security package are selected.
    
-I <auth_identity> - allows you to specify alternative identity to connect
    to the server. The identity is in the form user,domain,password where
    the three fields have the obvious meaning. If the user name, domain or
    password have special characters that can be interpreted by the shell
    be sure to enclose the identity in double quotes. You can specify *
    instead of the password and RPC will prompt you to enter the password
    without echoing it on the screen. If this field is not specified, the
    identity of the logged on user will be used. This field can be used
    only when authentication level and security package are selected.
  
-C <capabilities> - a hex bitmask of flags. It has the same meaning as
    the Capabilities field in the RPC_SECURITY_QOS structure described
    in the MSDN. This field can be used only when authentication level and
    security package are selected.
    
-T <identity_tracking> - can be static or dynamic. If not specified,
    dynamic is the default. This field can be used only when authentication
    level and security package are selected.

-M <impersonation_type> - can be anonymous, identify, impersonate or
    delegate. Default is impersonate. This field can be used only when
    authentication level and security package are selected.  

-S <server_sid> - the expected SID of the server. For more information
    see the Sid field in the RPC_SECURITY_QOS structure in the MSDN. Using      
    this option requires Windows .NET Server 2003 or higher. This field can
    be used only when authentication level and security package are
    selected.
    
-Z <effectiveonly> - the EffectiveOnly setting to use.  For more information
    see the EffectiveOnly field in the RPC_SECURITY_QOS structure in MSDN.
    Using this option requires Windows Vista or higher. This field can be
    used only when authentication level and security package are selected.

-D <serversecuritydescriptor> - the security descriptor (in string format)
    of the server when using mutual authentication.  For more information
    see the ServerSecurityDescriptor field in the RPC_SECURITY_QOS structure
    in MSDN. Using this option requires Windows 8 or higher. This field can
    be used only when authentication level and security package are
    selected.

-P <proxy_auth_identity> - specifies the identity to authenticate with to
    the RPC/HTTP proxy. Has the same format as for the -I option. 
    Also, you must specify security package (-u), authentication level 
    (-a), and authentication schemes (-H) in order to use this option.
    
-F <RPCHTTP_flags> - the flags to pass for RPC/HTTP front end
    authentication. The flags may be specified as numbers or names
    The currently recognized flags are:
        Use SSL - 1 or ssl or use_ssl
        Use first auth scheme - 2 or first or use_first
    See the Flags field in RPC_HTTP_TRANSPORT_CREDENTIALS for more 
    information. Also, you must specify security package (-u) and 
    authentication level (-a) in order to use this option.
    
-H <RPC/HTTP_authn_schemes> - the authentication schemes to use for
    RPC/HTTP front end authentication. This option is a list of numerical
    values or names separated by comma. E.g. Basic,NTLM. Recognized values
    are (names are not case sensitive:
        Basic - 1 or Basic
        NTLM - 2 or NTLM
        Certificate - 65536 or Cert
    Also, you must specify security package (-u) and authentication level 
    (-a) in order to use this option.
    
-B <server_certificate_subject> - the server certificate subject. For
    more information, see the ServerCertificateSubject field in the
    RPC_HTTP_TRANSPORT_CREDENTIALS structure in the MSDN. You must use
    SSL for this option to work. Also, you must specify security package 
    (-u) and authentication level (-a) in order to use this option.
    
-b - retrieves the server certificate subject from the certificate sent
    by the server and prints it to a screen or a log file. Valid only when
    the Proxy Echo only option (-E) and the use SSL options are specified.
    Also, you must specify security package (-u) and authentication level 
    (-a) in order to use this option.
    
-R - specifies the HTTP proxy. if it's 'none', we will not use HTTP proxy but
    directly attempt the RPC proxy. the value 'default' means to use the IE
    settings in your client machine. any other value will be treated as the
    explicit HTTP proxy. if you don't specify this flag, the default value
    is assumed, that is, the IE settings are checked. this flag is valid
    only when the -E (Echo Only) flag is enabled.

-E - restricts the ping to the RPC/HTTP proxy only. The ping does not
    reach the server. Useful when trying to establish whether the RPC/HTTP
    proxy is reachable. Also, you must specify security package (-u) and 
    authentication level (-a) in order to use this option. To specify an 
    HTTP proxy, use the -R flag. If an HTTP proxy is specified in the -o 
    flag, this option will be ignored.
 
-q - quiet mode. Does not issue any prompts except for passwords. Assumes
    'Y' response to all queries. Use this option with care.
    
-c - use smart card certificate. RPCPing will prompt user to choose
    smart card.
    
-A <http_proxy_auth_identity> - specifies the identity to authenticate
    with to the HTTP proxy. Has the same format as for the -I option. 
    Also, you must specify authentication schemes (-U), security package 
    (-u) and authentication level (-a) in order to use this option.
    
-U <HTTP_proxy_authn_schemes> - the authentication schemes to use for
    HTTP proxy authentication. This option is a list of numerical
    values or names separated by comma. E.g. Basic,NTLM. Recognized values 
    are (names are not case sensitive:
        Basic - 1 or Basic
        NTLM - 2 or NTLM
    You must specify security package (-u) and authentication level (-a) 
    in order to use this option.

-r <report_results_interval> - if multiple iterations are specified, this
    option will make rpcping display current execution statistics
    periodically instead after the last call. The report interval is given
    in seconds. Default is 15.
    
-v <verbose_level> - tells rpcping how verbose to make the output. Default
    value is 1. 2 and 3 provide more output from rpcping.
       
Example: Find out if your Exchange server that you connect through
RPC/HTTP is accessible:
    rpcping -t ncacn_http -s exchange_server -o RpcProxy=front_end_proxy
        -P "username,domain,*" -H Basic -u NTLM -a connect -F 3
When prompted for the password, enter it. exchange_server is the name of
your exchange server, front_end_proxy is the name of your proxy, username
and domain are your user name and domain as you would enter them in the
Outlook prompt. The other parameters will ask rpcping to ping your
Exchange server in exactly the same way as Outlook will connect to it for
the typical profile.

-p - Prompt for credentials if authentication fails.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RpcPing.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `RpcPing.exe` being misused. While `RpcPing.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rpcping.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rpcping.yml) | `Name: Rpcping.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rpcping.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rpcping.yml) | `  - Command: rpcping -s 127.0.0.1 -e 1234 -a privacy -u NTLM` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rpcping.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rpcping.yml) | `  - Path: C:\Windows\System32\rpcping.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rpcping.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rpcping.yml) | `  - Path: C:\Windows\SysWOW64\rpcping.exe` | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## rpcping

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Confirms the RPC connectivity between the computer running Microsoft Exchange Server and any of the supported Microsoft Exchange Client workstations on the network. This utility can be used to check if the Microsoft Exchange Server services are responding to RPC requests from the client workstations via the network.

### Syntax
```
rpcping [/t <protseq>] [/s <server_addr>] [/e <endpoint>
        |/f <interface UUID>[,Majorver]] [/O <Interface Object UUID]
        [/i <#_iterations>] [/u <security_package_id>] [/a <authn_level>]
        [/N <server_princ_name>] [/I <auth_identity>] [/C <capabilities>]
        [/T <identity_tracking>] [/M <impersonation_type>]
        [/S <server_sid>] [/P <proxy_auth_identity>] [/F <RPCHTTP_flags>]
        [/H <RPC/HTTP_authn_schemes>] [/o <binding_options>]
        [/B <server_certificate_subject>] [/b] [/E] [/q] [/c]
        [/A <http_proxy_auth_identity>] [/U <HTTP_proxy_authn_schemes>]
        [/r <report_results_interval>] [/v <verbose_level>] [/d]
```

##### Parameters

|            Parameter             |                                                                                                                                                                                                                                                                                                                                               Description                                                                                                                                                                                                                                                                                                                                               |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|          /t \<protseq>           |                                                                                                                                                                                                                                                  Specifies the protocol sequence to use. Can be one of the standard RPC protocol sequences, for example: ncacn_ip_tcp, ncacn_np, or ncacn_http.<p>If not specified, default is ncacn_ip_tcp.                                                                                                                                                                                                                                                   |
|        /s \<server_addr>         |                                                                                                                                                                                                                                                                                                            Specifies the server address. If not specified, the local machine will be pinged.                                                                                                                                                                                                                                                                                                            |
|          /e \<endpoint>          |                                                                                                                                                                                                                                                    Specifies the endpoint to ping. If none is specified, the endpoint mapper on the target machine will be pinged.<p>This option is mutually exclusive with the interface (**/f**) option.                                                                                                                                                                                                                                                     |
|      /o \<binding_options>       |                                                                                                                                                                                                                                                                                                                             Specifies the binding options for the RPC ping.                                                                                                                                                                                                                                                                                                                             |
| /f \<interface UUID>[,Majorver]  |                                                                                                            Specifies the interface to ping. This option is mutually exclusive with the endpoint option. The interface is specified as a UUID.<p>if the *Majorver* is not specified, version 1 of the interface will be sought.<p>When interface is specified, **rpcping** will query the endpoint mapper on the target machine to retrieve the endpoint for the specified interface. The endpoint mapper will be queried using the options specified in the command line.                                                                                                             |
|        /O \<Object UUID>         |                                                                                                                                                                                                                                                                                                                       Specifies the object UUID if the interface registered one.                                                                                                                                                                                                                                                                                                                        |
|        /i \<#_iterations>        |                                                                                                                                                                                                                                                                          Specifies the number of calls to make. The default is 1. This option is useful for measuring connection latency if multiple iterations are specified.                                                                                                                                                                                                                                                                          |
|    /u \<security_package_id>     | Specifies the security package (security provider) RPC will use to make the call. The security package is identified as a number or a name. If a number is used it is the same number as in the RpcBindingSetAuthInfoEx API. The list below shows the names and numbers. Names are not case sensitive:<p>-   Negotiate / 9 or one of nego, snego or negotiate<br />-   NTLM / 10 or NTLM<br />-   SChannel / 14 or SChannel<br />-   Kerberos / 16 or Kerberos<br />-   Kernel / 20 or Kernel<br />    if you specify this option, you must specify authentication level other than none. There is no default for this option. If it is not specified, RPC will not use security for the ping. |
|        /a \<authn_level>         |                                                                                                                                                               Specifies the authentication level to use. Possible values are:<p>-   connect<br />-   call<br />-   pkt<br />-   integrity<br />-   privacy<p>if this option is specified, the security package ID (/u) must also be specified. There is no default for this option.<p>if this option is not specified, RPC will not use security for the ping.                                                                                                                                                               |
|     /N \<server_princ_name>      |                                                                                                                                                                                                                                                                                 Specifies a server principal name.<p>This field can be used only when authentication level and security package are selected.                                                                                                                                                                                                                                                                                  |
|       /I \<auth_identity>        |                                                         Allows you to specify alternative identity to connect to the server. The identity is in the form user,domain,password. If the user name, domain, or password have special characters that can be interpreted by the shell, enclose the identity in double quotes. You can specify **\\**\* instead of the password and RPC will prompt you to enter the password without echoing it on the screen. If this field is not specified, the identity of the logged on user will be used.<p>This field can be used only when authentication level and security package are selected.                                                         |
|        /C \<capabilities>        |                                                                                                                                                                                                                                                                                   Specifies a hexadecimal bitmask of flags. This field can be used only when authentication level and security package are selected.                                                                                                                                                                                                                                                                                    |
|     /T \<identity_tracking>      |                                                                                                                                                                                                                                                               Specifies static or dynamic. If not specified, dynamic is the default.<p>This field can be used only when authentication level and security package are selected.                                                                                                                                                                                                                                                                |
|     /M \<impersonation_type>     |                                                                                                                                                                                                                                                           Specifies anonymous, identify, impersonate or delegate. Default is impersonate.<p>This field can be used only when authentication level and security package are selected.                                                                                                                                                                                                                                                           |
|         /S \<server_sid>         |                                                                                                                                                                                                                                                                              Specifies the expected SID of the server.<p>This field can be used only when authentication level and security package are selected.                                                                                                                                                                                                                                                                              |
|    /P \<proxy_auth_identity>     |                                                                                                                                                                                                                              Specifies the identity to authenticate with to the RPC/HTTP proxy. Has the same format as for the /I option. You must specify security package (/u), authentication level (/a), and authentication schemes (/H) in order to use this option.                                                                                                                                                                                                                               |
|       /F \<RPCHTTP_flags>        |                                                                                                                                                                Specifies the flags to pass for RPC/HTTP front end authentication. The flags may be specified as numbers or names The currently recognized flags are:<p>-   Use SSL / 1 or ssl or use_ssl<br />-   Use first auth scheme / 2 or first or use_first<p>You must specify security package (/u) and authentication level (/a) in order to use this option.                                                                                                                                                                 |
|   /H \<RPC/HTTP_authn_schemes>   |                                                                                                                           Specifies the authentication schemes to use for RPC/HTTP front end authentication. This option is a list of numerical values or names separated by comma. Example: Basic,NTLM. Recognized values are (names are not case sensitive):<p>-   Basic / 1 or Basic<br />-   NTLM / 2 or NTLM<br />-   Certificate / 65536 or Cert<p>You must specify security package (/u) and authentication level (/a) in order to use this option.                                                                                                                            |
| /B \<server_certificate_subject> |                                                                                                                                                                                                                                                    Specifies the server certificate subject. You must use SSL for this option to work.<p>You must specify security package (/u) and authentication level (/a) in order to use this option.                                                                                                                                                                                                                                                     |
|                /b                |                                                                                                                                                                                      Retrieves the server certificate subject from the certificate sent by the server and prints it to a screen or a log file. Valid only when the Proxy echo only option (/E) and the use SSL options are specified.<p>You must specify security package (/u) and authentication level (/a) in order to use this option.                                                                                                                                                                                      |
|                /R                |                                                                                                                                                               Specifies the HTTP proxy. If *none*, the RPC proxy is used. The value *default* means to use the IE settings in your client machine. Any other value will be treated as the explicit HTTP proxy. If you do not specify this flag, the default value is assumed, that is, the IE settings are checked. This flag is valid only when the **/E** (echo Only) flag is enabled.                                                                                                                                                                |
|                /E                |                                                                                                                                                     Restricts the ping to the RPC/HTTP proxy only. The ping does not reach the server. Useful when trying to establish whether the RPC/HTTP proxy is reachable. To specify an HTTP proxy, use the /R flag. If an HTTP proxy is specified in the /o flag, this option will be ignored.<p>You must specify security package (/u) and authentication level (/a) in order to use this option.                                                                                                                                                      |
|                /q                |                                                                                                                                                                                                                                                                                 Specifies quiet mode. Does not issue any prompts except for passwords. Assumes *Y* response to all queries. Use this option with care.                                                                                                                                                                                                                                                                                  |
|                /c                |                                                                                                                                                                                                                                                                                                               Use smart card certificate. rpcping will prompt user to choose smart card.                                                                                                                                                                                                                                                                                                                |
|                /A                |                                                                                                                                                                                                                        Specifies the identity with which to authenticate to the HTTP proxy. Has the same format as for the /I option.<p>You must specify authentication schemes (/U), security package (/u) and authentication level (/a) in order to use this option.                                                                                                                                                                                                                         |
|                /U                |                                                                                                                                                  Specifies the authentication schemes to use for HTTP proxy authentication. This option is a list of numerical values or names separated by comma. Example: Basic,NTLM. Recognized values are (names are not case sensitive):<p>-   Basic / 1 or Basic<br />-   NTLM / 2 or NTLM<p>You must specify security package (/u) and authentication level (/a) in order to use this option.                                                                                                                                                  |
|                /r                |                                                                                                                                                                                                                                             if multiple iterations are specified, this option will make **rpcping** display current execution statistics periodically instead after the last call. The report interval is given in seconds. Default is 15.                                                                                                                                                                                                                                              |
|                /v                |                                                                                                                                                                                                                                                                                           Tells **rpcping** how verbose to make the output. Default value is 1. 2 and 3 provide more output from **rpcping**.                                                                                                                                                                                                                                                                                           |
|                /d                |                                                                                                                                                                                                                                                                                                                                   Launches RPC network diagnostic UI.                                                                                                                                                                                                                                                                                                                                   |
|                /p                |                                                                                                                                                                                                                                                                                                                      Specifies to prompt for credentials if authentication fails.                                                                                                                                                                                                                                                                                                                       |
|                /?                |                                                                                                                                                                                                                                                                                                                                  Displays help at the command prompt.                                                                                                                                                                                                                                                                                                                                   |

### Examples
To find out if your Exchange server that you connect through RPC/HTTP is accessible, type:
```
rpcping /t ncacn_http /s exchange_server /o RpcProxy=front_end_proxy /P username,domain,* /H Basic /u NTLM /a connect /F 3
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


