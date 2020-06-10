
# wecutil.exe 
* File Path: `C:\WINDOWS\system32\wecutil.exe`
* Description: Event Collector Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `62F0E7169CAEF39317DAF7B09D424254`
SHA1 | `F6AF3517D6EFAEB10D1BE612DA88486C4E856084`
SHA256 | `EDC98AE8985AA1646B5AD1E57586A8D2C6327CE205C920A4DA548976BBB7E124`
SHA384 | `680351FC46269E39694D36F68F879507BAD453B3B35107DC7695275755C1CDEE517775979027F2627D3A9504BCC6B2F0`
SHA415 | `A1E29DC864FEA12CA2FF1E03F80A2752482B522A0B2E7EEF8513251FC27D1020C674989D4F4F319C92E33E5DE6D15D8452529AA38BDB6ADD86D60543CCE212D2`
SSDEEP | `1536:O4LDgo7v7jHtWYVRiXAczHSqM8eG1ZNrhwg8VM+U859GZfpzmJNZyy:O4LDNPHtHXiwoTeG1nNVf+U8LY6Jvt`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WECUTIL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


