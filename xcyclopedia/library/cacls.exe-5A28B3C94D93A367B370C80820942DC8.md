
# cacls.exe 
* File Path: `C:\Windows\system32\cacls.exe`
* Description: Control ACLs Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `5A28B3C94D93A367B370C80820942DC8`
SHA1 | `1328A9F91A011F707B2C0718EB206CD2DEFA4D7B`
SHA256 | `1E7C610F63BA1E22F8CE1350DF98F0825A4A23328C15928BE67EE6E8B58E0290`
SHA384 | `88EBC5C363B085C9BEED8912537EC008F3D2A4007B937FE44135A8DBF6F09FA6A919F49B58802BF6E87370BB1C7136F6`
SHA415 | `291D9CB617700388F16C202C859A7020CC7F8E1985D96530526404DA4DD4D82EEFF26B5483ECBF01C974BE558D4767530D749B791515B291ABCB09855D94C156`
SSDEEP | `768:5RieH9nlsba7UydioQhMSj6DkPkzixXsLmM+Pu:riUltYyiofSj64PdSmM+Pu`

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


