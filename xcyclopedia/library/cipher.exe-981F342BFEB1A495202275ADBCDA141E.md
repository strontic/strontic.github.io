
# cipher.exe 
* File Path: `C:\Windows\system32\cipher.exe`
* Description: File Encryption Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `981F342BFEB1A495202275ADBCDA141E`
SHA1 | `010960B96FEA177539F4661A311625F4719E5820`
SHA256 | `F2C1D0936204911AB67DEEC718F8136257DDAE477BF56BDEED296D197E8D7215`
SHA384 | `4CF3D9BCDAE0F9EB137AEA28CC2981E414686FFB3700858AD9088E43CC72B87DB838789327F736B31573F6FFAF1BA6BB`
SHA415 | `101E3F9711FC39019806AC8FA56D898BB7231866E9EA6C71BDB0E1DADCA1C3243B67B82F59D5F0AF37FAB9F86D8CE70F5BC79CA9D51EAB47AB3E32E525427173`
SSDEEP | `768:+nIEAyHarnYDRo/k536GbgjvXvvvD73RG7kkXUgwKmbbisev5xjEw4v:6AyHaIr36Gbivv3Im//HqEw4v`

## Runtime Data
### Usage (stdout):
```Batchfile
Displays or alters the encryption of directories [files] on NTFS partitions.

  CIPHER [/E | /D | /C]
         [/S:directory] [/B] [/H] [pathname [...]]

  CIPHER /K [/ECC:256|384|521]

  CIPHER /R:filename [/SMARTCARD] [/ECC:256|384|521]

  CIPHER /P:filename.cer

  CIPHER /U [/N]

  CIPHER /W:directory

  CIPHER /X[:efsfile] [filename]

  CIPHER /Y

  CIPHER /ADDUSER [/CERTHASH:hash | /CERTFILE:filename | /USER:username]
         [/S:directory] [/B] [/H] [pathname [...]]

  CIPHER /FLUSHCACHE [/SERVER:servername]

  CIPHER /REMOVEUSER /CERTHASH:hash
         [/S:directory] [/B] [/H] [pathname [...]]

  CIPHER /REKEY [pathname [...]]

    /B        Abort if an error is encountered. By default, CIPHER continues
              executing even if errors are encountered.
    /C        Displays information on the encrypted file.
    /D        Decrypts the specified files or directories.
    /E        Encrypts the specified files or directories. Directories will be
              marked so that files added afterward will be encrypted. The
              encrypted file could become decrypted when it is modified if the
              parent directory is not encrypted. It is recommended that you
              encrypt the file and the parent directory.
    /H        Displays files with the hidden or system attributes. These files
              are omitted by default.
    /K        Creates a new certificate and key for use with EFS. If this
              option is chosen, all the other options will be ignored.

              Note: By default, /K creates a certificate and key that conform
                    to current group policy. If ECC is specified, a self-signed
                    certificate will be created with the supplied key size.

    /N        This option only works with /U. This will prevent keys being
              updated. This is used to find all the encrypted files on the
              local drives.
    /R        Generates an EFS recovery key and certificate, then writes them
              to a .PFX file (containing certificate and private key) and a
              .CER file (containing only the certificate). An administrator may
              add the contents of the .CER to the EFS recovery policy to create
              the recovery key for users, and import the .PFX to recover
              individual files. If SMARTCARD is specified, then writes the
              recovery key and certificate to a smart card. A .CER file is
              generated (containing only the certificate). No .PFX file is
              generated.

              Note: By default, /R creates an 2048-bit RSA recovery key and
                    certificate. If ECC is specified, it must be followed by a
                    key size of 256, 384, or 521.

    /P        Creates a base64-encoded recovery-policy blob from the passed-in
              certificate. This blob can be used to set DRA policy for
              MDM deployments.
    /S        Performs the specified operation on the given directory and all
              files and subdirectories within it.
    /U        Tries to touch all the encrypted files on local drives. This will
              update user's file encryption key or recovery keys to the current
              ones if they are changed. This option does not work with other
              options except /N.
    /W        Removes data from available unused disk space on the entire
              volume. If this option is chosen, all other options are ignored.
              The directory specified can be anywhere in a local volume. If it
              is a mount point or points to a directory in another volume, the
              data on that volume will be removed.
    /X        Backup EFS certificate and keys into file filename. If efsfile is
              provided, the current user's certificate(s) used to encrypt the
              file will be backed up. Otherwise, the user's current EFS
              certificate and keys will be backed up.
    /Y        Displays your current EFS certificate thumbprint on the local PC.
    /ADDUSER  Adds a user to the specified encrypted file(s). If CERTHASH is
              provided, cipher will search for a certificate with this SHA1
              hash. If CERTFILE is provided, cipher will extract the
              certificate from the file. If USER is provided, cipher will
              try to locate the user's certificate in Active Directory Domain
              Services.
    /FLUSHCACHE
              Clears the calling user's EFS key cache on the specified server.
              If servername is not provided, cipher clears the user's key cache
              on the local machine.
    /REKEY    Updates the specified encrypted file(s) to use the configured
              EFS current key.
    /REMOVEUSER
              Removes a user from the specified file(s). CERTHASH must be the
              SHA1 hash of the certificate to remove.

    directory A directory path.
    filename  A filename without extensions.
    pathname  Specifies a pattern, file or directory.
    efsfile   An encrypted file path.

    Used without parameters, CIPHER displays the encryption state of the
    current directory and any files it contains. You may use multiple directory
    names and wildcards. You must put spaces between multiple parameters.

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

* Original Filename: CIPHER.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


