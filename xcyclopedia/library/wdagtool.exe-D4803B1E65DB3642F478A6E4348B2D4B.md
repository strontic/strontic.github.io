
# wdagtool.exe 

* File Path: `C:\WINDOWS\system32\wdagtool.exe`
* Description: 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D4803B1E65DB3642F478A6E4348B2D4B`
SHA1 | `97981B8E20D7C807F75F6C6BFB6DCEFB168DD72F`
SHA256 | `EFC84999D1E95514F56A6006F6E22E56D70C4C474B3FD48BBCE31B0BF832487B`
SHA384 | `91266091BCDC02CB3FECA1A593668C2C0D0CB9AB906F4AC2D39AD9601260FCC89897E0E73AA7E089D15B5CF1A08EAE7B`
SHA415 | `9A252F8015F23371819BC389BB08A69F159DBE3933970546D6F8BED4D59A41B17DCA34FA035AA88202187C83AE1013DBBB5D3D821D0256091348E6B36ED52DD8`
SSDEEP | `1536:P0tPSGE8+SBNdGLRVmD3L/M4Z1umO3VpOiVE1Kq3KrT:cK+BNdGLRW37M4imO3VpFVWKr`

## Runtime Data

### Usage (stdout):
```Batchfile
WDAGTool.exe [options]
    Available options:
        cleanup [flags] :     Cleans up the container and data indicated
                              by any of the following flags: 
                              RESET_PERSISTENCE_LAYER - Resets the user's
                              persisted data from inside the container.
                              This flag ignores the policy set for
                              AllowPersistence, always deleting the data.
                              RESET_AUDIT_LOGS - Resets the audit logs being
                              persisted for the container. This flag ignores
                              the policy set for AuditApplicationGuard, always
                              deleting the data. 
          resume <id> :       Resumes a paused container with the given id.
          pause <id> [level]: Pauses a running container with the given id.
                              Valid levels are 0 - 3.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
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

MIT License. Copyright (c) 2020 Strontic.


