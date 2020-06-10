
# wecutil.exe 
* File Path: `C:\Windows\SysWOW64\wecutil.exe`
* Description: Event Collector Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `8C57EDDA973FA2C52796FC2C121C13C6`
SHA1 | `37DB72F4ADE2AA206221C322C3B84663AF7E1DFB`
SHA256 | `5EE18D4E09F2188D26AD5D70E2F7CF5FB1D8ED68E43247115E52EE673A110C71`
SHA384 | `DEB95D918D690CC76CA9E1615820CEC2DCF33128D181416C9339F741FA020417B52B50383A7716C3237283A8AF9A6CCC`
SHA415 | `84F90DC88FF1708AEE47A8D1DAE45C4803CEF37B90340E7A5343AF72DBA1993A316A8ABB33AA156FC928ECE6647673792A524984BD0FD5B94A60FCBCD2ECCC7B`
SSDEEP | `1536:iYODAdw2EPr/9J8TIzrfkK3KUGgUIp8yQxWnWDMBrINMv:iY2kEZIIXXcwp8yQxuSuUiv`

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


