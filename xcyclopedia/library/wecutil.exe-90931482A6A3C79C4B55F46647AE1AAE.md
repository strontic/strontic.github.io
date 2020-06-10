
# wecutil.exe 
* File Path: `C:\WINDOWS\SysWOW64\wecutil.exe`
* Description: Event Collector Command Line Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `90931482A6A3C79C4B55F46647AE1AAE`
SHA1 | `330C23EE21394E25BA45C9788A1D1B723646D503`
SHA256 | `F9F9DB493A29FAF1763852696562DB8F2E5A4F3256F6D51197123E2AAF28FF65`
SHA384 | `0B20D88CC7AA36B2397CAECE70A7985C051A56CB5145C196BB3C142F82AEFD4B4B16ADA0A227AB261448F01F2DDCDADC`
SHA415 | `FE14F9C25E8C72D5ACE2FFE44923112E6CDC9FE8E1287FABA1A9EF1F97E18208F009EB50DD65A78566A3DFED75D43C01ACC9E67F6CC8C651588E596B43F8709C`
SSDEEP | `1536:R+kv3FHuPc9KvslKGVwXA4hjH6974KMWlC:R+k/Fu0EvIKGV14hjH6xzBlC`

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


