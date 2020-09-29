---
title: logoncli.dll | Net Logon Client DLL
excerpt: What is logoncli.dll?
---

# logoncli.dll 

* File Path: `C:\Windows\SysWOW64\logoncli.dll`
* Description: Net Logon Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `138871DBE68D0696D3D7FA91BC2873B1`
SHA1 | `5D2C526E6121BC222D6B88F9162F457833CDE1B1`
SHA256 | `9AC16F12023BE5F0049C9D30E86E45D65515F406269FF8821B49CDC8F03FB1DF`
SHA384 | `5E50481FC5944F4263EC5CDDB0ED8473CECD6012E813A91901EEE382195A8442231D8C09876EBB194342FD3F5AC282A6`
SHA512 | `E433DC37A671CE1AFD8491903E7A1E74EA8F292891AC5D6308D324FEB73D93A1E16F04A5D1CE083CF7F7BA8EFDAC0F3A64F4D0825D66FE3B5A228FB500A85B96`
SSDEEP | `3072:4zNbamfqW49Wv5AU/aQD6bcChD0hdBCFXYh74XWKLCUHqVzAEOAMl:oNb89IfibThDGBFh7CLCUsOF`
IMP | `F440C693555032D2E14DD32A58C326B9`
PESHA1 | `2CCB7D1B3294B552FE237DB2C56E3B6C4D02A18E`
PE256 | `6833934F17592DB8A4995069A7E2867608EFF31AFD5E0A4187E9BDE5478C40DB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AuthzrExtAccessCheck` | 1 (0x1) | Exported Function | 0x10024ad0 | 0x00024ad0
`I_NetQuerySecureChannelDCInfo` | 57 (0x39) | Exported Function | 0x10020490 | 0x00020490
`I_NetLogonUasLogon` | 56 (0x38) | Exported Function | 0x1001f550 | 0x0001f550
`I_NetLogonUasLogoff` | 55 (0x37) | Exported Function | 0x1001f4e0 | 0x0001f4e0
`I_NetLogonSendToSam` | 54 (0x36) | Exported Function | 0x1001f460 | 0x0001f460
`I_NetLogonSamLogonWithFlags` | 53 (0x35) | Exported Function | 0x1001f390 | 0x0001f390
`I_NetLogonSamLogonEx` | 52 (0x34) | Exported Function | 0x1001f2b0 | 0x0001f2b0
`I_NetLogonSamLogon` | 51 (0x33) | Exported Function | 0x1001f1e0 | 0x0001f1e0
`I_NetLogonSamLogoff` | 50 (0x32) | Exported Function | 0x1001f160 | 0x0001f160
`I_NetlogonGetTrustRid` | 71 (0x47) | Exported Function | 0x10020b60 | 0x00020b60
`I_NetLogonGetDomainInfo` | 49 (0x31) | Exported Function | 0x100203f0 | 0x000203f0
`I_NetLogonGetCapabilities` | 48 (0x30) | Exported Function | 0x10020370 | 0x00020370
`I_NetLogonControl2` | 46 (0x2e) | Exported Function | 0x10020210 | 0x00020210
`I_NetLogonControl` | 47 (0x2f) | Exported Function | 0x100202f0 | 0x000202f0
`I_NetlogonComputeServerSignature` | 70 (0x46) | Exported Function | 0x10020ae0 | 0x00020ae0
`I_NetlogonComputeServerDigest` | 69 (0x45) | Exported Function | 0x10020a70 | 0x00020a70
`I_NetlogonComputeClientSignature` | 68 (0x44) | Exported Function | 0x100209f0 | 0x000209f0
`I_NetlogonComputeClientDigest` | 67 (0x43) | Exported Function | 0x10020980 | 0x00020980
`I_NetServerAuthenticate` | 60 (0x3c) | Exported Function | 0x10020600 | 0x00020600
`I_NetServerAuthenticate2` | 58 (0x3a) | Exported Function | 0x10020500 | 0x00020500
`I_NetServerAuthenticate3` | 59 (0x3b) | Exported Function | 0x10020580 | 0x00020580
`I_NetServerGetTrustInfo` | 61 (0x3d) | Exported Function | 0x10020680 | 0x00020680
`NlBindingRemoveServerFromCache` | 84 (0x54) | Exported Function | 0x1001f850 | 0x0001f850
`NlBindingAddServerToCache` | 83 (0x53) | Exported Function | 0x1001f680 | 0x0001f680
`NetRemoveServiceAccount` | 82 (0x52) | Exported Function | 0x10021170 | 0x00021170
`NetQueryServiceAccount` | 81 (0x51) | Exported Function | 0x100210d0 | 0x000210d0
`NetLogonSetServiceBits` | 80 (0x50) | Exported Function | 0x10020cd0 | 0x00020cd0
`NetLogonGetTimeServiceParentDomain` | 79 (0x4f) | Exported Function | 0x10020c60 | 0x00020c60
`NetIsServiceAccount` | 78 (0x4e) | Exported Function | 0x10021080 | 0x00021080
`NetGetDCName` | 77 (0x4d) | Exported Function | 0x1001e450 | 0x0001e450
`I_NetGetForestTrustInformation` | 45 (0x2d) | Exported Function | 0x10020190 | 0x00020190
`NetGetAnyDCName` | 76 (0x4c) | Exported Function | 0x1001e3e0 | 0x0001e3e0
`NetEnumerateServiceAccounts` | 74 (0x4a) | Exported Function | 0x10020fd0 | 0x00020fd0
`NetAddServiceAccount` | 73 (0x49) | Exported Function | 0x10020f60 | 0x00020f60
`I_RpcExtInitializeExtensionPoint` | 72 (0x48) | Exported Function | 0x10013bd0 | 0x00013bd0
`I_NetServerTrustPasswordsGet` | 66 (0x42) | Exported Function | 0x10020900 | 0x00020900
`I_NetServerReqChallenge` | 65 (0x41) | Exported Function | 0x10020890 | 0x00020890
`I_NetServerPasswordSet2` | 63 (0x3f) | Exported Function | 0x10020790 | 0x00020790
`I_NetServerPasswordSet` | 64 (0x40) | Exported Function | 0x10020810 | 0x00020810
`I_NetServerPasswordGet` | 62 (0x3e) | Exported Function | 0x10020710 | 0x00020710
`NetEnumerateTrustedDomains` | 75 (0x4b) | Exported Function | 0x10020bd0 | 0x00020bd0
`I_NetGetDCList` | 44 (0x2c) | Exported Function | 0x1001ca50 | 0x0001ca50
`I_NetExtendMachinePasswordExpirationTimeout` | 43 (0x2b) | Exported Function | 0x10020130 | 0x00020130
`I_NetDatabaseSync2` | 41 (0x29) | Exported Function | 0x10020120 | 0x00020120
`DsGetDcNameW` | 19 (0x13) | Exported Function | 0x100102e0 | 0x000102e0
`DsGetDcNameA` | 18 (0x12) | Exported Function | 0x1001d510 | 0x0001d510
`DsGetDcCloseW` | 17 (0x11) | Exported Function | 0x1001d4f0 | 0x0001d4f0
`DsEnumerateDomainTrustsW` | 16 (0x10) | Exported Function | 0x1001fe50 | 0x0001fe50
`DsEnumerateDomainTrustsA` | 15 (0xf) | Exported Function | 0x1001fa30 | 0x0001fa30
`DsDeregisterDnsHostRecordsW` | 14 (0xe) | Exported Function | 0x1001f9b0 | 0x0001f9b0
`DsDeregisterDnsHostRecordsA` | 13 (0xd) | Exported Function | 0x1001f910 | 0x0001f910
`DsAddressToSiteNamesW` | 12 (0xc) | Exported Function | 0x1001d390 | 0x0001d390
`DsGetDcNameWithAccountA` | 20 (0x14) | Exported Function | 0x1001d540 | 0x0001d540
`DsAddressToSiteNamesExW` | 11 (0xb) | Exported Function | 0x1001d180 | 0x0001d180
`DsAddressToSiteNamesA` | 9 (0x9) | Exported Function | 0x1001cd10 | 0x0001cd10
`AuthzrExtModifyClaims` | 8 (0x8) | Exported Function | 0x10024e60 | 0x00024e60
`AuthzrExtInitializeRemoteResourceManager` | 7 (0x7) | Exported Function | 0x10024d70 | 0x00024d70
`AuthzrExtInitializeContextFromSid` | 6 (0x6) | Exported Function | 0x10024ce0 | 0x00024ce0
`AuthzrExtInitializeCompoundContext` | 5 (0x5) | Exported Function | 0x10024c50 | 0x00024c50
`AuthzrExtGetInformationFromContext` | 4 (0x4) | Exported Function | 0x10024be0 | 0x00024be0
`AuthzrExtFreeResourceManager` | 3 (0x3) | Exported Function | 0x10024bc0 | 0x00024bc0
`AuthzrExtFreeContext` | 2 (0x2) | Exported Function | 0x10024b40 | 0x00024b40
`DsAddressToSiteNamesExA` | 10 (0xa) | Exported Function | 0x1001cee0 | 0x0001cee0
`NlBindingSetAuthInfo` | 85 (0x55) | Exported Function | 0x1001f890 | 0x0001f890
`DsGetDcNameWithAccountW` | 21 (0x15) | Exported Function | 0x100108e0 | 0x000108e0
`DsGetDcNextW` | 23 (0x17) | Exported Function | 0x1001da00 | 0x0001da00
`I_NetDatabaseSync` | 42 (0x2a) | Exported Function | 0x10020100 | 0x00020100
`I_NetDatabaseRedo` | 40 (0x28) | Exported Function | 0x10020110 | 0x00020110
`I_NetDatabaseDeltas` | 39 (0x27) | Exported Function | 0x10020100 | 0x00020100
`I_NetChainSetClientAttributes2` | 37 (0x25) | Exported Function | 0x10020000 | 0x00020000
`I_NetChainSetClientAttributes` | 38 (0x26) | Exported Function | 0x10020080 | 0x00020080
`I_NetAccountSync` | 36 (0x24) | Exported Function | 0x1001fff0 | 0x0001fff0
`I_NetAccountDeltas` | 35 (0x23) | Exported Function | 0x1001fff0 | 0x0001fff0
`I_DsUpdateReadOnlyServerDnsRecords` | 34 (0x22) | Exported Function | 0x1001e360 | 0x0001e360
`DsGetDcNextA` | 22 (0x16) | Exported Function | 0x1001d910 | 0x0001d910
`DsValidateSubnetNameW` | 33 (0x21) | Exported Function | 0x1001e1f0 | 0x0001e1f0
`DsMergeForestTrustInformationW` | 31 (0x1f) | Exported Function | 0x1001ffb0 | 0x0001ffb0
`DsGetSiteNameW` | 30 (0x1e) | Exported Function | 0x1001e040 | 0x0001e040
`DsGetSiteNameA` | 29 (0x1d) | Exported Function | 0x1001dfc0 | 0x0001dfc0
`DsGetForestTrustInformationW` | 28 (0x1c) | Exported Function | 0x1001ff30 | 0x0001ff30
`DsGetDcSiteCoverageW` | 27 (0x1b) | Exported Function | 0x1001de20 | 0x0001de20
`DsGetDcSiteCoverageA` | 26 (0x1a) | Exported Function | 0x1001dc40 | 0x0001dc40
`DsGetDcOpenW` | 25 (0x19) | Exported Function | 0x1001db90 | 0x0001db90
`DsGetDcOpenA` | 24 (0x18) | Exported Function | 0x1001dad0 | 0x0001dad0
`DsValidateSubnetNameA` | 32 (0x20) | Exported Function | 0x1001e1b0 | 0x0001e1b0
`NlSetDsIsCloningPDC` | 86 (0x56) | Exported Function | 0x1001e630 | 0x0001e630


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LOGONCLI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/9ac16f12023be5f0049c9d30e86e45d65515f406269ff8821b49cdc8f03fb1df/detection/


## Possible Misuse

*The following table contains possible examples of `logoncli.dll` being misused. While `logoncli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `- 'logoncli.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


