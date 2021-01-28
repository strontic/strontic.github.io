---
title: "CLSID 21D6D48E-A88B-11D0-83DD-00AA003CCABD | TAPI Class"
excerpt: What is COM-Object CLSID 21D6D48E-A88B-11D0-83DD-00AA003CCABD?
---

# {21D6D48E-A88B-11D0-83DD-00AA003CCABD}

### `TAPI Class`

## Registry


### InprocServer32

##### `C:\Windows\System32\tapi3.dll`
* ThreadingModel: `Both`

### ProgID

##### `TAPI.TAPI.1`

### Programmable


### VersionIndependentProgID

##### `TAPI.TAPI`

## Instance

* Type: `ComObject`

### Methods

* Initialize: `void Initialize ()`
* Shutdown: `void Shutdown ()`
* EnumerateAddresses: `IEnumAddress EnumerateAddresses ()`
* RegisterCallNotifications: `int RegisterCallNotifications (ITAddress, bool, bool, int, int)`
* UnregisterNotifications: `void UnregisterNotifications (int)`
* EnumerateCallHubs: `IEnumCallHub EnumerateCallHubs ()`
* SetCallHubTracking: `void SetCallHubTracking (Variant, bool)`
* EnumeratePrivateTAPIObjects: `void EnumeratePrivateTAPIObjects (IEnumUnknown)`
* RegisterRequestRecipient: `void RegisterRequestRecipient (int, int, bool)`
* SetAssistedTelephonyPriority: `void SetAssistedTelephonyPriority (string, bool)`
* SetApplicationPriority: `void SetApplicationPriority (string, int, bool)`
* EnumeratePhones: `IEnumPhone EnumeratePhones ()`
* CreateEmptyCollectionObject: `ITCollection2 CreateEmptyCollectionObject ()`

### Properties

* Addresses: `Variant Addresses () {get} `
* CallHubs: `Variant CallHubs () {get} `
* PrivateTAPIObjects: `Variant PrivateTAPIObjects () {get} `
* EventFilter: `int EventFilter () {get} {set} `
* Phones: `Variant Phones () {get} `

MIT License. Copyright (c) 2021 Strontic.


