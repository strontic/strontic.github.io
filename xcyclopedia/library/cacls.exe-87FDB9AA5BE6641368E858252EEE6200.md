
# cacls.exe 
* File Path: `C:\Windows\SysWOW64\cacls.exe`
* Description: Control ACLs Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `87FDB9AA5BE6641368E858252EEE6200`
SHA1 | `9761D36F8EC5D019D3D60FA6E9F8950AB2CA0938`
SHA256 | `AA37A9CA5BF8823635BCE909C8D3BD97CD44080A20D1CD7E1C4DD4C85BAC25D0`
SHA384 | `B0A0469A94DE4C464A73E43299214810A3B6DCCE301CB418ACC3C334D4D6822140B8845318F89A1AB18EBB265D1D48D4`
SHA415 | `39B9FDB433E8049BDE2EB9706C60613753E4B972640FDBAAD450B48C9E8AABE26C8B907FF9424C974032AC1DB617344752823ECF6EC584F97CEFDD03DC3F55D3`
SSDEEP | `768:5X/pSxwCXPUnA9j6pYE40NYV59V6mf+We9br:5PpSVXPJ9miE40NQ59Qmf+We9br`

## Runtime Data
### Usage (stdout):
```Batchfile

 NOTE: Cacls is now deprecated, please use Icacls.

 Displays or modifies access control lists (ACLs) of files

 CACLS filename [/T] [/M] [/L] [/S[:SDDL]] [/E] [/C] [/G user:perm]
        [/R user [...]] [/P user:perm [...]] [/D user [...]]
    filename      Displays ACLs.
    /T            Changes ACLs of specified files in
                  the current directory and all subdirectories.
    /L            Work on the Symbolic Link itself versus the target
    /M            Changes ACLs of volumes mounted to a directory
    /S            Displays the SDDL string for the DACL.
    /S:SDDL       Replaces the ACLs with those specified in the SDDL string
                  (not valid with /E, /G, /R, /P, or /D).
    /E            Edit ACL instead of replacing it.
    /C            Continue on access denied errors.
    /G user:perm  Grant specified user access rights.
                  Perm can be: R  Read
                               W  Write
                               C  Change (write)
                               F  Full control
    /R user       Revoke specified user's access rights (only valid with /E).
    /P user:perm  Replace specified user's access rights.
                  Perm can be: N  None
                               R  Read
                               W  Write
                               C  Change (write)
                               F  Full control
    /D user       Deny specified user access.
 Wildcards can be used to specify more than one file in a command.
 You can specify more than one user in a command.

 Abbreviations:
    CI - Container Inherit.
         The ACE will be inherited by directories.
    OI - Object Inherit.
         The ACE will be inherited by files.
    IO - Inherit Only.
         The ACE does not apply to the current file/directory.
    ID - Inherited.
         The ACE was inherited from the parent directory's ACL.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


