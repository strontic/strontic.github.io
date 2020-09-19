---
title: nvspinfo.exe | "nvspinfo.PROGRAM"
---

# nvspinfo.exe 

* File Path: `C:\Windows\system32\nvspinfo.exe`
* Description: "nvspinfo.PROGRAM"

## Hashes

Type | Hash
-- | --
MD5 | `FE1FA5CBAB26DE105DB01ADCB1B254DC`
SHA1 | `D7BB3F150BD9C02C219681E3907F7149379EEF89`
SHA256 | `461BED0C59B3C815E8D0CBF8728D86D977520381BEC611A3792967847F67515A`
SHA384 | `0CB5B35106D337CA348063E4928DEEDED8FBF3CC694E141DE71F68F9692844BF42F580B33B94F8B58C29CA03062061DC`
SHA512 | `40F55B173C0AFC9AEED26DF58FD561C4F04BA38D793B9D5CC93EB5C136C80965CE134A0F0EC6A4CEAEC223EAC702412A08F345B9512B42572AD00369426298CA`
SSDEEP | `1536:VVpmx+8QfAl4kFNrCr3Cj181i1SdryEFd7dTlwgn+1A1ZJ23dJRaemtIXPkXfV67:ltfAl4knrS3Cj181i1SdryEFd7dTlwg2`

## Runtime Data

### Usage (stdout):
```cmhg
Known VmSwitch versions up to : 14.0
       Found VmSwitch version : 14.0
Feature (1) VmsCapabilityFeatureExtensibilityStackBypass is found
    "Can bypass extensibility stack for host vNICs"
Feature (2) VmsCapabilityFeatureUntrustedGuestIsolation is found
    "Can isolate untrusted VMs from cache attacks on host"
Feature (3) VmsCapabilityFeaturePacketTracking is found
    "Can track where packets have been within vmswitch"
Feature (4) VmsCapabilityFeatureNblOobIndicateUncachedData is found
    "Marks NBL as fully shadowed using bits in FORWARDING_EXTENSION"
Feature (5) VmsCapabilityFeatureSuspendedLiveMigration is found
    "Can support suspended live migration for port redirection"
Feature (6) VmsCapabilityFeatureIndependentHostSpreading is found
    "Can support independent host spreading when RSS is disabled in guest"
Feature (8) VmsCapabilityFeatureVersionedIoctl is found
    "IOCTL buffers start with header meta data"
Feature (9) VmsCapabilityFeatureQueryVlanInfo is found
    "Returns VLAN information"
Feature (10) VmsCapabilityFeatureSoftwareRscOnPhysicalNic is found
    "Can perform Software RSC over physical NIC"
Feature (11) VmsCapabilityFeatureLightweightMiniports is found
    "Supports device-less host MINIPORTs"
Feature (12) VmsCapabilityFeatureDisableVmNicIM is found
    "Supports disabling vmbus monitored notifications to vmNIC"
Fix (0) VmsCapabilityFixDirectOidCompletion is found
    "Direct OID completion"
Fix (1) VmsCapabilityFixExtensibilityStackBypass is found
    "Can bypass extensibility stack for host vNICs (a feature)"
Fix (2) VmsCapabilityFixAzureVrssExtendedParameters is found
    "Can address default object by management tools (e.g. vmmqctrl)"
Capability 1, size 20
Capability 2, size 24
Capability 3, size 24
Capability 4, size 24
Capability 5, size 24
Capability 6, size 20

Adapters:
'WAN Miniport (PPTP)' 'ms_pptpminiport'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_PPTPMINIPORT'
InstanceGuid = {07778D0D-8072-45DA-AD2050B687DFCFE7}

'Hyper-V Virtual Switch Extension Adapter' 'vms_vsmp'
'Hyper-V Virtual Switch Extension Adapter'
st=00000000 ch=00000009
PnpDevNodeId = 'ROOT\VMS_VSMP\0000'
InstanceGuid = {1F15E625-8166-4648-9D35856CF9BF48D7}

'Intel(R) 82599 Virtual Function' 'pci\ven_8086&dev_10ed'
st=00000000 ch=00000084
PnpDevNodeId = 'PCI\VEN_8086&DEV_10ED&SUBSYS_00000000&REV_01\3&267a616a&1&18'
InstanceGuid = {2370E472-86BF-4AB1-BEF87FBCDD897CE6}

'WAN Miniport (SSTP)' 'ms_sstpminiport'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_SSTPMINIPORT'
InstanceGuid = {4F014D41-56C5-4A9E-ADC8E15E604E951B}

'Hyper-V Virtual Ethernet Adapter' 'vms_mp'
'Hyper-V Virtual Ethernet Adapter'
st=00000000 ch=00000081
PnpDevNodeId = 'ROOT\VMS_MP\0000'
InstanceGuid = {5DD47A8D-A76C-468D-B7FA98D2772480BA}

'WAN Miniport (PPPOE)' 'ms_pppoeminiport'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_PPPOEMINIPORT'
InstanceGuid = {65B7DDC4-8E8B-45E6-B17B716CE7D4781C}

'Microsoft Kernel Debug Network Adapter' 'root\kdnic'
st=00000000 ch=00000009
PnpDevNodeId = 'ROOT\KDNIC\0000'
InstanceGuid = {82D00445-1AAE-424B-98E19F57B24A6942}

'WAN Miniport (IPv6)' 'ms_ndiswanipv6'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_NDISWANIPV6'
InstanceGuid = {859349DA-DE97-4389-853FB1459E2476E5}

'WAN Miniport (GRE)' 'ms_greminiport'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_GREMINIPORT'
InstanceGuid = {94D43713-638C-4B28-86D5C397AFFD18C0}

'WAN Miniport (IKEv2)' 'ms_agilevpnminiport'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_AGILEVPNMINIPORT'
InstanceGuid = {A7AA4452-F7FA-407B-898CDBD68B960889}

'WAN Miniport (L2TP)' 'ms_l2tpminiport'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_L2TPMINIPORT'
InstanceGuid = {A951F303-77C1-45DB-92029A4A72E3361E}

'WAN Miniport (IP)' 'ms_ndiswanip'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_NDISWANIP'
InstanceGuid = {C5C17198-661C-412F-AA94C2D56FDF97BB}

'WAN Miniport (Network Monitor)' 'ms_ndiswanbh'
st=00000000 ch=00000009
PnpDevNodeId = 'SWD\MSRRAS\MS_NDISWANBH'
InstanceGuid = {D05FCCD4-B0A2-4E77-98E13C4B59C30806}

'AWS PV Network Device' 'xenvif\ven_xs0001&dev_net&rev_00000000'
st=00000000 ch=00000084
PnpDevNodeId = 'XENVIF\VEN_XS0001&DEV_NET&REV_0000000B\0'
InstanceGuid = {FBFD7ADC-7EA2-4F8A-A0961490AA1D5E80}


cleaning up...finished

```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: "nvspinfo.PROGRAM"
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\nvspinfo.exe](nvspinfo.exe-37A0B6BB41B2F8C10C8B601C1B919936.md) | 47




MIT License. Copyright (c) 2020 Strontic.


