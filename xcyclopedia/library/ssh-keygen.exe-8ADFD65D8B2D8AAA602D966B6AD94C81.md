---
title: ssh-keygen.exe | 
excerpt: What is ssh-keygen.exe?
---

# ssh-keygen.exe 

* File Path: `C:\WINDOWS\system32\OpenSSH\ssh-keygen.exe`

## Hashes

Type | Hash
-- | --
MD5 | `8ADFD65D8B2D8AAA602D966B6AD94C81`
SHA1 | `5ADC21A69F41F24B5E7A7ACB95E7DDD62D37B1EC`
SHA256 | `29020DCD18E04213193464EA221E90B22AFB957101E20D466C724B73AE2B4423`
SHA384 | `C5E4512BA7BE2AF28894908E8396EF2CF1EABA412AE1EF45C32FF0EB262A035119B11433DCD57CFC8827B2D87CA7B462`
SHA512 | `07F16DD192AC0642228389C4999611D94123DC478AE88EA1EA79EC39FFED8AA8B5AAEDB298177D438B2522ED7A55B5B097C2EFBCF4EA37C4D1B81B020472FCD3`
SSDEEP | `12288:ye4xnydMvVyE4fnScbYyutbuBA8hQPb2LHCP8:TqrvV3PcMyBe8MqLHC0`
IMP | `3521BE309D673737C666AE104349D5D8`
PESHA1 | `3AB8300E37940AF75D3FDA38F32FD1D25E2AC286`
PE256 | `C1F2EA16206D5E3155147853F59075D82015EB47F8FB8A987D3EBC0F9B057030`

## Runtime Data

### Usage (stdout):
```cmhg
Generating public/private rsa key pair.
Enter file in which to save the key (C:\Users\user/.ssh/id_rsa): 
```

### Usage (stderr):
```cmhg
Too many arguments.
usage: ssh-keygen [-q] [-b bits] [-C comment] [-f output_keyfile] [-m format]
                  [-N new_passphrase] [-t dsa | ecdsa | ed25519 | rsa]
       ssh-keygen -p [-f keyfile] [-m format] [-N new_passphrase]
                   [-P old_passphrase]
       ssh-keygen -i [-f input_keyfile] [-m key_format]
       ssh-keygen -e [-f input_keyfile] [-m key_format]
       ssh-keygen -y [-f input_keyfile]
       ssh-keygen -c [-C comment] [-f keyfile] [-P passphrase]
       ssh-keygen -l [-v] [-E fingerprint_hash] [-f input_keyfile]
       ssh-keygen -B [-f input_keyfile]
       ssh-keygen -D pkcs11
       ssh-keygen -F hostname [-lv] [-f known_hosts_file]
       ssh-keygen -H [-f known_hosts_file]
       ssh-keygen -R hostname [-f known_hosts_file]
       ssh-keygen -r hostname [-g] [-f input_keyfile]
       ssh-keygen -G output_file [-v] [-b bits] [-M memory] [-S start_point]
       ssh-keygen -f input_file -T output_file [-v] [-a rounds] [-J num_lines]
                  [-j start_line] [-K checkpt] [-W generator]
       ssh-keygen -I certificate_identity -s ca_key [-hU] [-D pkcs11_provider]
                  [-n principals] [-O option] [-V validity_interval]
                  [-z serial_number] file ...
       ssh-keygen -L [-f input_keyfile]
       ssh-keygen -A [-f prefix_path]
       ssh-keygen -k -f krl_file [-u] [-s ca_public] [-z version_number]
                  file ...
       ssh-keygen -Q -f krl_file file ...
       ssh-keygen -Y check-novalidate -n namespace -s signature_file
       ssh-keygen -Y sign -f key_file -n namespace file ...
       ssh-keygen -Y verify -f allowed_signers_file -I signer_identity
       		-n namespace -s signature_file [-r revocation_file]

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\OpenSSH\ssh-keygen.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: OpenSSH for Windows
* Company Name: 
* File Version: 8.1.0.1
* Product Version: OpenSSH_8.1p1 for Windows
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/29020dcd18e04213193464ea221e90b22afb957101e20d466c724b73ae2b4423/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenSSH\ssh-keygen.exe](ssh-keygen.exe-F22288EF90CC363E97BDC9261A491EAC.md) | 96

## Possible Misuse

*The following table contains possible examples of `ssh-keygen.exe` being misused. While `ssh-keygen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`1169569d23a1e028d9c6f6e0c4d1ffe6532d0d60` \|ssh-keygen \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH keygen (ssh-keygen)"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


