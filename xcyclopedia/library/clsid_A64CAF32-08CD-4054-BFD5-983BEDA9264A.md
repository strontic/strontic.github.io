---
title: "CLSID A64CAF32-08CD-4054-BFD5-983BEDA9264A | WebProviderTokenRequest Object"
excerpt: What is COM-Object CLSID A64CAF32-08CD-4054-BFD5-983BEDA9264A?
---

# {A64CAF32-08CD-4054-BFD5-983BEDA9264A}

### `WebProviderTokenRequest Object`

## Registry


### {00000003-0000-0000-C000-000000000046}


### InprocServer32

##### `C:\Windows\System32\Windows.Security.Authentication.Web.Core.dll`
* ThreadingModel: `Both`

## Instance

* Type: `WebProviderTokenRequest`

### Methods

* get_ClientRequest: `Windows.Security.Authentication.Web.Core.WebTokenRequest get_ClientRequest()`
* get_WebAccounts: `System.Collections.Generic.IReadOnlyList[Windows.Security.Credentials.WebAccount] get_WebAccounts()`
* get_WebAccountSelectionOptions: `Windows.Security.Authentication.Web.Provider.WebAccountSelectionOptions get_WebAccountSelectionOptions()`
* get_ApplicationCallbackUri: `uri get_ApplicationCallbackUri()`
* GetApplicationTokenBindingKeyAsync: `Windows.Foundation.IAsyncOperation[Windows.Security.Cryptography.Core.CryptographicKey] GetApplicationTokenBindingKeyAsync(Windows.Security.Authentication.Web.TokenBindingKeyType keyType, uri target)`
* GetApplicationTokenBindingKeyIdAsync: `Windows.Foundation.IAsyncOperation[Windows.Storage.Streams.IBuffer] GetApplicationTokenBindingKeyIdAsync(Windows.Security.Authentication.Web.TokenBindingKeyType keyType, uri target)`
* get_ApplicationPackageFamilyName: `string get_ApplicationPackageFamilyName()`
* get_ApplicationProcessName: `string get_ApplicationProcessName()`
* CheckApplicationForCapabilityAsync: `Windows.Foundation.IAsyncOperation[bool] CheckApplicationForCapabilityAsync(string capabilityName)`

### Properties

* ApplicationCallbackUri: `uri ApplicationCallbackUri {get;}`
* ClientRequest: `Windows.Security.Authentication.Web.Core.WebTokenRequest ClientRequest {get;}`
* WebAccountSelectionOptions: `Windows.Security.Authentication.Web.Provider.WebAccountSelectionOptions WebAccountSelectionOptions {get;}`
* WebAccounts: `System.Collections.Generic.IReadOnlyList[Windows.Security.Credentials.WebAccount] WebAccounts {get;}`
* ApplicationPackageFamilyName: `string ApplicationPackageFamilyName {get;}`
* ApplicationProcessName: `string ApplicationProcessName {get;}`

MIT License. Copyright (c) 2021 Strontic.


