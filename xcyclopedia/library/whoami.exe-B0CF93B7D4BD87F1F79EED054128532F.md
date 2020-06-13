
# whoami.exe 

* File Path: `C:\Windows\SysWOW64\whoami.exe`
* Description: whoami - displays logged on user information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B0CF93B7D4BD87F1F79EED054128532F`
SHA1 | `1D385BBC40537BC8E0257158789284D900802A42`
SHA256 | `72C2B9733D3D143CB23BA5D6F3D5B690D39ED458B6C430557FF7B50FE6C3F28F`
SHA384 | `03E3008303C0446F9B2F2342ABBFD2143A91DCC7A233184C50DAE89FC37754477F2EABBD2FE96FC609C1DA3309D5E502`
SHA512 | `31D779C17F86623F83898C93327EC8BE6224B692362B33585D760ED03363B1FA3D5A0D7D18330309B57F1E4B22672B58D499B18AB1AF0E70D1772F75553B9DB4`
SSDEEP | `768:eZt/YOkQa1f0zf6ehi0n0Um5aOmCuJ4wNdiMmxMu0boJV8LLmHQdw8DXzod+x/Em:It/iQic71sKCJoiK8aL0Yw8w+xcfcnB`

## Runtime Data

### Usage (stdout):
```Batchfile

WhoAmI has three ways of working: 

Syntax 1:
    WHOAMI [/UPN | /FQDN | /LOGONID]

Syntax 2:
    WHOAMI { [/USER] [/GROUPS] [/CLAIMS] [/PRIV] } [/FO format] [/NH]

Syntax 3:
    WHOAMI /ALL [/FO format] [/NH]

Description:
    This utility can be used to get user name and group information
    along with the respective security identifiers (SID), claims,
    privileges, logon identifier (logon ID) for the current user
    on the local system. I.e. who is the current logged on user?
    If no switch is specified, tool displays the user name in NTLM
    format (domain\username).

Parameter List:
    /UPN                    Displays the user name in User Principal 
                            Name (UPN) format.

    /FQDN                   Displays the user name in Fully Qualified 
                            Distinguished Name (FQDN) format.

    /USER                   Displays information on the current user
                            along with the security identifier (SID).

    /GROUPS                 Displays group membership for current user,
                            type of account, security identifiers (SID)
                            and attributes.

    /CLAIMS                 Displays claims for current user,
                            including claim name, flags, type and values.

    /PRIV                   Displays security privileges of the current
                            user.

    /LOGONID                Displays the logon ID of the current user.

    /ALL                    Displays the current user name, groups 
                            belonged to along with the security 
                            identifiers (SID), claims and privileges for 
                            the current user access token.

    /FO       format        Specifies the output format to be displayed.
                            Valid values are TABLE, LIST, CSV.
                            Column headings are not displayed with CSV
                            format. Default format is TABLE.

    /NH                     Specifies that the column header should not
                            be displayed in the output. This is
                            valid only for TABLE and CSV formats.

    /?                      Displays this help message.

Examples:
    WHOAMI
    WHOAMI /UPN
    WHOAMI /FQDN 
    WHOAMI /LOGONID
    WHOAMI /USER
    WHOAMI /USER /FO LIST
    WHOAMI /USER /FO CSV
    WHOAMI /GROUPS
    WHOAMI /GROUPS /FO CSV /NH
    WHOAMI /CLAIMS
    WHOAMI /CLAIMS /FO LIST
    WHOAMI /PRIV
    WHOAMI /PRIV /FO TABLE
    WHOAMI /USER /GROUPS
    WHOAMI /USER /GROUPS /CLAIMS /PRIV
    WHOAMI /ALL
    WHOAMI /ALL /FO LIST
    WHOAMI /ALL /FO CSV /NH
    WHOAMI /?

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "WHOAMI /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: whoami.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# whoami



Displays user, group and privileges information for the user who is currently logged on to the local system. If used without parameters, **whoami** displays the current domain and user name.



## Syntax

```
whoami [/upn | /fqdn | /logonid]
whoami {[/user] [/groups] [/priv]} [/fo <Format>] [/nh]
whoami /all [/fo <Format>] [/nh]
```

### Parameters

|Parameter|Description|
|---------|-----------|
|/upn|Displays the user name in user principal name (UPN) format.|
|/fqdn|Displays the user name in fully qualified domain name (FQDN) format.|
|/logonid|Displays the logon ID of the current user.|
|/user|Displays the current domain and user name and the security identifier (SID).|
|/groups|Displays the user groups to which the current user belongs.|
|/priv|Displays the security privileges of the current user.|
|/fo \<Format>|Specifies the output format. Valid values include:</br>**table** Displays output in a table. This is the default value.</br>**list** Displays output in a list.</br>**csv** Displays output in comma-separated value (CSV) format.|
|/all|Displays all information in the current access token, including the current user name, security identifiers (SID), privileges, and groups that the current user belongs to.|
|/nh|Specifies that the column header should not be displayed in the output. This is valid only for table and CSV formats.|
|/?|Displays help at the command prompt.|

## Examples

To display the domain and user name of the person who is currently logged on to this computer, type:
```
whoami
```
Output similar to the following appears:
```
DOMAIN1\administrator
```
To display all of the information in the current access token, type:
```
whoami /all
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


