---
title: "CLSID E2A4E630-7AD8-44f0-B6EE-D36EA4C6EB94 | Network Diagnostics Client Interface Wrapper"
excerpt: What is COM-Object CLSID E2A4E630-7AD8-44f0-B6EE-D36EA4C6EB94?
---

# {E2A4E630-7AD8-44f0-B6EE-D36EA4C6EB94}

### `Network Diagnostics Client Interface Wrapper`
* LocalizedString: `@C:\Windows\System32\ndfapi.dll,-40001`

## Registry


### InprocServer32

##### `C:\Windows\system32\ndfapi.dll`
* ThreadingModel: `Both`

### ProgID

##### `ndfapi.NetworkDiagnostics.1`

### TypeLib

##### `{11DD5EA9-F8DB-4F6E-BF7C-6AADBA404A3D}`

### Version

##### `1.0`

## Instance

* Type: `ComObject`

### Methods

* CreateIncident: `void CreateIncident (string, string)`
* Diagnose: `IDiagnosticsWaitHandle Diagnose (uint, uint)`
* Repair: `IDiagnosticsWaitHandle Repair (uint, uint)`
* Validate: `IDiagnosticsWaitHandle Validate (uint)`
* OpenExistingIncident: `void OpenExistingIncident (string)`
* SetFollowUpSession: `void SetFollowUpSession (INetworkDiagnostics)`
* ShouldSkipRootCause: `uint ShouldSkipRootCause (IRootCauseInfo)`
* ShouldSkipRepair: `uint ShouldSkipRepair (IRepairInfo)`
* SkipRepair: `void SkipRepair (uint)`
* RepairShown: `void RepairShown (uint)`

### Properties

* DiagnoseResult: `uint DiagnoseResult () {get} `
* RootCauses: `IRootCauseInfoEnum RootCauses () {get} `
* RepairResult: `uint RepairResult () {get} `
* ValidateResult: `uint ValidateResult () {get} `
* Progress: `string Progress () {get} `
* IncidentID: `string IncidentID () {get} `
* EntryPoint: `string EntryPoint () {get} `
* HelperAttributes: `string HelperAttributes () {get} `
* SessionStatus: `uint SessionStatus () {get} `
* FollowUpSession: `string FollowUpSession () {get} `
* TraceFile: `string TraceFile () {get} `

MIT License. Copyright (c) 2021 Strontic.


