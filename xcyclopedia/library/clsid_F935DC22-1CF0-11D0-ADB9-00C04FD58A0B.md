---
title: "CLSID F935DC22-1CF0-11D0-ADB9-00C04FD58A0B | Windows Script Host Shell Object"
excerpt: What is COM-Object CLSID F935DC22-1CF0-11D0-ADB9-00C04FD58A0B?
---

# {F935DC22-1CF0-11D0-ADB9-00C04FD58A0B}

* (default): `Windows Script Host Shell Object`

## Registry


### {40FC6ED5-2438-11CF-A3DB-080036F12502}


### InProcServer32

* (default): `C:\Windows\System32\wshom.ocx`
* ThreadingModel: `Apartment`

### ProgID

* (default): `WScript.Shell.1`

### Programmable


### TypeLib

* (default): `{F935DC20-1CF0-11D0-ADB9-00C04FD58A0B}`

### VersionIndependentProgID

* (default): `WScript.Shell`

## Instance

* Type: `__ComObject`

### Methods

* Run: `int Run (string, Variant, Variant)`
* Popup: `int Popup (string, Variant, Variant, Variant)`
* CreateShortcut: `IDispatch CreateShortcut (string)`
* ExpandEnvironmentStrings: `string ExpandEnvironmentStrings (string)`
* RegRead: `Variant RegRead (string)`
* RegWrite: `void RegWrite (string, Variant, Variant)`
* RegDelete: `void RegDelete (string)`
* LogEvent: `bool LogEvent (Variant, string, string)`
* AppActivate: `bool AppActivate (Variant, Variant)`
* SendKeys: `void SendKeys (string, Variant)`
* Exec: `IWshExec Exec (string)`

### Properties

* SpecialFolders: `IWshCollection SpecialFolders () {get} `
* CurrentDirectory: `string CurrentDirectory () {get} {set} `

MIT License. Copyright (c) 2021 Strontic.


