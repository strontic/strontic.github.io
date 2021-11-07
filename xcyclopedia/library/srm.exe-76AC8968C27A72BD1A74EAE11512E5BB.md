---
title: srm.exe | 
excerpt: What is srm.exe?
---

# srm.exe 

* File Path: `C:\Program Files\SplunkUniversalForwarder\bin\srm.exe`

## Hashes

Type | Hash
-- | --
MD5 | `76AC8968C27A72BD1A74EAE11512E5BB`
SHA1 | `20704F98A703D53DE12825B57F4E4C534AACBDB0`
SHA256 | `5B377BE29BF967C798FEE140BD6820B57D63329507A7D7A54A6DAEEE0B0E8D75`
SHA384 | `AC5A8BE57E8C836297936DF3D076F4544CBAD18DB3B8FE433C4F2E017EFBFD4ADD417A8EFB631AD197B5C2A7EF58BC55`
SHA512 | `B7F7A9693DFAF468B1510A5785A23C97D639D0EC35331262AC7C69A883ABDB9A3175C144AA77B7DCAF9827E51B6E48E21FAEEAC90500238098CFB1130662D87B`
SSDEEP | `3072:Jeyy6UWCPF5kkoZvK6vsOBlE5atxIAleGCAsnbIcTT:gy9UWC95noZ3kOBlfKAYv`
IMP | `D86B91708F75DB6CDAE907AADEBFB979`
PESHA1 | `23BCA986A483FA59B70539C15D7E74716B0BB331`
PE256 | `9768841146DEC92EF8BC0B66D54899C5DB4D773D2B20C87934FC6AC83C74422C`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: srm.exe [OPTION]... [FILE]...
Overwrite and remove (unlink) the files.

  -d, --directory       ignored (for compatability with rm(1))
  -f, --force           ignore nonexistant files, never prompt
  -i, --interactive     prompt before any removal
  -s, --simple          overwrite with single pass using 0x00
  -P, --openbsd         overwrite with three passes like OpenBSD rm
  -D, --dod             overwrite with 7 US DoD compliant passes
  -E, --doe             overwrite with 3 US DoE compliant passes
  -r, -R, --recursive   remove the contents of directories
  -v, --verbose         explain what is being done
  -h, --help            display this help and exit
  -V, --version         display version information and exit

```

### Usage (stderr):
```cmhg
C:\Program Files\SplunkUniversalForwarder\bin\srm.exe: invalid option -- e
Try `srm.exe --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\SplunkUniversalForwarder\bin\srm.exe |
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

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/5b377be29bf967c798fee140bd6820b57d63329507a7d7a54a6daeee0b0e8d75/detection





MIT License. Copyright (c) 2020-2021 Strontic.


