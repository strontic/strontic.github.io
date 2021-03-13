---
title: slmgr.vbs | 
excerpt: What is slmgr.vbs?
---

# slmgr.vbs 

* File Path: `C:\Windows\system32\slmgr.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `3903BCAB32A4A853DFA54962112D4D02`
SHA1 | `BA6433FBA48797CD43463441358004AC81B76A8B`
SHA256 | `95FC646D222D324DB46F603A7F675C329FE59A567ED27FDAED2A572A19206816`
SHA384 | `D76FE47D564F9E306B7CAA2EF9B57B7C37D7A48C0AAEB199D9277B5B124A4E7F5C4EF8ABDFC6D5748329CE2C1D57C2A0`
SHA512 | `DB27B16EC8F8139C44C433D51350FBDA6C8F8113E2E8178FF53298B4DACE5EF93D65D7CC422F5A2D544D053471C36392DA4ACD2B7DA8AF38BB42344DB70DBE0A`
SSDEEP | `1536:CY4NiWnudQV24qf4t0OeJBIGtCnCQf147Xt1wbsSXiMvQiih:CY4h4QAlf4WIICCG14791wXyM4iih`
PESHA1 | `BA6433FBA48797CD43463441358004AC81B76A8B`
PE256 | `95FC646D222D324DB46F603A7F675C329FE59A567ED27FDAED2A572A19206816`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid combination of command parameters.

Windows Software Licensing Management Tool
Usage: slmgr.vbs [MachineName [User Password]] [<Option>]
           MachineName: Name of remote machine (default is local machine)
           User:        Account with required privilege on remote machine
           Password:    password for the previous account

Global Options:
/ipk <Product Key>
    Install product key (replaces existing key)
/ato [Activation ID]
    Activate Windows
/dli [Activation ID | All]
    Display license information (default: current license)
/dlv [Activation ID | All]
    Display detailed license information (default: current license)
/xpr [Activation ID]
    Expiration date for current license state

Advanced Options:
/cpky 
    Clear product key from the registry (prevents disclosure attacks)
/ilc <License file>
    Install license
/rilc 
    Re-install system license files
/rearm 
    Reset the licensing status of the machine
/rearm-app <Application ID>
    Reset the licensing status of the given app
/rearm-sku <Activation ID>
    Reset the licensing status of the given sku
/upk [Activation ID]
    Uninstall product key

/dti [Activation ID]
    Display Installation ID for offline activation
/atp <Confirmation ID> [Activation ID]
    Activate product with user-provided Confirmation ID

Volume Licensing: Key Management Service (KMS) Client Options:
/skms <Name[:Port] | : port> [Activation ID]
    Set the name and/or the port for the KMS computer this machine will use. IPv6 address must be specified in the format [hostname]:port
/ckms [Activation ID]
    Clear name of KMS computer used (sets the port to the default)
/skms-domain <FQDN> [Activation ID]
    Set the specific DNS domain in which all KMS SRV records can be found. This setting has no effect if the specific single KMS host is set via /skms option.
/ckms-domain [Activation ID]
    Clear the specific DNS domain in which all KMS SRV records can be found. The specific KMS host will be used if set via /skms. Otherwise default KMS auto-discovery will be used.
/skhc 
    Enable KMS host caching
/ckhc 
    Disable KMS host caching

Volume Licensing: Token-based Activation Options:
/lil 
    List installed Token-based Activation Issuance Licenses
/ril <ILID> <ILvID>
    Remove installed Token-based Activation Issuance License
/ltc 
    List Token-based Activation Certificates
/fta <Certificate Thumbprint> [<PIN>]
    Force Token-based Activation

Volume Licensing: Key Management Service (KMS) Options:
/sprt <Port>
    Set TCP port KMS will use to communicate with clients
/sai <Activation Interval>
    Set interval (minutes) for unactivated clients to attempt KMS connection. The activation interval must be between 15 minutes (min) and 30 days (max) although the default (2 hours) is recommended.
/sri <Renewal Interval>
    Set renewal interval (minutes) for activated clients to attempt KMS connection. The renewal interval must be between 15 minutes (min) and 30 days (max) although the default (7 days) is recommended.
/sdns 
    Enable DNS publishing by KMS (default)
/cdns 
    Disable DNS publishing by KMS
/spri 
    Set KMS priority to normal (default)
/cpri 
    Set KMS priority to low
/act-type [Activation-Type] [Activation ID]
    Set activation type to 1 (for AD) or 2 (for KMS) or 3 (for Token) or 0 (for all).

Volume Licensing: Active Directory (AD) Activation Options:
/ad-activation-online <Product Key> [Activation Object name]
    Activate AD (Active Directory) forest with user-provided product key
/ad-activation-get-iid <Product Key>
    Display Installation ID for AD (Active Directory) forest
/ad-activation-apply-cid <Product Key> <Confirmation ID> [Activation Object name]
    Activate AD (Active Directory) forest with user-provided product key and Confirmation ID
/ao-list 
    Display Activation Objects in AD (Active Directory)
/del-ao <Activation Object DN | Activation Object RDN>
    Delete Activation Objects in AD (Active Directory) for user-provided Activation Object


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/95fc646d222d324db46f603a7f675c329fe59a567ed27fdaed2a572a19206816/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\slmgr.vbs](slmgr.vbs-3903BCAB32A4A853DFA54962112D4D02.md) | 100

## Possible Misuse

*The following table contains possible examples of `slmgr.vbs` being misused. While `slmgr.vbs` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-ramsay.json](https://github.com/eset/malware-ioc/blob/master/ramsay/misp-ramsay.json) | `"value": "slmgr.vbs",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [ramsay](https://github.com/eset/malware-ioc/blob/master/ramsay/README.adoc) | `slmgr.vbs`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


