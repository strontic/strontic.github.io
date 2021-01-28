---
title: "CLSID EF411752-3736-4CB4-9C8C-8EF4CCB58EFE | SpObjectToken Class"
excerpt: What is COM-Object CLSID EF411752-3736-4CB4-9C8C-8EF4CCB58EFE?
---

# {EF411752-3736-4CB4-9C8C-8EF4CCB58EFE}

* `SpObjectToken Class`

## Registry


### InprocServer32

* `C:\Windows\System32\Speech\Common\sapi.dll`
* ThreadingModel: `Both`

### ProgID

* `SAPI.SpObjectToken.1`

### TypeLib

* `{C866CA3A-32F7-11D2-9602-00C04F8EE628}`

### Version

* `5.4`

### VersionIndependentProgID

* `SAPI.SpObjectToken`

## Instance

* Type: `__ComObject`

### Methods

* GetDescription: `string GetDescription (int)`
* SetId: `void SetId (string, string, bool)`
* GetAttribute: `string GetAttribute (string)`
* CreateInstance: `IUnknown CreateInstance (IUnknown, SpeechTokenContext)`
* Remove: `void Remove (string)`
* GetStorageFileName: `string GetStorageFileName (string, string, string, SpeechTokenShellFolder)`
* RemoveStorageFileName: `void RemoveStorageFileName (string, string, bool)`
* IsUISupported: `bool IsUISupported (string, Variant, IUnknown)`
* DisplayUI: `void DisplayUI (int, string, string, Variant, IUnknown)`
* MatchesAttributes: `bool MatchesAttributes (string)`

### Properties

* Id: `string Id () {get} `
* DataKey: `ISpeechDataKey DataKey () {get} `
* Category: `ISpeechObjectTokenCategory Category () {get} `

MIT License. Copyright (c) 2021 Strontic.


