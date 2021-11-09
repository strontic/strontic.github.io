---
title: iscsicli.exe | iSCSI Discovery tool
excerpt: What is iscsicli.exe?
---

# iscsicli.exe 

* File Path: `C:\WINDOWS\system32\iscsicli.exe`
* Description: iSCSI Discovery tool

## Hashes

Type | Hash
-- | --
MD5 | `104A2B620480D11E1B593DD2E238E17D`
SHA1 | `5EC5E47FC8A33BAED70970F6F7171D9145788938`
SHA256 | `6438A99752207735D8D5B1A4E1B71E3C0B3447FCB0CABDDE79CE62D5D02750B6`
SHA384 | `991FCF0DE582E60B156665D559D4FA8CF676B0A290E7C650EA0B588B67F14326C85332DBD3EB9392941A64DEB47D7EBA`
SHA512 | `58F1BE5D501918453AF76AE452A52EDE75891CFA3D35DC1B0E14C84579FDEF1EA9AC03DE711CAD85E0184A4190CB9BEC43196F4E845F5F11B4142CAD9A42B8A5`
SSDEEP | `1536:G9MglwlwsILaECDDX6sibPusRUk5is32rq:ShlSZECDDXkjusRUR4sq`
IMP | `028C14ACF014C0D70B45E3DF78F2A400`
PESHA1 | `CEBDA9B1E929F09C03AAFF2E2A4ADFD44D6C79AB`
PE256 | `B89C3297CEC0DFD935F6A5180A03AEC4FC7CBC75141F6922EBCF5EB0BC3FA821`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft iSCSI Initiator Version 10.0 Build 22000

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
C:\WINDOWS\system32\iscsicli.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iscsicli.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/6438a99752207735d8d5b1a4e1b71e3c0b3447fcb0cabdde79ce62d5d02750b6/detection





MIT License. Copyright (c) 2020-2021 Strontic.


