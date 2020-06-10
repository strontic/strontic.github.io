
# cacls.exe 
* File Path: `C:\WINDOWS\SysWOW64\cacls.exe`
* Description: Control ACLs Program
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `B304B0EF47E125F696425BD99096D3E3`
SHA1 | `494AF17B85558A09C77629B2AC7145A9BBA3AFEC`
SHA256 | `7E32B9948FE3D9C99B34C2A8A6B85A160891C909B7358E2D621F1A40469EE6EA`
SHA384 | `6EDF461BB0BCAE5BA07363781FC9373021CB53C033A7B37592DEF40AE04A81150E3F1C3D23AED861C9E18807D844F726`
SHA415 | `33DB4F1A207762FF7587DA7CB0F366911D18F63998F38D12D2263552E9EFF85BEE47BBB34F0063B95746B2AD8E4E7CE6A8F80D341668E8BFF031A7CA488C872E`
SSDEEP | `384:tSCcR08Y0F7eNrvT4alMzJS5zEtE0HVSwRb1dBt1535RFvZzmi0D+GwNRdWtDWub:mR0F0FoX2zU1QECdRZ7N8D+Gwkf`

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

* Original Filename: CACLS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


