---
title: cfn-elect-cmd-leader.exe | An EC2 bootstrapper for CloudFormation
excerpt: What is cfn-elect-cmd-leader.exe?
---

# cfn-elect-cmd-leader.exe 

* File Path: `C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe`
* Description: An EC2 bootstrapper for CloudFormation

## Hashes

Type | Hash
-- | --
MD5 | `381A030E578E8285BF1F462CC036E4D0`
SHA1 | `D6D51A5096A39A1D4BF34BA759248A82AEEBEDCD`
SHA256 | `BD61C6FBD71679EB9BE6C2554F40262DDE0E5F69D3A51ED6C483541AB6425607`
SHA384 | `6C436F903866C7E372527537B168273B6FB294421FC15DE6A621D74E6EF1F60BD84AF1CAB68B222D078744B5A0B966DC`
SHA512 | `88C45DA414DE77B4E20EE87CC8D798D327DC45FAC0894607CECE170A9B0B571D002DB2C02EEE12DC91E1C966542210BD605D38E3CBB14907570A63BBA33107E3`
SSDEEP | `384:OytbeSasdkBKuZu/snjycBghtrYh8eknggMl4gKg67WhtrjHqC3V5ipeKCXosu5R:BvmBjHgTsfkngjjjHV5ipeXXosuQNO9V`
IMP | `8571CAA1C1E39E800CB623F4B1D233D9`
PESHA1 | `2CB5D3724BC9D000B01FC925AE2A5CDDA0149D7A`
PE256 | `CF03DAE2348B0B633F5ABA4537F1ADA6783670CC5AA7CEFDC0AEA5315A936216`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: cfn-elect-cmd-leader.exe [options]

Options:
  -h, --help            show this help message and exit
  -s STACK_NAME, --stack=STACK_NAME
                        A CloudFormation stack
  -c COMMAND_NAME, --command-name=COMMAND_NAME
                        The command name
  -i INVOCATION_ID, --invocation-id=INVOCATION_ID
                        The invocation ID
  -l LISTENER_ID, --listener-id=LISTENER_ID
                        The listener ID
  -u ENDPOINT, --url=ENDPOINT
                        The CloudFormation service URL. The endpoint URL must
                        match the region option. Use of this parameter is
                        discouraged.
  --region=REGION       The CloudFormation region. Default: us-east-1.
  -v, --verbose         Enables verbose logging

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
Error: You must specify StackName
Usage: cfn-elect-cmd-leader.exe [options]

Options:
  -h, --help            show this help message and exit
  -s STACK_NAME, --stack=STACK_NAME
                        A CloudFormation stack
  -c COMMAND_NAME, --command-name=COMMAND_NAME
                        The command name
  -i INVOCATION_ID, --invocation-id=INVOCATION_ID
                        The invocation ID
  -l LISTENER_ID, --listener-id=LISTENER_ID
                        The listener ID
  -u ENDPOINT, --url=ENDPOINT
                        The CloudFormation service URL. The endpoint URL must
                        match the region option. Use of this parameter is
                        discouraged.
  --region=REGION       The CloudFormation region. Default: us-east-1.
  -v, --verbose         Enables verbose logging

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

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9518_none_08e07c8fa840efbe | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\cfn-bootstrap\_socket.pyd |
C:\Program Files\Amazon\cfn-bootstrap\_ssl.pyd |
C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe |
C:\Program Files\Amazon\cfn-bootstrap\PYTHON27.DLL |
C:\Program Files\Amazon\cfn-bootstrap\select.pyd |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
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

* Status: The file C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: cfn-elect-cmd-leader.exe
* Product Name: aws-cfn-bootstrap
* Company Name: 
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/bd61c6fbd71679eb9be6c2554f40262dde0e5f69d3a51ed6c483541ab6425607/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon\cfn-bootstrap\cfn-get-metadata.exe](cfn-get-metadata.exe-AB00AE1FE4E4943F9CCB91C01E1C4F35.md) | 90
[C:\Program Files\Amazon\cfn-bootstrap\cfn-hup.exe](cfn-hup.exe-FC05F4A7EA27BD5F73BE9016B8F70BD9.md) | 58
[C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe](cfn-init.exe-5E0F3A7E9C8313FA6889B824EAB63614.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe](cfn-send-cmd-event.exe-6569521FE751E682B6AF18F84D544079.md) | 65
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe](cfn-send-cmd-result.exe-3F9A3602A5CC3B5C8C8011A9DCB76006.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe](cfn-signal.exe-DDB912A9A7741BCFC2DB4C1DDE995AB1.md) | 68
[C:\Program Files\Amazon\cfn-bootstrap\winhup.exe](winhup.exe-48FE04D8A6525EBF39345C41CE0D6842.md) | 86




MIT License. Copyright (c) 2020 Strontic.


