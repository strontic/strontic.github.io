---
title: iscsicli.exe | iSCSI Discovery tool
---

# iscsicli.exe 

* File Path: `C:\Windows\system32\iscsicli.exe`
* Description: iSCSI Discovery tool

## Hashes

Type | Hash
-- | --
MD5 | `DDD4ADBFC4B3C951084CB5F59D46E7C3`
SHA1 | `66DD269949BC599F5B1ECF9E5EFC1AE280132D39`
SHA256 | `B62ED416F061FBF96185743DE993D0EF17F552C91EFA7D0C1001BBC845A03E97`
SHA384 | `077AFD58C85FA8E7F81C8ED90A4B049F4ED4FE6687EB096D37362B373217BF440CA5A1CB75F187F1CF1B498A9CCD1CB6`
SHA512 | `1D353DDA46892EBE11EAF603A27E4E0F97484BEE9F1BC451FC7F42720D4D8C816961212DD8D1C963794D290846D4FEBA9C7FBCC398A51C8159B030B6312911AF`
SSDEEP | `3072:JCspsGa2SxmsYO2uAICgKOKaeqUKOpVk/qfWJTfS1n37MX:U5eOjYORKRaeqUp3WJrM`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft iSCSI Initiator Version 10.0 Build 17763

iscsicli

iscsicli AddTarget <TargetName> <TargetAlias> <TargetPortalAddress>
                           <TargetPortalSocket> <Target flags>
                           <Persist> <Login Flags> <Header Digest> <Data Digest> 
                           <Max Connections> <DefaultTime2Wait>
                           <DefaultTime2Retain> <Username> <Password> <AuthType>
                           <Mapping Count> <Target Lun> <OS Bus> <Os Target> 
                           <OS Lun> ...

iscsicli RemoveTarget <TargetName> 

iscsicli AddTargetPortal <TargetPortalAddress> <TargetPortalSocket> 
                         [HBA Name] [Port Number]
                         <Security Flags>
                         <Login Flags> <Header Digest> <Data Digest> 
                         <Max Connections> <DefaultTime2Wait>
                        <DefaultTime2Retain> <Username> <Password> <AuthType>

iscsicli RemoveTargetPortal <TargetPortalAddress> <TargetPortalSocket> [HBA Name] [Port Number]

iscsicli RefreshTargetPortal <TargetPortalAddress> <TargetPortalSocket> [HBA Name] [Port Number]

iscsicli ListTargets [ForceUpdate]

iscsicli ListTargetPortals

iscsicli TargetInfo <TargetName> [Discovery Mechanism]

iscsicli LoginTarget <TargetName> <ReportToPNP>
                     <TargetPortalAddress> <TargetPortalSocket>
                     <InitiatorInstance> <Port number> <Security Flags>
                    <Login Flags> <Header Digest> <Data Digest> 
                    <Max Connections> <DefaultTime2Wait>
                    <DefaultTime2Retain> <Username> <Password> <AuthType> <Key>
                    <Mapping Count> <Target Lun> <OS Bus> <Os Target> 
                    <OS Lun> ...

iscsicli LogoutTarget <SessionId>

iscsicli PersistentLoginTarget <TargetName> <ReportToPNP>
                     <TargetPortalAddress> <TargetPortalSocket>
                    <InitiatorInstance> <Port number> <Security Flags>
                    <Login Flags> <Header Digest> <Data Digest> 
                    <Max Connections> <DefaultTime2Wait>
                    <DefaultTime2Retain> <Username> <Password> <AuthType> <Key>
                    <Mapping Count> <Target Lun> <OS Bus> <Os Target> 
                    <OS Lun> ...

iscsicli ListPersistentTargets

iscsicli RemovePersistentTarget <Initiator Name> <TargetName> 
                               <Port Number> 
                               <Target Portal Address> 
                                <Target Portal Socket> 

iscsicli AddConnection <SessionId> <Initiator Instance>
                      <Port Number> <Target Portal Address>
                      <Target Portal Socket> <Security Flags>
                      <Login Flags> <Header Digest> <Data Digest> 
                      <Max Connections> <DefaultTime2Wait>
                      <DefaultTime2Retain> <Username> <Password> <AuthType> <Key>

iscsicli RemoveConnection <SessionId> <ConnectionId> 
iscsicli ScsiInquiry <SessionId> <LUN> <EvpdCmddt> <PageCode>

iscsicli ReadCapacity <SessionId> <LUN>

iscsicli ReportLUNs <SessionId>

iscsicli ReportTargetMappings

iscsicli ListInitiators

iscsicli AddiSNSServer <iSNS Server Address>

iscsicli RemoveiSNSServer <iSNS Server Address>

iscsicli RefreshiSNSServer <iSNS Server Address>

iscsicli ListiSNSServers

iscsicli FirewallExemptiSNSServer

iscsicli NodeName <node name>

iscsicli SessionList <Show Session Info>

iscsicli CHAPSecret <chap secret>

iscsicli TunnelAddr <Initiator Name> <InitiatorPort> <Destination Address> <Tunnel Address> <Persist>

iscsicli GroupKey <Key> <Persist>

iscsicli BindPersistentVolumes

iscsicli BindPersistentDevices

iscsicli ReportPersistentDevices

iscsicli AddPersistentDevice <Volume or Device Path>

iscsicli RemovePersistentDevice <Volume or Device Path>

iscsicli ClearPersistentDevices

iscsicli Ping <Initiator Name> <Address> [Request Count] [Request Size] [Request Timeout]

iscsicli GetPSKey <Initiator Name> <initiator Port> <Id Type> <Id>

iscsicli PSKey <Initiator Name> <initiator Port> <Security Flags> <Id Type> <Id> <Key> <persist>
Quick Commands

iscsicli QLoginTarget <TargetName>  [CHAP Username] [CHAP Password]

iscsicli QAddTarget <TargetName> <TargetPortalAddress>

iscsicli QAddTargetPortal <TargetPortalAddress>
                          [CHAP Username] [CHAP Password]

iscsicli QAddConnection <SessionId> <Initiator Instance>
                        <Target Portal Address>
                        [CHAP Username] [CHAP Password]

Target Mappings:
    <Target Lun> is the LUN value the target uses to expose the LUN.
                 It must be in the form 0x0123456789abcdef
    <OS Bus> is the bus number the OS should use to surface the LUN
    <OS Target> is the target number the OS should use to surface the LUN
    <OS LUN> is the LUN number the OS should use to surface the LUN

Payload Id Type:
    ID_IPV4_ADDR is      1 - Id format is 1.2.3.4
    ID_FQDN is           2 - Id format is ComputerName
    ID_IPV6_ADDR is      5 - Id form is IPv6 Address
Security Flags:
    TunnelMode is          0x00000040
    TransportMode is       0x00000020
    PFS Enabled is         0x00000010
    Aggressive Mode is     0x00000008
    Main mode is           0x00000004
    IPSEC/IKE Enabled is   0x00000002
    Valid Flags is         0x00000001

Login Flags:
    ISCSI_LOGIN_FLAG_REQUIRE_IPSEC                0x00000001
        IPsec is required for the operation

    ISCSI_LOGIN_FLAG_MULTIPATH_ENABLED            0x00000002
        Multipathing is enabled for the target on this initiator

AuthType:
    ISCSI_NO_AUTH_TYPE = 0,
        No iSCSI in-band authentication is used

    ISCSI_CHAP_AUTH_TYPE = 1,
        One way CHAP (Target authenticates initiator is used)

    ISCSI_MUTUAL_CHAP_AUTH_TYPE = 2
        Mutual CHAP (Target and Initiator authenticate each other is used)

Target Flags:
    ISCSI_TARGET_FLAG_HIDE_STATIC_TARGET            0x00000002
        If this flag is set then the target will never be reported unless it
        is also discovered dynamically.

    ISCSI_TARGET_FLAG_MERGE_TARGET_INFORMATION      0x00000004
        If this flag is set then the target information passed will be
        merged with any target information already statically configured for
        the target

CHAP secrets, CHAP passwords and IPSEC preshared keys can be specified as
a text string or as a sequence of hexadecimal values. The value specified on
the command line is always considered a string unless the first two characters
0x in which case it is considered a hexadecimal value.

For example 0x12345678 specifies a 4 byte secret

All numerical values are assumed decimal unless preceeded by 0x. If
preceeded by 0x then value is assumed to be hex

iscsicli can also be run in command line mode where iscsicli commands
can be entered directly from the console. To enter command line
mode, just run iscsicli without any parameters

The operation completed successfully. 

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\iscsicli.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iscsicli.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\iscsicli.exe](iscsicli.exe-518F842EA8449A89448D6754A4AA8AD9.md) | 71
[C:\Windows\system32\iscsicli.exe](iscsicli.exe-5D9CE9006FDE6D04DF8A589897844D4E.md) | 69
[C:\Windows\SysWOW64\iscsicli.exe](iscsicli.exe-256A7F9BA07FA2DE104725F1EF97EE7C.md) | 65
[C:\Windows\SysWOW64\iscsicli.exe](iscsicli.exe-8E8F391704E2A0E15B67740BC79B7B38.md) | 66
[C:\windows\SysWOW64\iscsicli.exe](iscsicli.exe-E14C6ADFC8FE002023459590BFF0009C.md) | 77




MIT License. Copyright (c) 2020 Strontic.


