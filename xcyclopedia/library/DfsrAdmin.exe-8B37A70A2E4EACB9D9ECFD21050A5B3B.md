
# DfsrAdmin.exe 

* File Path: `C:\Windows\DfsrAdmin.exe`
* Description: DFS Replication Command Line
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8B37A70A2E4EACB9D9ECFD21050A5B3B`
SHA1 | `0FDA13C5713B2774C439DE7DB5121C8EBD950429`
SHA256 | `0BA23072CFA6F3C9DCF809DF261F12D775C51FF6B95C92D96B9BDCF31FC590F9`
SHA384 | `0CF32B770D7CD8E901ADC3B3920694E44BEFF1CAB1F9AC486301CD0DD89D0932B21A560288F33BCAFE8DCA217D52AAE8`
SHA512 | `9D7506B2EE3917029B5AEE055E3F13492DAFCCEB96ABB5BAF522D75E50A439869EB7DCBA5C58EB517053B0F2AD99D57D40D7FA13C10B38A92EB99A195F5A0A4D`
SSDEEP | `3072:RncwuBKkFpSJ8oBgjeCBfzBdYPZs3VDTENpSVwICI+Z:JtTkFpK8IfgdYPZs3VD+ICI`

## Runtime Data

### Usage (stdout):
```Batchfile

Help: 
=== Supported Objects ===
You can perform actions on the following objects:


Bulk          Perform several actions by using a single input
              file              
 
Conn          Perform actions on connections between members of a replication 
              group

Health        Generate a health report for one or more members of a 
              replication group
 
Mem           Perform actions on a member of a replication group

Membership    Perform actions related to a member's participation in a 
              replicated folder

PropRep       Generate propagation report for one or more propagation
              test files
              
PropTest      Generate and drop a propagation test file on a membership, 
              used for testing replication

RF            Perform actions on a folder that is replicated between members
              of a replication group
 
RG    	      Perform actions on a group of computers that participates in
              replication

Sub           Perform actions related to a member's subscription in 
              replication groups

Type "DfsrAdmin <Object> /?" for detailed help.

Usage: DfsrAdmin <Object> <Action> [<SubObject>] [<SubAction>]
       </Parameter:Value> ... [</Optional-Parameter:Value> ...]
       [/Domain:<value>] [/DC:<value>] [/CSV] [/Force]

=== Optional Parameters Supported For All Commands ===
/Domain: Specify the domain for the replication group
/DC:     Specify the domain controller to connect to in the replication 
         group's domain
/Force:  Specify that a failed operation is skipped when an action causes a 
         series of operations to be performed

=== Optional Parameter Supported For All List Commands ===
/CSV:    Dumps the list output in CSV format

```

### Usage (stderr):
```Batchfile

Failed: 
The object -help is not a valid object.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DfsrAdmin.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.2999
* Product Version: 10.0.14393.2999
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.



MIT License. Copyright (c) 2020 Strontic.


