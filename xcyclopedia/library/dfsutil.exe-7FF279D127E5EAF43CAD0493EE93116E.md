---
title: dfsutil.exe | DfsUtil - Dfs Administration Utility
excerpt: What is dfsutil.exe?
---

# dfsutil.exe 

* File Path: `C:\Windows\system32\dfsutil.exe`
* Description: DfsUtil - Dfs Administration Utility

## Hashes

Type | Hash
-- | --
MD5 | `7FF279D127E5EAF43CAD0493EE93116E`
SHA1 | `D6031E88400785602AD501E213CA2553267501E8`
SHA256 | `8950BE62E6B782A5188507C136525F06F94A44E6C057AE7DB14A43CBC71AE760`
SHA384 | `652795800F46B5EA1D866ED7EF5D17C248F686E70CD70A7157C2434CEC34BCD34FC408C646DD5B04564B1214A5034F13`
SHA512 | `F7F94AABB6555A1343F9A78D0D96968F61DF74B88EA2CBE9196E5940C3141F878F205F762D507A9386DB71EB21AA0CD39D0D1DE3CD1A78EC80C5C1F32187F582`
SSDEEP | `3072:njwkbncLsHW7BkDFKrSUTOQ+DvHK4a3MeNOApxOOY/hLlj1Zs2FrolC:nsUnA1BkDFwd+HK4aceMhZFrol`

## Runtime Data

### Usage (stdout):
```cmhg
Unrecognized option "h"

USAGE:
Dfsutil is an administrative tool to perform operations on DFS namespaces.

Usage:
dfsutil [/OPTIONS]

    /Root:<DfsName> /View [/Verbose]
    /Root:<DfsName> /Export:<File> [/Verbose]
    /Root:<DfsName> /Import:<File> /Set|Merge|Compare [/Verbose] [/NoBackup]

    /Root:<DfsName> /Import:<File> /BlobSize
    /Root:<DfsName> /ImportRoot:<MasterDfsName> /Mirror|Compare
                    [/Verbose] [/NoBackup]

    /Server:<MachineName> /View
    /Domain:<DomainName> /View    
    
    /AddFtRoot /Server:<ServerName> /Share:<ShareName> /Comment:<Comment>
    /AddStdRoot /Server:<ServerName> /Share:<ShareName> /Comment:<Comment>
    /RemStdRoot /Server:<ServerName> /Share:<ShareName>
    /RemFtRoot /Server:<ServerName> /Share:<ShareName>
    /RemFtRoot:<RootName> /Server:<ServerName> /Share:<ShareName>
    /AddLink /Path:<DfsPath> /Server:<LinkTargetServer> /Share:<TargetShare> /Comment:<Comment>
    /RemoveLink /Path:<DfsPath> /Server:<LinkTargetServer> /Share:<TargetShare>

    /SiteName:<MachineName or IpAddress> 
    /DisplayDfsPath:<DfsPath>   

    /<Command> /? - Detailed usage information for specific command
    
    -----------Advanced Commands -----------------------------------------
    /UnmapFtRoot /Root:<DfsName> /Server:<RootTargetServer> /Share:<ReplicaShare>
    /Clean /Server:<ServerName> /Share:<ShareName>

    /Root:<DfsName> /SiteCosting /Enable|Disable|Display [/Verbose]
    /Root:<DfsName> /RootScalability /Enable|Disable|Display [/Verbose]
    /Path:<DfsPath> /InSite /Enable|Disable|Display [/Verbose]
    /Path:<DfsPath> /TargetFailback /Enable|Disable|Display [/Verbose]
    /Path:<DfsPath> /TargetPriority /Server:<TargetServerName> /Share:<TargetShare>
                    [/Display] [/Set] [/PriorityRank:<Rank>] 
                    [/PriorityClass:<SiteCostNormal|GlobalHigh|SiteCostHigh|SiteCostLow|GlobalLow>]
                    [/Verbose]
    /Path:<DfsPath> /State /Server:<RootOrLinkTargetServer> /Share:<TargetShare> /Enable|Disable|Display [/Verbose]
    /Path:<DfsPath> {/TTL:<Timeout> /Set}|{/TTL /Display} [/Verbose]

    /ViewDfsDirs:<VolumeName> [/RemoveReparse]  [/Verbose]
    -----------Registry Related Commands ---------------------------------
    /SiteCostedReferrals[:<Value>] /Server:<Name> /Display|/Set
    /LdapTimeoutValueInSeconds[:<Value>] /Server:<Name> /Display|/Set
    /InsiteReferrals[:<Value>] /Server:<Name> /Display|/Set
    /DfsDnsConfig[:<Value>] /Server:<Name> /Display|/Set
    /SyncIntervalinSeconds[:<Value>] /Server:<Name> /Display|/Set
    /PreferLogonDC[:<Value>] /Server:<Name> /Display|/Set
    /DfsDcNameDelay[:<Value>] /Server:<Name> /Display|/Set
    /ProviderCacheTimeoutInMinutes[:<Value>] /Server:<Name> /Display|/Set
    -----------Client-side Only Commands-----------------------------------
    /PktFlush        - Flush the local referral cached information
    /SpcFlush        - Flush the local domain cached information
    /PktInfo         - Show DFS internal information.
    /SpcInfo         - Show DFS internal information.
    /PurgeMupCache   - Flush the local DFS/MUP cached information
    /DisplayMupCache - Display the local DFS/MUP cached information
    

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Dfsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## dfsutil

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

The dfsutil command manages DFS Namespaces, servers, and clients.

### Functionality available in PowerShell

The [DFSN](/powershell/module/dfsn/?view=win10-ps) PowerShell module provides equivalent functionality to the following dfsutil parameters.

| Parameter | Description |
| --------- | ----------- |
| root | Displays, creates, removes, imports, exports namespace roots. |
| link | Displays, creates, removes, or moves folders (links). |
| target | Displays, create, remove folder target or namespace server. |
| property | Displays or modifies a folder target or namespace server. |
| server | Displays or modifies namespace configuration. |
| domain | Displays all domain-based namespaces in a domain. |

### Functionality available only in dfsutil

The following functionality is available only as dfsutil parameters:

| Parameter | Description |
| --------- | ----------- |
| client | Displays or modifies client information or registry keys. |
| diag | Perform diagnostics or view dfsdirs/dfspath. |
| cache | Displays or flushes the client cache. |

For more info about each of these commands, open a command prompt on a server with the DFS Namespaces management tools installed, and then type `dfsutil client /?`, `dfsutil diag /?`, or `dfsutil cache /?`.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


