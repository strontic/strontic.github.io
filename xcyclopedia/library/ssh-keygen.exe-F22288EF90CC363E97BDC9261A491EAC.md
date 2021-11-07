---
title: ssh-keygen.exe | 
excerpt: What is ssh-keygen.exe?
---

# ssh-keygen.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-keygen.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F22288EF90CC363E97BDC9261A491EAC`
SHA1 | `480A60085924E597F5413D0D0B61B8F0DC269121`
SHA256 | `731BEFCB1A1655FE46EF91B3A02982B71D841E439DE362EF3B1ECA5644FC8DAE`
SHA384 | `442503A01FBBAE94D2EC23E4C101EA2F34B957BBE8E493A82B6B504F8E43BCD4144ADA21DBF0DA64CEF121B1911C8796`
SHA512 | `D65F6F88800DFFD85878EF9888211F5E29E1C8719F5A1E6B2A82857A79E15F1E302B93EF09A330F7A8ED19890A4A26D166B74893F36ECD17575A82706709A2D7`
SSDEEP | `12288:Re4xnydMvVyE4fnScbYyutbuBA8hQPb2L6CP8:kqrvV3PcMyBe8MqL6C0`
IMP | `3521BE309D673737C666AE104349D5D8`
PESHA1 | `851B79ACDCA25A24E3467E0DE11F29356C772CC3`
PE256 | `AC5EFD05768CF71E31C68A1A288B5A84B258A953B7578D98BCCDE23FF612983B`

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
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\OpenSSH\ssh-keygen.exe |


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

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/731befcb1a1655fe46ef91b3a02982b71d841e439de362ef3b1eca5644fc8dae/detection


## Possible Misuse

*The following table contains possible examples of `ssh-keygen.exe` being misused. While `ssh-keygen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`1169569d23a1e028d9c6f6e0c4d1ffe6532d0d60` \|ssh-keygen \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH keygen (ssh-keygen)"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


