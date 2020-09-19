---
title: repadmin.exe | NT5DS
---

# repadmin.exe 

* File Path: `C:\Windows\system32\repadmin.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `951B223D0B582BF2B5ED27EF3130F7BF`
SHA1 | `DABB07956989DBE9465D260D3CA7B9B2AB6234A3`
SHA256 | `28BB5CA1A5F618C10BD3C8B8B646E3AE0B9BFB7D2E03F2C36F52A185816FB882`
SHA384 | `DF9AA2BDE96D1EDEDFADBCB7BF8CAE20F98FB987DE5D9CD358C0F0CA01B368C84B1E0F0CD190160D8BE7FAECC4C1016D`
SHA512 | `B426713E906F4E427085F67AA2019C53C7AEABA960E9BF8CC893C18765C8097F32CDFC6C4CBDE9EEB2EF112E9FC6C414A181B57AC75CCA2259467EE9AC777292`
SSDEEP | `6144:C2NlFYp/PK8VscuLMo705tTaFH8NwZaWc52oRkWUCQeV:CUlqvVKLMo7WDUN`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\repadmin.exe |


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
[C:\Windows\system32\dcdiag.exe](dcdiag.exe-7936349C0FD5FEF9317F678460C78707.md) | 35
[C:\Windows\system32\dsmgmt.exe](dsmgmt.exe-F268289F96C350F9CDA9B5AB39448E4E.md) | 40




MIT License. Copyright (c) 2020 Strontic.


