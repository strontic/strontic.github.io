---
title: iscsicli.exe | iSCSI Discovery tool
excerpt: What is iscsicli.exe?
---

# iscsicli.exe 

* File Path: `C:\Windows\system32\iscsicli.exe`
* Description: iSCSI Discovery tool

## Hashes

Type | Hash
-- | --
MD5 | `87EA97EDF96EEFE4DB352CB584E6AC07`
SHA1 | `3EF9C8EF289C38BB8BD6011A67691A54CBCB2405`
SHA256 | `BDCECA674699354DD54A9C3C2481FF9C1B947132C348DE135CC7EDEEA452B524`
SHA384 | `FE1458237F9BA8E0FEAA064B9EA38582E8EC249490954C5184607567495BD4C8159A88B1F7C02B7233D4896E2DEFE705`
SHA512 | `93DB8CB3F0C49FCB90CD39B1CAF4D4F8BA1F9D22F24E5C3100889258EFC2E20B81969A52944CC52285A87D1822C72EF7A9FA0BCEEA9BB12C746B304425E64B7C`
SSDEEP | `1536:QJHREH44NN63rS+PYbX7XDB9F3KyqacVubBkks2NztFxUJr23NrJn:lHHN67SlrWalbBx3PoaNJn`
IMP | `028C14ACF014C0D70B45E3DF78F2A400`
PESHA1 | `3845245FA3154707290B7AE634B2AFB1915FD4BF`
PE256 | `79450F263AE26B8F8740239DD0AEC4F44DBFDA178FDB1D537F9F00DE2262C35D`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft iSCSI Initiator Version 10.0 Build 19041

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

* Original Filename: iscsicli.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/bdceca674699354dd54a9c3c2481ff9c1b947132c348de135cc7edeea452b524/detection





MIT License. Copyright (c) 2020 Strontic.


