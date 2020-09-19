﻿---
title: dfsrmig.exe | DFS Replication SYSVOL Migration Tool
---

# dfsrmig.exe 

* File Path: `C:\Windows\system32\dfsrmig.exe`
* Description: DFS Replication SYSVOL Migration Tool

## Hashes

Type | Hash
-- | --
MD5 | `7CE07C85D43D3A684F38DE7C30C4D64D`
SHA1 | `F1C736A7BAB07D3AACA8C895782C725272B38131`
SHA256 | `55AED6E9EF9E510134D69F867B11F8E643A14A54D185DF86384F0F40B019678D`
SHA384 | `4D1E48CF88BC3051F008F1111FCCEEFFA99AB7714BA629302F4475D8870828E5667F3FEA2678CB801A8E8387ADDF74ED`
SHA512 | `A92FE86AFDB3F331013EC96A15156D460B66656D7648EF390C4ACF66FC465BBFE9363E0D5C54D9B028166386B23ECA0AF82B6A3004C7C3343B5BD646540725B7`
SSDEEP | `24576:u/buM671JFLUt5TGaj8+eGRI2k2L6oBjuveH9wnYFK0ZlTfr8RKvYFyeKKYnMYq:k6RPc5Caj8+hB9HZuvedbPTf/nKj`

## Runtime Data

### Usage (stdout):
```cmhg
Migrate SYSVOL from NTFRS to DFSR.

DfsrMig [/SetGlobalState State] [/GetGlobalState] [/GetMigrationState]
	[/DeleteRoNtfrsMember] [/DeleteRoDfsrMember]
	[/CreateGlobalObjects]

/SetGlobalState [State]         Set the current global DFSR migration state.
                                0  'Start'
                                1  'Prepared'
                                2  'Redirected'
                                3  'Eliminated'

/GetGlobalState                 Get the current global DFSR migration state.

/GetMigrationState              Shows the progress of migration across all
				Domain Controllers.


[Optional arguments] (to be used only if required):


/CreateGlobalObjects            Creates DFSR Global AD objects and missing
				RODC DFSR member objects. Useful if an
				RODC could not start migration for a long time.

/DeleteRoNtfrsMember [RODCName] Deletes NTFRS Member object for the RODC
				specified (or all RODCs if no RODCName is
				specified). Useful if an RODC is stuck in
				the 'Eliminating' state for a long time.

/DeleteRoDfsrMember  [RODCName] Deletes DFSR Member object for the RODC
				specified (or all RODCs if no RODCName is
				specified). Useful if an RODC is stuck in
				the 'Undo-Preparing' state for a long time.
Succeeded.


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

* Original Filename: dfsrmig.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## dfsrmig

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

The migration tool for the DFS Replication service, dfsrmig.exe, is installed with the DFS Replication service. This tool migrates SYSvol replication from File Replication Service (FRS) to Distributed File System (DFS) Replication. It also provides information about the progress of the migration and modifies Active Directory Domain Services (AD DS) objects to support the migration.

### Syntax

```
dfsrmig [/setglobalstate <state> | /getglobalstate | /getmigrationstate | /createglobalobjects |
/deleterontfrsmember [<read_only_domain_controller_name>] | /deleterodfsrmember [<read_only_domain_controller_name>] | /?]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `/setglobalstate <state>` | Sets the domain's global migration state to one that corresponds to the value specified by *state*. You can only set the global migration state to a stable state. The *state* values include:<ul><li>**0** - Start state</li><li>**1** - Prepared state</li><li>**2** - Redirected state</li><li>**3** - Eliminated state</li></ul> |
| /getglobalstate | Retrieves the current global migration state for the domain from the local copy of the AD DS database, when run on the PDC emulator. Use this option to confirm that you set the correct global migration state.<p>**Important:** You should only run this command on the PDC emulator. |
| /getmigrationstate | Retrieves the current local migration state for all domain controllers in the domain and determines whether those local states match the current global migration state. Use this option to determine if all domain controllers have reached the global migration state. |
| /createglobalobjects | Creates the global objects and settings in AD DS used by DFS Replication uses. The only situations where you should use this option to  manually create objects and settings, are:<ul><li>**A new read-only domain controller is promoted during migration**. If a new read-only domain controller is promoted in the domain after moving into the **Prepared** state, but before migration to the **Eliminated** state, then the objects that correspond to the new domain controller aren't created, causing replication and the migration to fail.</li><li>**Global settings for the DFS Replication service are missing or were deleted**. If these settings are missing for a domain controller, migration from the **Start** state to the **Prepared** state will stall at the **Preparing** transition state. **Note:** Because the global AD DS settings for the DFS Replication service for a read-only domain controller are created on the PDC emulator, these settings need to replicate to the read-only domain controller from the PDC emulator before the DFS Replication service on the read-only domain controller can use these settings. Because of Active Directory replication latencies, this replication can take some time to occur. |
| `/deleterontfrsmember [<read_only_domain_controller_name>]` | Deletes the global AD DS settings for FRS replication that correspond to the specified read-only domain controller, or deletes the global AD DS settings for FRS replication for all read-only domain controllers if no value is specified for `<read_only_domain_controller_name>`.<p>You shouldn't need to use this option during a normal migration process, because the DFS Replication service automatically deletes these AD DS settings during the migration from the **Redirected** state to the **Eliminated** state. Use this option to manually delete the AD DS settings only when the automatic deletion fails on a read-only domain controller and stalls the read-only domain controller for a long ime during the migration from the **Redirected** state to the **Eliminated** state. |
| `/deleterodfsrmember [<read_only_domain_controller_name>]` | Deletes the global AD DS settings for DFS Replication that correspond to the specified read-only domain controller, or deletes the global AD DS settings for DFS Replication for all read-only domain controllers if no value is specified for `<read_only_domain_controller_name>`.<p>Use this option to manually delete the AD DS settings only when the automatic deletion fails on a read-only domain controller and stalls the read-only domain controller for a long time when rolling back the migration from the Prepared state to the start state. |
| /? | Displays help at the command prompt. |

##### Remarks

- Use the `/setglobalstate <state>` command to set the global migration state in AD DS on the PDC emulator to initiate and control the migration process. If the PDC emulator isn't available, this command fails.

- Migration to the **Eliminated** state is irreversible and rollback isn't possible, so use a value of **3** for *state* only when you are fully committed to using DFS Replication for SYSvol replication.

- Global migration states must be a stable migration state.

- Active Directory replication replicates the global state to other domain controllers in the domain, but because of replication latencies, you can get inconsistencies if you run `dfsrmig /getglobalstate` on a domain controller other than the PDC emulator.

- The output of `dsfrmig /getmigrationstate` indicates whether migration to the current global state is complete, listing the local migration state for any domain controllers that haven't yet reached the current global migration state. The local migration state for domain controllers can also include transition states for domain controllers that have not reached the current global migration state.

- Read-only domain controllers can't delete settings from AD DS, the PDC emulator performs this operation, and the changes eventually replicate to the read-only domain controllers after the applicable latencies for active directory replication.

- The **dfsrmig** command is supported only on domain controllers that run at the Windows Server domain functional level, because SYSvol migration from FRS to DFS Replication is only possible on domain controllers that operate at that level.

- You can run the **dfsrmig** command on any domain controller, but operations that create or manipulate AD DS objects are only allowed on read-write capable domain controllers (not on read-only domain controllers).

### Examples

To set the global migration state to Prepared (**1**) and to initiate migration or to rollback from the Prepared state, type:

```
dfsrmig /setglobalstate 1
```

To set the global migration state to Start (**0**) and to initiate rollback to the Start state, type:

```
dfsrmig /setglobalstate 0
```

To display the global migration state, type:

```
dfsrmig /getglobalstate
```

Output from the `dfsrmig /getglobalstate` command:

```
Current DFSR global state: Prepared
Succeeded.
```

To display information about whether the local migration states on all the domain controllers match the global migration state and if there are any local migration states where the local state doesn't match the global state, type:

```
dfsrmig /GetMigrationState
```

Output from the `dfsrmig /getmigrationstate` command when the local migration states on all of the domain controllers match the global migration state:

```
All Domain Controllers have migrated successfully to Global state (Prepared).
Migration has reached a consistent state on all Domain Controllers.
Succeeded.
```

Output from the `dfsrmig /getmigrationstate` command when the local migration states on some domain controllers don't match the global migration state.

```
The following Domain Controllers are not in sync with Global state (Prepared):
Domain Controller (Local Migration State) DC type
=========
CONTOSO-DC2 (start) ReadOnly DC
CONTOSO-DC3 (Preparing) Writable DC
Migration has not yet reached a consistent state on all domain controllers
State information might be stale due to AD latency.
```

To create the global objects and settings that DFS Replication uses in AD DS on domain controllers where those settings were not created automatically during migration or where those settings are missing, type:

```
dfsrmig /createglobalobjects
```

To delete the global AD DS settings for FRS replication for a read-only domain controller named contoso-dc2 if those settings were not deleted automatically deleted by the migration process, type:

```
dfsrmig /deleterontfrsmember contoso-dc2
```

To delete the global AD DS settings for FRS replication for all read-only domain controllers if those settings were not deleted automatically by the migration process, type:

```
dfsrmig /deleterontfrsmember
```

To delete the global AD DS settings for DFS Replication for a read-only domain controller named contoso-dc2 if those settings were not deleted automatically by the migration process, type:

```
dfsrmig /deleterodfsrmember contoso-dc2
```

To delete the global AD DS settings for DFS Replication for all read-only domain controllers if those settings were not deleted automatically by the migration process, type:

```
dfsrmig /deleterodfsrmember
```

To display help at the command prompt:

```
dfsrmig
```

```
dfsrmig /?
```

### Additional References

- [Command-Line Syntax Key](https://go.microsoft.com/fwlink/?LinkId=122056)

- [SYSvol Migration Series: Part 2 dfsrmig.exe: The SYSvol Migration Tool](https://techcommunity.microsoft.com/t5/storage-at-microsoft/sysvol-migration-series-part-2-8211-dfsrmig-exe-the-sysvol/ba-p/423470)

- [Active Directory Domain Services](../../identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview.md)

---



MIT License. Copyright (c) 2020 Strontic.

