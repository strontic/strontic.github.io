﻿---
title: cipher.exe | File Encryption Utility
excerpt: What is cipher.exe?
---

# cipher.exe 

* File Path: `C:\windows\system32\cipher.exe`
* Description: File Encryption Utility

## Hashes

Type | Hash
-- | --
MD5 | `942FAF084F4417750E5B53613191B1CA`
SHA1 | `D76DF25B12B1325DB796ADA32BE809FD4A8E232F`
SHA256 | `97244ED78DE0EE8D6FB00A67B8720C8DE6FA304A3C4238874E146198202B83CD`
SHA384 | `40379B932B1E2B298F98BAEFCD896ACE6AB7594E5BB6F65012161A2007923DAFAB22F79280D6BEE8EF8212D0B6C43FE4`
SHA512 | `7132398AD91178D034760E9A72CA71E11AB059ED755DCA7FF09E78E60C718FE326A94995CFC3A27A1A307B8E357778EFB246DC8B6EF7350861CFDDEB4757A54A`
SSDEEP | `768:Y8L6XOqJopbDmQAWTvIEA65SnVOX/HXrqRvATt8PRRTvo9WFW7e:Y8bqJ3EApuPXuRvATKpaEA7e`

## Signature

* Status: The file C:\windows\system32\cipher.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CIPHER.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `cipher.exe` being misused. While `cipher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek_susp_kerberos_rc4.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_susp_kerberos_rc4.yml) | `cipher: 'rc4-hmac'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \cipher.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [arcsight-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/arcsight-zeek.yml) | `cipher:`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [arcsight-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/arcsight-zeek.yml) | `#cipher: message`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [arcsight-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/arcsight-zeek.yml) | `#cipher: deviceCustomString4`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-auditbeat-modules-enabled.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-auditbeat-modules-enabled.yml) | `cipher: auditd.data.cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-auditd.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-auditd.yml) | `cipher: cipher`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1486.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1486/T1486.md) | echo "#{pwd_for_encrypted_file}" \| $which_gpg --batch --yes --passphrase-fd 0 --cipher-algo #{encryption_alg} -o #{encrypted_file_path} -c #{input_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
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


