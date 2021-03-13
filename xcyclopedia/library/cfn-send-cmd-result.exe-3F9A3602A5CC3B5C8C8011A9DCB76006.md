---
title: cfn-send-cmd-result.exe | An EC2 bootstrapper for CloudFormation
excerpt: What is cfn-send-cmd-result.exe?
---

# cfn-send-cmd-result.exe 

* File Path: `C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe`
* Description: An EC2 bootstrapper for CloudFormation

## Hashes

Type | Hash
-- | --
MD5 | `3F9A3602A5CC3B5C8C8011A9DCB76006`
SHA1 | `5B28ED5CFC49F1C761DDF3CD4FCCC0B80C8A2720`
SHA256 | `0500B21DA4072CE70F932B24DFE5422C1B120096E5DB1D9BD8376273D11943F1`
SHA384 | `33206B00D68A5772CD3C0AB43BA822EA0FB6393A671851357005F1DE0BC055243DACDDCBBB96F36E0617F835D406FE04`
SHA512 | `C24C4273BB8AE443F716C11214E67B73563D0E88005174837B71ED39974F0491A4CAE0DCF8A6DDFEB2EB65C94CB5EB624CB8C4088CFF82D8CC94A09141BE900E`
SSDEEP | `384:uytbeSasdkBKuZu/snjycBghtrYh8eknggMl4gKg67WhtrjHqC3V5lpeKn7DQx7F:hvmBjHgTsfkngjjjHV5lpeFx7Pp2Oaja`
IMP | `8571CAA1C1E39E800CB623F4B1D233D9`
PESHA1 | `8563E2EE39BC6E708CF5982EA02D3BF325D810AF`
PE256 | `E96BE5365C98168B2D4E1582872BF8778999AEC55DE67BCF125C657E928CF5F2`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: cfn-send-cmd-result.exe [options] [Command Result Data]

Options:
  -h, --help            show this help message and exit
  --access-key=ACCESS_KEY
                        An AWS Access Key
  --secret-key=SECRET_KEY
                        An AWS Secret Key
  --token=SECURITY_TOKEN
                        An AWS Session Token
  -q QUEUE_URL, --queue-url=QUEUE_URL
                        SQS Queue URL for storing the command result
  -d DISPATCHER_ID, --dispatcher-id=DISPATCHER_ID
                        The dispatcher ID
  -c COMMAND_NAME, --command-name=COMMAND_NAME
                        The command name
  -i INVOCATION_ID, --invocation-id=INVOCATION_ID
                        The invocation ID
  -l LISTENER_ID, --listener-id=LISTENER_ID
                        The listener ID
  -s SUCCESS, --success=SUCCESS
                        If true, signal success; if false, signal failure.
                        Default: true
  -e EXIT_CODE, --exit-code=EXIT_CODE
                        Derive success or failure from specified exit code.
                        Note: This takes precedence over the success flag

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
Error: You must specify DispatcherId
Usage: cfn-send-cmd-result.exe [options] [Command Result Data]

Options:
  -h, --help            show this help message and exit
  --access-key=ACCESS_KEY
                        An AWS Access Key
  --secret-key=SECRET_KEY
                        An AWS Secret Key
  --token=SECURITY_TOKEN
                        An AWS Session Token
  -q QUEUE_URL, --queue-url=QUEUE_URL
                        SQS Queue URL for storing the command result
  -d DISPATCHER_ID, --dispatcher-id=DISPATCHER_ID
                        The dispatcher ID
  -c COMMAND_NAME, --command-name=COMMAND_NAME
                        The command name
  -i INVOCATION_ID, --invocation-id=INVOCATION_ID
                        The invocation ID
  -l LISTENER_ID, --listener-id=LISTENER_ID
                        The listener ID
  -s SUCCESS, --success=SUCCESS
                        If true, signal success; if false, signal failure.
                        Default: true
  -e EXIT_CODE, --exit-code=EXIT_CODE
                        Derive success or failure from specified exit code.
                        Note: This takes precedence over the success flag

  Proxy:
    Options for specifying proxies. Format:
    [scheme://][user:password@]host:port

    --http-proxy=HTTP_PROXY
                        A (non-SSL) HTTP proxy
    --https-proxy=HTTPS_PROXY
                        An HTTPS proxy

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: cfn-send-cmd-result.exe
* Product Name: aws-cfn-bootstrap
* Company Name: 
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/0500b21da4072ce70f932b24dfe5422c1b120096e5db1d9bd8376273d11943f1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe](cfn-elect-cmd-leader.exe-381A030E578E8285BF1F462CC036E4D0.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-get-metadata.exe](cfn-get-metadata.exe-AB00AE1FE4E4943F9CCB91C01E1C4F35.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-hup.exe](cfn-hup.exe-FC05F4A7EA27BD5F73BE9016B8F70BD9.md) | 61
[C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe](cfn-init.exe-5E0F3A7E9C8313FA6889B824EAB63614.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe](cfn-send-cmd-event.exe-6569521FE751E682B6AF18F84D544079.md) | 69
[C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe](cfn-signal.exe-DDB912A9A7741BCFC2DB4C1DDE995AB1.md) | 69
[C:\Program Files\Amazon\cfn-bootstrap\winhup.exe](winhup.exe-48FE04D8A6525EBF39345C41CE0D6842.md) | 90




MIT License. Copyright (c) 2020-2021 Strontic.


