---
title: cipher.exe | File Encryption Utility
excerpt: What is cipher.exe?
---

# cipher.exe 

* File Path: `C:\Windows\SysWOW64\cipher.exe`
* Description: File Encryption Utility

## Hashes

Type | Hash
-- | --
MD5 | `A3630EF795BD7CFC6B2A7371A625A40B`
SHA1 | `6A6B963F96D5471DD971A5945EFC095B82A03596`
SHA256 | `BFFE1B9F0B4139C5FCBF318149E54B71DD53DAECF34D8E1F281549A02DE1F332`
SHA384 | `ABE55BC6AA8EDEB3837410AFD3343BAA203D348BF6668C6DDFBB227D90D4100D292C17C2AF59C7527FE070EFB14DA0EA`
SHA512 | `D2DD6FC5A6C297F721F90B1D2330776BE4B69587ED7B0D12155347D0DD65ABF30AC33E489F5D0C0C75124E224984A3B30EC7A6775AECE91062CFA7641A1FE959`
SSDEEP | `768:jIuxw8oIMaXnge2bDn5RBIM4WXZnuA+ZEYuozDYE:j/x+i3GvBF4ZABozDY`
IMP | `3709556898BEAA4E2B5F857FFA0F54BA`
PESHA1 | `EA15B3BFC3A69CCC93C9828FFA7BF1D358E7FD20`
PE256 | `24A199EFB27A736C5E5BCEA197B1D1A25D27509A911B0529DE57AD1A02972474`

## Runtime Data

### Usage (stdout):
```cmhg
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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\cipher.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CIPHER.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/bffe1b9f0b4139c5fcbf318149e54b71dd53daecf34d8e1f281549a02de1f332/detection/


## Possible Misuse

*The following table contains possible examples of `cipher.exe` being misused. While `cipher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek_susp_kerberos_rc4.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_susp_kerberos_rc4.yml) | `cipher: 'rc4-hmac'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [arcsight-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/arcsight-zeek.yml) | `cipher:`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [arcsight-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/arcsight-zeek.yml) | `#cipher: message`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [arcsight-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/arcsight-zeek.yml) | `#cipher: deviceCustomString4`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `cipher:`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `service=kerberos: kerberos.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `service=ssl: tls.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `kerberos_cipher: kerberos.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `ssl_cipher: tls.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `tls_cipher: tls.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `#cipher: kerberos.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-corelight.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-corelight.yml) | `#cipher: tls.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `cipher: 'zeek.*.cipher'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `kerberos_cipher: zeek.kerberos.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `ssl_cipher: zeek.ssl.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `tls_cipher: zeek.ssl.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `#cipher: zeek.kerberos.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `cipher_alg: zeek.ssh.algorithm.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `#cipher: tls.cipher # Not implemented in Elastic Beats`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `#cipher: zeek.ssl.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `=== XOR cipher keys`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [carbon_tool.py](https://github.com/eset/malware-ioc/blob/master/turla/carbon_tool.py) | `from Crypto.Cipher import CAST`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [carbon_tool.py](https://github.com/eset/malware-ioc/blob/master/turla/carbon_tool.py) | `cipher = CAST.new(key, CAST.MODE_OFB, iv)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [carbon_tool.py](https://github.com/eset/malware-ioc/blob/master/turla/carbon_tool.py) | `data = cipher.encrypt(plaintext)	`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [carbon_tool.py](https://github.com/eset/malware-ioc/blob/master/turla/carbon_tool.py) | `data = cipher.decrypt(ciphertext)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `[-Q cipher \| cipher-auth \| mac \| kex \| key]`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_promethium_neodymium.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_promethium_neodymium.yar) | $s1 = "%s SslHandshakeDone(%d) %d. Secure connection with %s, cipher %s, %d secret bits (%d total), session reused=%s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | $s3 = "Crypto.Cipher.AES(" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## cipher

Displays or alters the encryption of directories and files on NTFS volumes. If used without parameters, **cipher** displays the encryption state of the current directory and any files it contains.

### Syntax

```
cipher [/e | /d | /c] [/s:<directory>] [/b] [/h] [pathname [...]]
cipher /k
cipher /r:<filename> [/smartcard]
cipher /u [/n]
cipher /w:<directory>
cipher /x[:efsfile] [filename]
cipher /y
cipher /adduser [/certhash:<hash> | /certfile:<filename>] [/s:directory] [/b] [/h] [pathname [...]]
cipher /removeuser /certhash:<hash> [/s:<directory>] [/b] [/h] [<pathname> [...]]
cipher /rekey [pathname [...]]
```

#### Parameters

| Parameters | Description |
| ---------- | ----------- |
| /b | Aborts if an error is encountered. By default, **cipher** continues to run even if errors are encountered. |
| /c | Displays information on the encrypted file. |
| /d | Decrypts the specified files or directories. |
| /e | Encrypts the specified files or directories. Directories are marked so that files that are added afterward will be encrypted. |
| /h | Displays files with hidden or system attributes. By default, these files are not encrypted or decrypted. |
| /k | Creates a new certificate and key for use with Encrypting File System (EFS) files. If the **/k** parameter is specified, all other parameters are ignored. |
| /r:`<filename>` [/smartcard] | Generates an EFS recovery agent key and certificate, then writes them to a .pfx file (containing certificate and private key) and  a .cer file (containing only the certificate). If **/smartcard** is specified, it writes the recovery key and certificate to a smart card, and no .pfx file is generated. |
| /s:`<directory>` | Performs the specified operation on all subdirectories in the specified *directory*. |
| /u [/n] |  Finds all encrypted files on the local drive(s). If used with the **/n** parameter, no updates are made. If used without **/n**, **/u** compares the user's file encryption key or the recovery agent's key to the current ones, and updates them if they have changed. This parameter works only with **/n**. |
| /w:`<directory>` | Removes data from available unused disk space on the entire volume. If you use the **/w** parameter, all other parameters are ignored. The directory specified can be located anywhere in a local volume. If it is a mount point or points to a directory in another volume, the data on that volume is removed. |
| /x[:efsfile] [`<FileName>`] | Backs up the EFS certificate and keys to the specified file name. If used with **:efsfile**, **/x** backs up the user's certificate(s) that were used to encrypt the file. Otherwise, the user's current EFS certificate and keys are backed up. |
| /y | Displays your current EFS certificate thumbnail on the local computer. |
| /adduser [/certhash:`<hash>` | /certfile:`<filename>`] |
| /rekey | Updates the specified encrypted file(s) to use the currently configured EFS key. |
| /removeuser /certhash:`<hash>` | Removes a user from the specified file(s). The *Hash* provided for **/certhash** must be the SHA1 hash of the certificate to remove. |
| /? | Displays help at the command prompt. |

#### Remarks

- If the parent directory is not encrypted, an encrypted file could become decrypted when it is modified. Therefore, when you encrypt a file, you should also encrypt the parent directory.

- An administrator can add the contents of a .cer file to the EFS recovery policy to create the recovery agent for users, and then import the .pfx file to recover individual files.

- You can use multiple directory names and wildcards.

- You must put spaces between multiple parameters.

### Examples

To display the encryption status of each of the files and subdirectories in the current directory, type:

```
cipher
```

Encrypted files and directories are marked with an **E**. Unencrypted files and directories are marked with a **U**. For example, the following output indicates that the current directory and all its contents are currently unencrypted:

```
Listing C:\Users\MainUser\Documents\
New files added to this directory will not be encrypted.
U Private
U hello.doc
U hello.txt
```

To enable encryption on the Private directory used in the previous example, type:

```
cipher /e private
```

The following output displays:

```
Encrypting files in C:\Users\MainUser\Documents\
Private             [OK]
1 file(s) [or directorie(s)] within 1 directorie(s) were encrypted.
```

The **cipher** command displays the following output:

```
Listing C:\Users\MainUser\Documents\
New files added to this directory will not be encrypted.
E Private
U hello.doc
U hello.txt
```

Where the **Private** directory is now marked as encrypted.

#### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


