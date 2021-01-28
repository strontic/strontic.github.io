---
title: "CLSID CDA8ACB0-8CF5-4F6C-9BA2-5931D40C8CAE | FaxServer Class"
excerpt: What is COM-Object CLSID CDA8ACB0-8CF5-4F6C-9BA2-5931D40C8CAE?
---

# {CDA8ACB0-8CF5-4F6C-9BA2-5931D40C8CAE}

* `FaxServer Class`

## Registry


### InprocServer32

* `C:\Windows\System32\fxscomex.dll`
* ThreadingModel: `Apartment`

### ProgID

* `FaxComEx.FaxServer.1`

### Programmable


### TypeLib

* `{2BF34C1A-8CAC-419F-8547-32FDF6505DB8}`

### Version

* `1.0`

### VersionIndependentProgID

* `FaxComEx.FaxServer`

## Instance

* Type: `__ComObject`

### Methods

* Connect: `void Connect (string)`
* GetDeviceProviders: `IFaxDeviceProviders GetDeviceProviders ()`
* GetDevices: `IFaxDevices GetDevices ()`
* Disconnect: `void Disconnect ()`
* GetExtensionProperty: `Variant GetExtensionProperty (string)`
* SetExtensionProperty: `void SetExtensionProperty (string, Variant)`
* ListenToServerEvents: `void ListenToServerEvents (FAX_SERVER_EVENTS_TYPE_ENUM)`
* RegisterDeviceProvider: `void RegisterDeviceProvider (string, string, string, string, int)`
* UnregisterDeviceProvider: `void UnregisterDeviceProvider (string)`
* RegisterInboundRoutingExtension: `void RegisterInboundRoutingExtension (string, string, string, Variant)`
* UnregisterInboundRoutingExtension: `void UnregisterInboundRoutingExtension (string)`

### Properties

* ServerName: `string ServerName () {get} `
* InboundRouting: `IFaxInboundRouting InboundRouting () {get} `
* Folders: `IFaxFolders Folders () {get} `
* LoggingOptions: `IFaxLoggingOptions LoggingOptions () {get} `
* MajorVersion: `int MajorVersion () {get} `
* MinorVersion: `int MinorVersion () {get} `
* MajorBuild: `int MajorBuild () {get} `
* MinorBuild: `int MinorBuild () {get} `
* Debug: `bool Debug () {get} `
* Activity: `IFaxActivity Activity () {get} `
* OutboundRouting: `IFaxOutboundRouting OutboundRouting () {get} `
* ReceiptOptions: `IFaxReceiptOptions ReceiptOptions () {get} `
* Security: `IFaxSecurity Security () {get} `
* RegisteredEvents: `FAX_SERVER_EVENTS_TYPE_ENUM RegisteredEvents () {get} `
* APIVersion: `FAX_SERVER_APIVERSION_ENUM APIVersion () {get} `
* Configuration: `IFaxConfiguration Configuration () {get} `
* CurrentAccount: `IFaxAccount CurrentAccount () {get} `
* FaxAccountSet: `IFaxAccountSet FaxAccountSet () {get} `
* Security2: `IFaxSecurity2 Security2 () {get} `

MIT License. Copyright (c) 2021 Strontic.


