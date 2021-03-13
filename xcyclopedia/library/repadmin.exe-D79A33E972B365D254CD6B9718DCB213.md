---
title: repadmin.exe | NT5DS
excerpt: What is repadmin.exe?
---

# repadmin.exe 

* File Path: `C:\Windows\SysWOW64\repadmin.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `D79A33E972B365D254CD6B9718DCB213`
SHA1 | `B4D7614C0568CF16EB09E1CCEC55BE192D50E371`
SHA256 | `6853E4A1D887102DB51E56447DF5D05775D801D52B4886518DD95BF864071E6C`
SHA384 | `D4F8D3DB5E27605E6D56FD8B21F3AA0CCB649E6400DFF29459DC81ADA22FB38D0DDCE520DCF18CD0D853395B389D1B30`
SHA512 | `5221BFD79866F54A475141AB75B05E78FC4A84B6949E9CA171A9C0D959CE35D1D612148D8494550DF74C39F52800A87850571E37A265EC053F10482B5F3834FE`
SSDEEP | `6144:IHTJfoS39xraJenrmUjL6jQvJmT7SLd18dUivN1pYJrf7IK:22jQvJmTWL/iV1pYJI`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: repadmin <cmd> <args> [/u:{domain\user}] [/pw:{password|*}]
                             [/retry[:<retries>][:<delay>]]
                             [/csv]

Use these commands to see the help:

/?          Displays a list of commands available for use in repadmin and their
            description.
/help       Same as /?
/?:<cmd>    Displays the list of possible arguments <args>, appropriate 
            syntaxes and examples for the specified command <cmd>.
/help:<cmd> Same as /?:<cmd>  
/experthelp Displays a list of commands for use by advanced users only.
/listhelp   Displays the variations of syntax available for the DSA_NAME,
            DSA_LIST, NCNAME and OBJ_LIST strings.  
/oldhelp    Displays a list of deprecated commands that still work but
            are no longer supported by Microsoft.
     

Supported <cmd> commands (use /?<cmd> for detailed help):  
     /kcc    Forces the KCC on targeted domain controller(s) to immediately 
             recalculate its inbound replication topology.
             
     /prp    This command allows an admin to view or modify the 
             password replication policy for RODCs.
             
     /queue  Displays inbound replication requests that the  DC needs to issue 
             to become consistent with its source replication partners.

     /replicate  Triggers the immediate replication of the specified directory
             partition to the destination domain controller from the source DC.
             
     /replsingleobj Replicates a single object between any two domain
             controllers that have common directory partitions. 
             
     /replsummary The replsummary operation quickly and concisely summarizes
             the replication state and relative health of a forest.
             
     /rodcpwdrepl Triggers replication of passwords for the specified user(s) 
             from the source (Hub DC) to one or more Read Only DC's.

     /showattr Displays the attributes of an object.
     
     /showobjmeta Displays the replication metadata for a specified object
             stored in Active Directory, such as attribute ID, version 
             number, originating and local Update Sequence Number (USN), and 
             originating server's GUID and Date and Time stamp. 
             
     /showrepl Displays the replication status when specified domain controller
             last attempted to inbound replicate Active Directory partitions.
               
     /showutdvec displays the highest committed Update Sequence Number (USN)
             that the targeted DC's copy of Active Directory shows as 
             committed for itself and its transitive partners. 
     
     /syncall Synchronizes a specified domain controller with all replication
              partners.

Supported additional parameters:

     /u:    Specifies the domain and user name separated by a backslash 
            {domain\user} that has permissions to perform operations in 
            Active Directory. UPN logons not supported.  
                         
     /pw:   Specifies the password for the user name entered with the /u 
            parameter.
                        
     /retry This parameter will cause repadmin to repeat its attempt to bind 
            to the target dc should the first attempt fail with one of the 
            following error status:

            1722 / 0x6ba : "The RPC Server is unavailable"
            1753 / 0x6d9 : "There are no more endpoints available from the 
                            endpoint mapper"
                 
     /csv   Used with /showrepl to output results in comma separated
            value format. See /csvhelp


Note: Most commands take their parameters in the order of "Destination or 
      Target DSA_LIST", then a "Source DSA_NAME" if required, and finally the
      NC or Object DN if required.

	<DSA_NAME> (or <DSA_LIST>) is a Directory Service Agent binding 
        string. For Active Directory Domain Services, this is simply a network
        label (such as a DNS, NetBios, or IP address) of a Domain Controller. 
        For Active Directory Lightweight Directory Services, this must be a 
        network label of the AD LDS server followed by a colon and the LDAP 
        port of the AD LDS instance
            Examples (AD DS):  dc-01
                               dc-01.microsoft.com
            Examples (AD LDS): ad-am-01:2000
                               ad-am-01.microsoft.com:2000

      <Naming Context> is the Distinguished Name of the root of the NC
            Example: DC=My-Domain,DC=Microsoft,DC=Com
Note: Text (Naming Context names, server names, etc) with International or
      Unicode characters will only display correctly if appropriate fonts and
      language support are loaded.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: repadmin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\dcdiag.exe](dcdiag.exe-CA1502D2B3342A4F8890FC8A120E4B32.md) | 35
[C:\Windows\SysWOW64\dsmgmt.exe](dsmgmt.exe-6222DD5B0F8120806673AB634E5844FB.md) | 41




MIT License. Copyright (c) 2020-2021 Strontic.


