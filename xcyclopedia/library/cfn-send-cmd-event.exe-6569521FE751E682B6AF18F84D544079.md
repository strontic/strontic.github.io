---
title: cfn-send-cmd-event.exe | An EC2 bootstrapper for CloudFormation
excerpt: What is cfn-send-cmd-event.exe?
---

# cfn-send-cmd-event.exe 

* File Path: `C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe`
* Description: An EC2 bootstrapper for CloudFormation

## Hashes

Type | Hash
-- | --
MD5 | `6569521FE751E682B6AF18F84D544079`
SHA1 | `57BFE6908B56B140DE4EAAEAD4CCD95F71273181`
SHA256 | `320F6D6E4D3317CB7357D1C6315703FD9839D4FCB519C3932640E231DA88C3D5`
SHA384 | `75FE378A41076911B63A78D25207C91FC4B1D9DCE44056E8E32688977A46829D9020A5E72E76656FCB45B6E81F1253BA`
SHA512 | `6DDEB99C268D1BA51C1DB8B5B75677B2A6F88C5AFD3FC983549A524CE5D591A394B6182EA9FF47ACA7E3A6C59E27F4427C1DD7148977D2E86AEC2E5AF67D589B`
SSDEEP | `768:5vmBjHgTsfkngjjjHV5qpe5mUzmpOP4fTaq:KLgTsfawhf5mUzKOP47aq`
IMP | `8571CAA1C1E39E800CB623F4B1D233D9`
PESHA1 | `BF61A4C06813759AF34B4984D41C499D7E4D012A`
PE256 | `663D37D4FC81D66E4031ECF9B0C4073333F91D8EE7CD30B6028D8A6F130D246C`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: cfn-send-cmd-event.exe [options] [Command Event Message]

Options:
  -h, --help            show this help message and exit
  --event-handle=EVENT_HANDLE
                        Event Handle URL
  -e EVENT_ID, --event-id=EVENT_ID
                        An id that uniquely identifies the event for this
                        command and listener
  -t EVENT_TIMESTAMP, --event-timestamp=EVENT_TIMESTAMP
                        The time the event occurred, in ISO 8601 form
  -d DISPATCHER_ID, --dispatcher-id=DISPATCHER_ID
                        The dispatcher ID
  -c COMMAND_NAME, --command-name=COMMAND_NAME
                        The command name
  -i INVOCATION_ID, --invocation-id=INVOCATION_ID
                        The invocation ID
  -l LISTENER_ID, --listener-id=LISTENER_ID
                        The listener ID

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
Traceback (most recent call last):
  File "cfn-send-cmd-event", line 58, in <module>
  File "re.pyc", line 141, in match
TypeError: expected string or buffer

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: cfn-send-cmd-event.exe
* Product Name: aws-cfn-bootstrap
* Company Name: 
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/320f6d6e4d3317cb7357d1c6315703fd9839d4fcb519c3932640e231da88c3d5/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe](cfn-elect-cmd-leader.exe-381A030E578E8285BF1F462CC036E4D0.md) | 65
[C:\Program Files\Amazon\cfn-bootstrap\cfn-get-metadata.exe](cfn-get-metadata.exe-AB00AE1FE4E4943F9CCB91C01E1C4F35.md) | 63
[C:\Program Files\Amazon\cfn-bootstrap\cfn-hup.exe](cfn-hup.exe-FC05F4A7EA27BD5F73BE9016B8F70BD9.md) | 61
[C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe](cfn-init.exe-5E0F3A7E9C8313FA6889B824EAB63614.md) | 68
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe](cfn-send-cmd-result.exe-3F9A3602A5CC3B5C8C8011A9DCB76006.md) | 69
[C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe](cfn-signal.exe-DDB912A9A7741BCFC2DB4C1DDE995AB1.md) | 68
[C:\Program Files\Amazon\cfn-bootstrap\winhup.exe](winhup.exe-48FE04D8A6525EBF39345C41CE0D6842.md) | 65




MIT License. Copyright (c) 2020 Strontic.


