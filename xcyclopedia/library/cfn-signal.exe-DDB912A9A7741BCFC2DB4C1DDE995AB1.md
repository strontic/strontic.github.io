---
title: cfn-signal.exe | An EC2 bootstrapper for CloudFormation
excerpt: What is cfn-signal.exe?
---

# cfn-signal.exe 

* File Path: `C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe`
* Description: An EC2 bootstrapper for CloudFormation

## Hashes

Type | Hash
-- | --
MD5 | `DDB912A9A7741BCFC2DB4C1DDE995AB1`
SHA1 | `4FCAA47DEF52FFE798367EE55A4E0DBC7AAE6EC8`
SHA256 | `3CF6F694067887C5A4CBE33B264C14611DC40A2C564236DD94FE051BB719FDC3`
SHA384 | `8FCFBA181158F9BFF35E4F3A608055D591A60508E5A2A31360F4D2357BCF8B3B0E4FC84A62DAFD93B8D083F63149A4DC`
SHA512 | `0433502B43E4405CF835534D2011ECBF47AF044DFC0D333823595038F54EEBECDF3E0B49BE30EA8F257F96C04ED70CF7824A3CC6BE76271DA5983EE6850A4928`
SSDEEP | `768:lvmBjHgTsfkngjjjHV5CpeUe4plNjUq29yj:eLgTsfawh/UXlNjgIj`
IMP | `8571CAA1C1E39E800CB623F4B1D233D9`
PESHA1 | `35516F229CCE1E97218712C847FDA97448343D5A`
PE256 | `D83ADC2B2C55A74162C9D6E248F68C450C4F4EFBF9F5B4D2C51B019C14D309D7`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: cfn-signal.exe [options] [WaitConditionHandle URL]

Options:
  -h, --help            show this help message and exit
  -s SUCCESS, --success=SUCCESS
                        If true, signal success to CloudFormation; if false,
                        signal failure. Default: true
  -i ID, --id=ID        A unique ID to send with the signal
  -e EXIT_CODE, --exit-code=EXIT_CODE
                        Derive success or failure from specified exit code

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

  WaitConditionHandle Signal Options:
    -r REASON, --reason=REASON
                        The reason for success/failure
    -d DATA, --data=DATA
                        Data to include with the WaitCondition signal

  Resource Signal Options:
    --stack=STACK_NAME  A CloudFormation stack
    --resource=LOGICAL_RESOURCE_ID
                        A CloudFormation logical resource ID
    --url=ENDPOINT      The CloudFormation service URL. The endpoint URL must
                        match the region option. Use of this parameter is
                        discouraged.
    --region=REGION     The CloudFormation region. Default: us-east-1.

```

### Usage (stderr):
```cmhg
Error: Invalid WaitConditionHandle URL specified: help

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: cfn-signal.exe
* Product Name: aws-cfn-bootstrap
* Company Name: 
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3cf6f694067887c5a4cbe33b264c14611dc40a2c564236dd94fe051bb719fdc3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe](cfn-elect-cmd-leader.exe-381A030E578E8285BF1F462CC036E4D0.md) | 68
[C:\Program Files\Amazon\cfn-bootstrap\cfn-get-metadata.exe](cfn-get-metadata.exe-AB00AE1FE4E4943F9CCB91C01E1C4F35.md) | 66
[C:\Program Files\Amazon\cfn-bootstrap\cfn-hup.exe](cfn-hup.exe-FC05F4A7EA27BD5F73BE9016B8F70BD9.md) | 58
[C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe](cfn-init.exe-5E0F3A7E9C8313FA6889B824EAB63614.md) | 65
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe](cfn-send-cmd-event.exe-6569521FE751E682B6AF18F84D544079.md) | 68
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe](cfn-send-cmd-result.exe-3F9A3602A5CC3B5C8C8011A9DCB76006.md) | 69
[C:\Program Files\Amazon\cfn-bootstrap\winhup.exe](winhup.exe-48FE04D8A6525EBF39345C41CE0D6842.md) | 65




MIT License. Copyright (c) 2020 Strontic.


