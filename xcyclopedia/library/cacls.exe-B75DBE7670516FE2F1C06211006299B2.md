
# cacls.exe 
* File Path: `C:\WINDOWS\system32\cacls.exe`
* Description: Control ACLs Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `B75DBE7670516FE2F1C06211006299B2`
SHA1 | `787DEEEEC2690EE3264E4A283193EFF8E5E37C3E`
SHA256 | `D134EB94124645E73C9BF7F97A834A6E6261D2890CC9BD11A75A34F4E16E812C`
SHA384 | `2D4A97A4A6E2677D1F4F29828868489777ED29F1A9DE03DE4CAAE20FC1A3DE72A2F2BE98B1FBF1AB6DD460C39ED29FF3`
SHA415 | `215046CE99E4DFE2645F9DBC230BB29891B3AE985882419738BDE15024E41B5B19110A14DA6F0118A72F270A218C87378C7213DD69B0024C1BBEE6B3252D6353`
SSDEEP | `768:462i0EvHYstIAp5m8ubMFdQDpRuvu0tiPbND+G4bU:b2ibbIA3m8rFaDp820kxD+GuU`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


