---
title: "CLSID CB0FC8E5-686A-478B-A252-FDECF8E167B7 | scanprofilemgr class"
excerpt: What is COM-Object CLSID CB0FC8E5-686A-478B-A252-FDECF8E167B7?
---

# {CB0FC8E5-686A-478B-A252-FDECF8E167B7}

### `scanprofilemgr class`

## Registry


### InprocServer32

##### `C:\Windows\System32\wiascanprofiles.dll`
* ThreadingModel: `both`

### ProgID

##### `scanprofiles.scanprofilemgr.1`

### Programmable


### TypeLib

##### `{77a6bd8a-ab60-49ff-853c-b6ee7babaf96}`

### Version

##### `1.0`

### VersionIndependentProgID

##### `scanprofiles.scanprofilemgr`

## Instance

* Type: `__ComObject`

### Methods

* GetNumProfiles: `void GetNumProfiles (uint)`
* GetNumProfilesforDeviceID: `void GetNumProfilesforDeviceID (string, uint)`
* GetProfiles: `void GetProfiles (uint, IScanProfile)`
* GetProfilesforDeviceID: `void GetProfilesforDeviceID (string, uint, IScanProfile)`
* GetDefaultProfile: `void GetDefaultProfile (string, IScanProfile)`
* CreateProfile: `void CreateProfile (string, string, GUID, IScanProfile)`
* OpenProfile: `void OpenProfile (GUID, IScanProfile)`
* SetDefault: `void SetDefault (IScanProfile)`
* DeleteProfile: `void DeleteProfile (IScanProfile)`
* DeleteAllProfiles: `void DeleteAllProfiles (string)`
* DeleteAllProfilesForUser: `void DeleteAllProfilesForUser ()`
* Refresh: `void Refresh ()`

MIT License. Copyright (c) 2021 Strontic.


