---
title: vshadow.exe | VShadow, Volume Shadow Copy Service (VSS) Sample Requestor
excerpt: What is vshadow.exe?
---

# vshadow.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\vshadow.exe`
* Description: VShadow, Volume Shadow Copy Service (VSS) Sample Requestor

## Hashes

Type | Hash
-- | --
MD5 | `91170F962E63A7065E39564DC5428EE3`
SHA1 | `27AAB9E8FE9D0547794FA86B808563BA22FB4F86`
SHA256 | `436EFB1D6574FA0DAB562C938C074BA38FF0FF938884690CFD0293182BC395B5`
SHA384 | `73B1AF32FD059754E7B1F92DFFBE8D09B6B19BF9402166C421839FC3A7D8263A1F74AB3D872F0BA5516AE5244F02A4F8`
SHA512 | `7151D7D9CE1988DF0236B70702E7699FC035F46E853C444F8F841970244E979946351E89496C5ED87FFA26689589259D8603BE5E3086AEFC638110F497E9A99F`
SSDEEP | `6144:cMwdaYBYgBsKv5DzqELJ2J55ULdqSPovikkvzd/+:0a8YPW1+EsVULdq9Mvp+`
IMP | `702A07FF266ECFBCEEAC19B4BDB17820`
PESHA1 | `764ECEF5AB2E6B435100868D6B503CFE60B0B23F`
PE256 | `BE6165E991C4F791C60A28E1CEEE77522CA944AFCD2C4C6911AE7F92E7E20DAF`

## Runtime Data

### Usage (stdout):
```cmhg

VSHADOW.EXE 3.0 - Volume Shadow Copy sample client.
Copyright (C) 2005 Microsoft Corporation. All rights reserved.



ERROR: invalid parameter '--help'

Usage:
   VSHADOW [optional flags] [commands]

List of optional flags:
  -?                 - Displays the usage screen
  -p                 - Manages persistent shadow copies
  -nw                - Manages no-writer shadow copies
  -nar               - Creates shadow copies with no auto-recovery
  -tr                - Creates TxF-recovered shadow copies
  -ad                - Creates differential HW shadow copies
  -ap                - Creates plex HW shadow copies
  -scsf              - Creates Shadow Copies for Shared Folders (Client Accessible)
  -t={file.xml}      - Transportable shadow set. Generates also the backup components doc.
  -bc={file.xml}     - Generates the backup components doc for non-transportable shadow set.
  -wi={Writer Name}  - Verify that a writer/component is included
  -wx={Writer Name}  - Exclude a writer/component from set creation or restore
  -mask              - BreakSnapshotSetEx flag: Mask shadow copy luns from system on break.
  -rw                - BreakSnapshotSetEx flag: Make shadow copy luns read-write on break.
  -forcerevert       - BreakSnapshotSetEx flag: Complete operation only if all disk signatures revertable.
  -norevert          - BreakSnapshotSetEx flag: Do not revert disk signatures.
  -revertsig         - Revert to the original disk's signature during resync.
  -novolcheck        - Ignore volume check during resync. Unselected volumes will be overwritten.
  -script={file.cmd} - SETVAR script creation
  -exec={command}    - Custom command executed after shadow creation, import or between break and make-it-write
  -wait              - Wait before program termination or between shadow set break and make-it-write
  -tracing           - Runs VSHADOW.EXE with enhanced diagnostics


List of commands:
  {volume list}                   - Creates a shadow set on these volumes
  -ws                             - List writer status
  -wm                             - List writer summary metadata
  -wm2                            - List writer detailed metadata
  -wm3                            - List writer detailed metadata in raw XML format
  -q                              - List all shadow copies in the system
  -qx={SnapSetID}                 - List all shadow copies in this set
  -s={SnapID}                     - List the shadow copy with the given ID
  -da                             - Deletes all shadow copies in the system
  -do={volume}                    - Deletes the oldest shadow of the specified volume
  -dx={SnapSetID}                 - Deletes all shadow copies in this set
  -ds={SnapID}                    - Deletes this shadow copy
  -i={file.xml}                   - Transportable shadow copy import
  -b={SnapSetID}                  - Break the given shadow set into read-only volumes
  -bw={SnapSetID}                 - Break the shadow set into writable volumes
  -bex={SnapSetID}                - Break using BreakSnapshotSetEx and flags, see options for available flags
  -el={SnapID},dir                - Expose the shadow copy as a mount point
  -el={SnapID},drive              - Expose the shadow copy as a drive letter
  -er={SnapID},share              - Expose the shadow copy as a network share
  -er={SnapID},share,path         - Expose a child directory from the shadow copy as a share
  -r={file.xml}                   - Restore based on a previously-generated Backup Components document
  -rs={file.xml}                  - Simulated restore based on a previously-generated Backup Components doc
  -revert={SnapID}                - Revert a volume to the specified shadow copy
  -addresync={SnapID},drive       - Resync the given shadow copy to the specified volume
  -addresync={SnapID}             - Resync the given shadow copy to it's original volume
  -resync=bcd.xml                 - Perform Resync using the specified BCD


Examples:

 - Non-persistent shadow copy creation on C: and E:
     VSHADOW C: E:

 - Non-persistent shadow copy creation on a CSV named Volume1
     VSHADOW C:\ClusterStorage\Volume1

 - Persistent shadow copy creation on C: (with no writers)
     VSHADOW -p -nw C:

 - Transportable shadow copy creation on X:
     VSHADOW -t=file1.xml X:

 - Transportable shadow copy import
     VSHADOW -i=file1.xml

 - List all shadow copies in the system:
     VSHADOW -q

Please see the README.DOC file for more details.




```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\vshadow.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vshadow.exe
* Product Name: VShadow
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


