---
title: "CLSID b2bcff59-a757-4b0b-a1bc-ea69981da69e | AzAuthorizationStore Class"
excerpt: What is COM-Object CLSID b2bcff59-a757-4b0b-a1bc-ea69981da69e?
---

# {b2bcff59-a757-4b0b-a1bc-ea69981da69e}

### `AzAuthorizationStore Class`

## Registry


### InprocServer32

##### `C:\Windows\system32\azroles.dll`
* ThreadingModel: `Both`

### ProgID

##### `AzRoles.AzAuthorizationStore.1`

### Programmable


### VersionIndependentProgID

##### `AzRoles.AzAuthorizationStore`

## Instance

* Type: `ComObject`

### Methods

* GetProperty: `Variant GetProperty (int, Variant)`
* SetProperty: `void SetProperty (int, Variant, Variant)`
* AddPropertyItem: `void AddPropertyItem (int, Variant, Variant)`
* DeletePropertyItem: `void DeletePropertyItem (int, Variant, Variant)`
* AddPolicyAdministrator: `void AddPolicyAdministrator (string, Variant)`
* DeletePolicyAdministrator: `void DeletePolicyAdministrator (string, Variant)`
* AddPolicyReader: `void AddPolicyReader (string, Variant)`
* DeletePolicyReader: `void DeletePolicyReader (string, Variant)`
* Initialize: `void Initialize (int, string, Variant)`
* UpdateCache: `void UpdateCache (Variant)`
* Delete: `void Delete (Variant)`
* OpenApplication: `IAzApplication OpenApplication (string, Variant)`
* CreateApplication: `IAzApplication CreateApplication (string, Variant)`
* DeleteApplication: `void DeleteApplication (string, Variant)`
* CreateApplicationGroup: `IAzApplicationGroup CreateApplicationGroup (string, Variant)`
* OpenApplicationGroup: `IAzApplicationGroup OpenApplicationGroup (string, Variant)`
* DeleteApplicationGroup: `void DeleteApplicationGroup (string, Variant)`
* Submit: `void Submit (int, Variant)`
* AddDelegatedPolicyUser: `void AddDelegatedPolicyUser (string, Variant)`
* DeleteDelegatedPolicyUser: `void DeleteDelegatedPolicyUser (string, Variant)`
* AddPolicyAdministratorName: `void AddPolicyAdministratorName (string, Variant)`
* DeletePolicyAdministratorName: `void DeletePolicyAdministratorName (string, Variant)`
* AddPolicyReaderName: `void AddPolicyReaderName (string, Variant)`
* DeletePolicyReaderName: `void DeletePolicyReaderName (string, Variant)`
* AddDelegatedPolicyUserName: `void AddDelegatedPolicyUserName (string, Variant)`
* DeleteDelegatedPolicyUserName: `void DeleteDelegatedPolicyUserName (string, Variant)`
* CloseApplication: `void CloseApplication (string, int)`
* OpenApplication2: `IAzApplication2 OpenApplication2 (string, Variant)`
* CreateApplication2: `IAzApplication2 CreateApplication2 (string, Variant)`
* IsUpdateNeeded: `bool IsUpdateNeeded ()`
* BizruleGroupSupported: `bool BizruleGroupSupported ()`
* UpgradeStoresFunctionalLevel: `void UpgradeStoresFunctionalLevel (int)`
* IsFunctionalLevelUpgradeSupported: `bool IsFunctionalLevelUpgradeSupported (int)`
* GetSchemaVersion: `void GetSchemaVersion (int, int)`

### Properties

* Description: `string Description () {get} {set} `
* ApplicationData: `string ApplicationData () {get} {set} `
* DomainTimeout: `int DomainTimeout () {get} {set} `
* ScriptEngineTimeout: `int ScriptEngineTimeout () {get} {set} `
* MaxScriptEngines: `int MaxScriptEngines () {get} {set} `
* GenerateAudits: `int GenerateAudits () {get} {set} `
* Writable: `int Writable () {get} `
* PolicyAdministrators: `Variant PolicyAdministrators () {get} `
* PolicyReaders: `Variant PolicyReaders () {get} `
* Applications: `IAzApplications Applications () {get} `
* ApplicationGroups: `IAzApplicationGroups ApplicationGroups () {get} `
* DelegatedPolicyUsers: `Variant DelegatedPolicyUsers () {get} `
* TargetMachine: `string TargetMachine () {get} `
* ApplyStoreSacl: `int ApplyStoreSacl () {get} {set} `
* PolicyAdministratorsName: `Variant PolicyAdministratorsName () {get} `
* PolicyReadersName: `Variant PolicyReadersName () {get} `
* DelegatedPolicyUsersName: `Variant DelegatedPolicyUsersName () {get} `

MIT License. Copyright (c) 2021 Strontic.


