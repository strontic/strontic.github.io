
# wecutil.exe 
* File Path: `C:\Windows\system32\wecutil.exe`
* Description: Event Collector Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `79DB4E860724467CAD0D448B34ED9648`
SHA1 | `C5C96FC7CA4629A057324747E0FCAF8DD2224892`
SHA256 | `789705EBCBBC42C73BB32308CF7D600F99D789DAD08DB6E79C9F7CA4C37AB8E0`
SHA384 | `A2396CF42D8EED5F8A117C5B74676453D364DD4461FF34422F7003AE16038A796747C2D92328802C1B09DC7CC7FEADAE`
SHA415 | `F34EF54E6E64541824978784032A0DA52937DD3D7A8646EED01BA3E530029A458BB2F3C5A17DFC1967163F616569670D56193937BD67A75363A3C489DE5F88AA`
SSDEEP | `1536:Sv88yHaViIRG/ekIGuQoeVMFiDkVvXCObkF/6m7VOc85DfzRVEK3sX2Q:Sv81+SWOuzeaFAIXFb+6EON5DfVVEWI`

## Runtime Data
### Usage (stdout):
```Batchfile
Windows Event Collector Utility

Enables you to create and manage subscriptions to events forwarded from remote
event sources that support WS-Management protocol.

Usage:

You can use either the short (i.e. es, /f) or long (i.e. enum-subscription, /format)
version of the command and option names. Commands, options and option values are
case-insensitive.

(ALL UPPER-CASE = VARIABLE)

wecutil COMMAND [ARGUMENT [ARGUMENT] ...] [/OPTION:VALUE [/OPTION:VALUE] ...]

Commands:

es (enum-subscription)               List existent subscriptions.
gs (get-subscription)                Get subscription configuration.
gr (get-subscriptionruntimestatus)   Get subscription runtime status.
ss (set-subscription)                Set subscription configuration.
cs (create-subscription)             Create new subscription.
ds (delete-subscription)             Delete subscription.
rs (retry-subscription)              Retry subscription.
qc (quick-config)                    Configure Windows Event Collector service.

Common options:

/h|? (help)
Get general help for the wecutil program.

wecutil { -help | -h | -? }

For arguments and options, see usage of specific commands:

wecutil COMMAND -?

```

### Usage (stderr):
```Batchfile
Command help is not supported. Error = 0x57.
The parameter is incorrect.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WECUTIL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


