---
title: cfn-init.exe | An EC2 bootstrapper for CloudFormation
excerpt: What is cfn-init.exe?
---

# cfn-init.exe 

* File Path: `C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe`
* Description: An EC2 bootstrapper for CloudFormation

## Hashes

Type | Hash
-- | --
MD5 | `5E0F3A7E9C8313FA6889B824EAB63614`
SHA1 | `E7A5B44B8CC5F681C549C97546F37A3F33170566`
SHA256 | `CFBAB698F849F46D68C736AF3AA2BD1A27A16DE772F5A14AAD1A6D7E25475D21`
SHA384 | `B9E858B2D7F64C802138E5149390BF3F7C775B165DC25DA53C5F3F3589B807667F51075EA7406AFC86A4403F5272CCE9`
SHA512 | `D888447F6E65E7A01B3429479F214710D29ED91A8B2B2B2D13C3762455821C5E86211F9F0F9AC60499185D043E6DA2C92C41F2241DF91552A9968EE87A198086`
SSDEEP | `384:eytbeSasdkBKuZu/snjycBghtrYh8eknggMl4gKg67WhtrjHqC3V5/peK9/VNLOq:RvmBjHgTsfkngjjjHV5/pemrL8N8XPB`
IMP | `8571CAA1C1E39E800CB623F4B1D233D9`
PESHA1 | `1C4B8E4500194D8DDFDF050AD17CE70526B1590C`
PE256 | `EDF656D354A1356200FFF432848827A93EF1C55ACEA184C07024C7F617324371`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: cfn-init.exe [options]
  or:  cfn-init.exe [options] <filename>
  or:  cat <filename> | cfn-init.exe [options] -

Options:
  -h, --help            show this help message and exit
  -s STACK_NAME, --stack=STACK_NAME
                        A CloudFormation stack
  -r LOGICAL_RESOURCE_ID, --resource=LOGICAL_RESOURCE_ID
                        A CloudFormation logical resource ID
  -c CONFIGSETS, --configsets=CONFIGSETS
                        An optional list of configSets (default: "default")
  -u ENDPOINT, --url=ENDPOINT
                        The CloudFormation service URL. The endpoint URL must
                        match the region option. Use of this parameter is
                        discouraged.
  --region=REGION       The CloudFormation region. Default: us-east-1.
  -v, --verbose         Enables verbose logging
  --resume              Resume from a previous cfn-init run

  AWS Credentials:
    Options for specifying AWS Account Credentials.

    -f CREDENTIAL_FILE, --credential-file=CREDENTIAL_FILE
                        A credential file, readable only by the owner, with
                        keys 'AWSAccessKeyId' and 'AWSSecretKey'
    --role=IAM_ROLE     An IAM Role
    --access-key=ACCESS_KEY
                        An AWS Access Key
    --secret-key=SECRET_KEY
                        An AWS Secret Key

  Proxy:
    Options for specifying proxies. Format:
    [scheme://][user:password@]host:port

    --http-proxy=HTTP_PROXY
                        A (non-SSL) HTTP proxy
    --https-proxy=HTTPS_PROXY
                        An HTTPS proxy

```

### Usage (stderr):
```cmhg
Unknown error reading from file help

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\cfn-bootstrap\_hashlib.pyd |
C:\Program Files\Amazon\cfn-bootstrap\_socket.pyd |
C:\Program Files\Amazon\cfn-bootstrap\_ssl.pyd |
C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe |
C:\Program Files\Amazon\cfn-bootstrap\PYTHON27.DLL |
C:\Program Files\Amazon\cfn-bootstrap\select.pyd |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\SYSTEM32\CRYPTBASE.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rsaenh.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\System32\WS2_32.dll |
C:\Windows\WinSxS\amd64_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9518_none_08e07c8fa840efbe\MSVCR90.dll |


## Signature

* Status: The file C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: cfn-init.exe
* Product Name: aws-cfn-bootstrap
* Company Name: 
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/cfbab698f849f46d68c736af3aa2bd1a27a16de772f5a14aad1a6d7e25475d21/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe](cfn-elect-cmd-leader.exe-381A030E578E8285BF1F462CC036E4D0.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-get-metadata.exe](cfn-get-metadata.exe-AB00AE1FE4E4943F9CCB91C01E1C4F35.md) | 88
[C:\Program Files\Amazon\cfn-bootstrap\cfn-hup.exe](cfn-hup.exe-FC05F4A7EA27BD5F73BE9016B8F70BD9.md) | 71
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe](cfn-send-cmd-event.exe-6569521FE751E682B6AF18F84D544079.md) | 68
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe](cfn-send-cmd-result.exe-3F9A3602A5CC3B5C8C8011A9DCB76006.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe](cfn-signal.exe-DDB912A9A7741BCFC2DB4C1DDE995AB1.md) | 65
[C:\Program Files\Amazon\cfn-bootstrap\winhup.exe](winhup.exe-48FE04D8A6525EBF39345C41CE0D6842.md) | 86




MIT License. Copyright (c) 2020-2021 Strontic.


