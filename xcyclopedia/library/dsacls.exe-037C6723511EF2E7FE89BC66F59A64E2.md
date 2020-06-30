---
title: dsacls.exe | DS Control ACLs Program
---

# dsacls.exe 

* File Path: `C:\Windows\SysWOW64\dsacls.exe`
* Description: DS Control ACLs Program
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `037C6723511EF2E7FE89BC66F59A64E2`
SHA1 | `666655445FE81AD48C0B10A19407C5FA9E0AE0EF`
SHA256 | `1329D6C387F7C614C48CCE6B1348F967F8F90D510D87D52D7A021A10CFFFE880`
SHA384 | `9CFAAB8A913380EEDE54496309FDBCFBFEE748FEA57A9539E26B81C4BE0C9171D873157551977D5047AB069DABB2D237`
SHA512 | `029CAF3450ABE964F86BBFB31957B612CD7757DA180185542B6E0298A138CF9254E4AF28A2FD5D2F12311B673B6959DC5766CC83833514E840DC4A605D650010`
SSDEEP | `768:eoO2E1olUkH+zlFBNXlBaEHsBV76kxf9g0FcoXs3+ridglivVtyf2MFq5eJ4qfGF:eK+c+zlFzXlBaEGd6kxFg0FZMXwFDJ4C`

## Runtime Data

### Usage (stdout):
```Batchfile
Parameter -help was unexpected.
Displays or modifies permissions (ACLS) of an Active Directory Domain Services (AD DS)
Object

DSACLS object [/I:TSP] [/N] [/P:YN] [/G <group/user>:<perms> [...]]
              [/R <group/user> [...]] [/D <group/user>:<perms> [...]]
              [/S] [/T] [/A] [/resetDefaultDACL] [/resetDefaultSACL]
              [/takeOwnership] [/user:<userName>] [/passwd:<passwd> | *]
              [/simple]

   object           Path to the AD DS object for which to display or
                    manipulate the ACLs

   Path is the RFC 1779 format of the name, as in

       CN=John Doe,OU=Software,OU=Engineering,DC=Widget,DC=com

   A specific AD DS can be denoted by prepending \\server[:port]\
   to the object, as in

        \\ADSERVER\CN=John Doe,OU=Software,OU=Engineering,DC=Widget,DC=US

   no options       displays the security on the object.

   /I               Inheritance flags:
                        T: This object and sub objects
                        S: Sub objects only
                        P: Propagate inheritable permissions one level only.

   /N               Replaces the current access on the object, instead of
                    editing it.

   /P               Mark the object as protected
                       Y:Yes
                       N:No
                    If /P option is not present, current protection flag is
                    maintained.

   /G  <group/user>:<perms>
                    Grant specified group (or user) specified permissions.
                    See below for format of <group/user> and <perms>

   /D  <group/user>:<perms>
                    Deny specified group (or user) specified permissions.
                    See below for format of <group/user> and <perms>

   /R  <group/user> Remove all permissions for the specified group (or user).
                    See below for format of <group/user>

   /S               Restore the security on the object to the default for
                    that object class as defined in AD DS Schema. This option
                    works when dsacls is bound to NTDS. To restore default
                    ACL of an object in AD LDS use /resetDefaultDACL and
                    /resetDefaultSACL options.

   /T               Restore the security on the tree of objects to the
                    default for the object class.
                    This switch is valid only with the /S option.

   /A               When displaying the security on an AD DS
                    object, display the auditing information as well as
                    the permissions and ownership information.

  /resetDefaultDACL Restore the DACL on the object to the default for
                    that object class as defined in AD DS Schema.

  /resetDefaultSACL Restore the SACL on the object to the default for
                    that object class as defined in AD DS Schema.

  /takeOwnership    Take ownership of the object.

  /domain:<domainName> Connect to ldap server using this domain account
                       of the user.

  /user:<userName>  Connect to ldap server using this user name. If this
                    option is not used dsacls will bind as the currently
                    logged on user, using SSPI.

  /passwd:<passwd> | * Passwd for the user account.

  /simple           Bind to server using ldap simple bind. Note that the
                    clear text password will be sent over the wire.

   <user/group> should be in the following forms:
                group@domain or domain\group
                user@domain or domain\user
                FQDN of the user or group
                A string SID

   <perms> should be in the following form:

        [Permission bits];[Object/Property];[Inherited Object Type]

        Permission bits can have the following values concatenated together:

        Generic Permissions
            GR      Generic Read
            GE      Generic Execute
            GW      Generic Write
            GA      Generic All

       Specific Permissions
            SD      Delete
            DT      Delete an object and all of it's children
            RC      Read security information
            WD      Change security information
            WO      Change owner information
            LC      List the children of an object

            CC      Create child object
            DC      Delete a child object
                    For these two permissions, if [Object/Property] is
                    not specified to define a specific child object type,
                    they apply all types of child objects otherwise they
                    apply to that specific child object type.

            WS      Write To Self (also known as Validated Write). There
                    are 3 kinds of validated writes:
                       Self-Membership (bf9679c0-0de6-11d0-a285-00aa003049e2)
                       applied to Group object. It allows updating membership
                       of a group in terms of adding/removing to its own account. 
                    Example: (WS; bf9679c0-0de6-11d0-a285-00aa003049e2; AU)
                    applied to group X, allows an Authenticated User to 
                    add/remove oneself to/from group X, but not anybody else.
                       Validated-DNS-Host-Name (72e39547-7b18-11d1-adef-00c04fd8d5cd)
                       applied to computer object. It allows updating the 
                       DNS host name attribute that is compliant with the
                       computer name & domain name.
                       Validated-SPN (f3a64788-5306-11d1-a9c5-0000f80367c1)
                       applied to computer object: It allows updating the SPN
                       attribute that is compliant to the DNS host name of the
                       computer.
            WP      Write property
            RP      Read property
                    For these two permissions, if [Object/Property] is not
                    specified to define a specific property, they apply to
                    all properties of the object otherwise they apply to that
                    specific property of the object.

            CA      Control access right
                    For this permission, if [Object/Property] is not specified
                    to define the specific "extended right" for control access,
                    it applies to all control accesses meaningful on the
                    object, otherwise it applies to the specific extended right
                    for that object.

            LO      List the object access.  Can be used to grant
                    list access to a specific object if
                    List Children (LC) is not granted to the parent as
                    well can denied on specific objects to hide those objects
                    if the user/group has LC on the parent.
                    NOTE:  AD DS does NOT enforce this permission
                    by default, it has to be configured to start checking for
                    this permission.

        [Object/Property]
        must be the display name of the object type or the property.
        for example "user" is the display name for user objects and
        "telephone number" is the display name for telephone number property.

        [Inherited Object Type]
        must be the display name of the object type that the permissions
        are expected to be inherited to. The permissions MUST be Inherit Only.

        NOTE: This must only be used when defining object specific permissions
        that override the default permissions defined in the AD DS schema for that
        object type.  USE THIS WITH CAUTION and ONLY IF YOU UNDERSTAND object
        specific permissions.


        Examples of a valid <perms> would be:

        SDRCWDWO;;user
        means:
        Delete, Read security information, Change security information and
        Change ownership permissions on objects of type "user".


        CCDC;group;
        means:
        Create child and Delete child permissions to create/delete objects
        of type group.

        RPWP;telephonenumber;
        means:
        read property and write property permissions on telephone number
        property

You can specify more than one user in a command.
The command completed successfully

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DSACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


