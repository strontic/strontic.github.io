---
title: "CLSID 1f3d8aa5-9ebf-4ee4-85c2-ea40379aede8 | CScriptedDiag"
excerpt: What is COM-Object CLSID 1f3d8aa5-9ebf-4ee4-85c2-ea40379aede8?
---

# {1f3d8aa5-9ebf-4ee4-85c2-ea40379aede8}

* (default): `CScriptedDiag`

## Registry


### InprocServer32

* (default): `C:\Windows\System32\sdiageng.dll`
* ThreadingModel: `both`

### ProgID

* (default): `ScriptedDiag.Engine.1`

### TypeLib

* (default): `{4b21f542-0eb5-4205-a12b-59bf2f2555fe}`

### VersionIndependentProgID

* (default): `ScriptedDiag.Engine`

## Instance

* Type: `__ComObject`

### Methods

* Initialize: `void Initialize (string, IUnknown, string)`
* Diagnose: `string Diagnose ()`
* Resolve: `void Resolve (string)`
* Verify: `string Verify ()`
* Cancel: `void Cancel ()`
* SaveResults: `string SaveResults ()`

### Properties

* Rootcauses: `string Rootcauses () {get} `
* DiagnosticIdentification: `string DiagnosticIdentification () {get} `
* DisplayInformation: `string DisplayInformation () {get} `
* ExtensionPoint: `string ExtensionPoint () {get} `
* ElevationContext: `uint ElevationContext () {get} `
* Interactivity: `uint Interactivity () {get} `
* PrivacyLink: `string PrivacyLink () {get} `
* Interactions: `string Interactions () {get} `

MIT License. Copyright (c) 2021 Strontic.


