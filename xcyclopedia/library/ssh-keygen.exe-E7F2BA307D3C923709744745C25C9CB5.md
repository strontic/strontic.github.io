---
title: ssh-keygen.exe | 
excerpt: What is ssh-keygen.exe?
---

# ssh-keygen.exe 

* File Path: `C:\Windows\system32\OpenSSH\ssh-keygen.exe`

## Hashes

Type | Hash
-- | --
MD5 | `E7F2BA307D3C923709744745C25C9CB5`
SHA1 | `9A58D2AB3681C2DD9DCEB3C497F17966CF8B9B67`
SHA256 | `F647D15BAC7651FB3FC23779D7568F7C14B139745AFF03201EA5F569A7D84810`
SHA384 | `BA21430FD59C29B39E185EACDA530F562B5E524103C3FAAA4E2514731A8B78F6C93413AFD8D0B24BAEA0A0F4867A1D37`
SHA512 | `DB5F7CA98083444D348C7BE8851ECEDA225A06446C4C97323B2A6B3A382CC0867A89CD3EEEEC4A7A1F505B4FC3226D7EB9E002C24785B0E33C936E29CF25D29E`
SSDEEP | `6144:1jOlrq2QzsTMhJoEBA/YF9HE0C09/l760j6qTjhqVSxwn1VU1B8zqcNPaDb2O7fB:1CTOJl+EO0CM/M0+Ck8Bixo0lHCd`
IMP | `643DF7829C13810977871B7A9E601644`
PESHA1 | `970DC5D9DEE15124AB266C6FE37D09E8E1879DF0`
PE256 | `48DE64377C0CB07CA1AF00987DB65A9A4734F6FD5BCE156D8CDACA2D7039D612`

## Runtime Data

### Usage (stdout):
```cmhg
Generating public/private rsa key pair.
Enter file in which to save the key (C:\Users\user/.ssh/id_rsa): 
```

### Usage (stderr):
```cmhg
Too many arguments.
usage: ssh-keygen [-q] [-b bits] [-t dsa | ecdsa | ed25519 | rsa]
                  [-N new_passphrase] [-C comment] [-f output_keyfile]
       ssh-keygen -p [-P old_passphrase] [-N new_passphrase] [-f keyfile]
       ssh-keygen -i [-m key_format] [-f input_keyfile]
       ssh-keygen -e [-m key_format] [-f input_keyfile]
       ssh-keygen -y [-f input_keyfile]
       ssh-keygen -c [-P passphrase] [-C comment] [-f keyfile]
       ssh-keygen -l [-v] [-E fingerprint_hash] [-f input_keyfile]
       ssh-keygen -B [-f input_keyfile]
       ssh-keygen -F hostname [-f known_hosts_file] [-l]
       ssh-keygen -H [-f known_hosts_file]
       ssh-keygen -R hostname [-f known_hosts_file]
       ssh-keygen -r hostname [-f input_keyfile] [-g]
       ssh-keygen -G output_file [-v] [-b bits] [-M memory] [-S start_point]
       ssh-keygen -T output_file -f input_file [-v] [-a rounds] [-J num_lines]
                  [-j start_line] [-K checkpt] [-W generator]
       ssh-keygen -s ca_key -I certificate_identity [-h] [-U]
                  [-D pkcs11_provider] [-n principals] [-O option]
                  [-V validity_interval] [-z serial_number] file ...
       ssh-keygen -L [-f input_keyfile]
       ssh-keygen -A
       ssh-keygen -k -f krl_file [-u] [-s ca_public] [-z version_number]
                  file ...
       ssh-keygen -Q -f krl_file file ...

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: OpenSSH for Windows
* Company Name: 
* File Version: 7.7.2.1
* Product Version: OpenSSH_7.7p1 for Windows
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/f647d15bac7651fb3fc23779d7568f7c14b139745aff03201ea5f569a7d84810/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenSSH\ssh-add.exe](ssh-add.exe-C808CB063C0B78E92FF7F5A85905218D.md) | 21
[C:\Windows\system32\OpenSSH\ssh-agent.exe](ssh-agent.exe-9FFECD197D09FF33B00D5E5B78A48146.md) | 25
[C:\Windows\system32\OpenSSH\ssh-keyscan.exe](ssh-keyscan.exe-4720A475F697D41705EBEECC9812C718.md) | 21

## Possible Misuse

*The following table contains possible examples of `ssh-keygen.exe` being misused. While `ssh-keygen.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor](https://github.com/eset/malware-ioc/blob/master/sshdoor/README.adoc) | `\|`1169569d23a1e028d9c6f6e0c4d1ffe6532d0d60` \|ssh-keygen \|"/usr/share/man/man0/.cache" \|176.9.47.34:28739 \|N/A` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `description = "Signature to match the clean (or not) OpenSSH keygen (ssh-keygen)"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


