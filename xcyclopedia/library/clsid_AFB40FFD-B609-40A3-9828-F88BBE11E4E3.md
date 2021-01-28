---
title: "CLSID AFB40FFD-B609-40A3-9828-F88BBE11E4E3 | Server XML HTTP 3.0"
excerpt: What is COM-Object CLSID AFB40FFD-B609-40A3-9828-F88BBE11E4E3?
---

# {AFB40FFD-B609-40A3-9828-F88BBE11E4E3}

### `Server XML HTTP 3.0`

## Registry


### InProcServer32

##### `C:\Windows\System32\msxml3.dll`
* ThreadingModel: `Apartment`

### ProgID

##### `Msxml2.ServerXMLHTTP.3.0`

### TypeLib

##### `{F5078F18-C551-11D3-89B9-0000F81FE221}`

### Version

##### `3.0`

### VersionIndependentProgID

##### `Msxml2.ServerXMLHTTP`

## Instance

* Type: `__ComObject`

### Methods

* open: `void open (string, string, Variant, Variant, Variant)`
* setRequestHeader: `void setRequestHeader (string, string)`
* getResponseHeader: `string getResponseHeader (string)`
* getAllResponseHeaders: `string getAllResponseHeaders ()`
* send: `void send (Variant)`
* abort: `void abort ()`
* setTimeouts: `void setTimeouts (int, int, int, int)`
* waitForResponse: `bool waitForResponse (Variant)`
* getOption: `Variant getOption (SERVERXMLHTTP_OPTION)`
* setOption: `void setOption (SERVERXMLHTTP_OPTION, Variant)`
* setProxy: `void setProxy (SXH_PROXY_SETTING, Variant, Variant)`
* setProxyCredentials: `void setProxyCredentials (string, string)`

### Properties

* status: `int status () {get} `
* statusText: `string statusText () {get} `
* responseXML: `IDispatch responseXML () {get} `
* responseText: `string responseText () {get} `
* responseBody: `Variant responseBody () {get} `
* responseStream: `Variant responseStream () {get} `
* readyState: `int readyState () {get} `
* onreadystatechange: `IDispatch onreadystatechange () {set} `

MIT License. Copyright (c) 2021 Strontic.


