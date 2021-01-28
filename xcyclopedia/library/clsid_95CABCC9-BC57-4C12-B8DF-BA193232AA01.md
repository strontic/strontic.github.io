---
title: "CLSID 95CABCC9-BC57-4C12-B8DF-BA193232AA01 | WebAccount Object"
excerpt: What is COM-Object CLSID 95CABCC9-BC57-4C12-B8DF-BA193232AA01?
---

# {95CABCC9-BC57-4C12-B8DF-BA193232AA01}

### `WebAccount Object`

## Registry


### InProcServer32

##### `C:\Windows\System32\vaultcli.dll`
* ThreadingModel: `Both`

## Instance

* Type: `WebAccount`

### Methods

* get_WebAccountProvider: `Windows.Security.Credentials.WebAccountProvider get_WebAccountProvider(), Windows.Security.Credentials.WebAccountProvider IWebAccount.get_WebAccountProvider()`
* get_UserName: `string get_UserName(), string IWebAccount.get_UserName()`
* get_State: `Windows.Security.Credentials.WebAccountState get_State(), Windows.Security.Credentials.WebAccountState IWebAccount.get_State()`
* get_Id: `string get_Id()`
* get_Properties: `System.Collections.Generic.IReadOnlyDictionary[string,string] get_Properties()`
* GetPictureAsync: `Windows.Foundation.IAsyncOperation[Windows.Storage.Streams.IRandomAccessStream] GetPictureAsync(Windows.Security.Credentials.WebAccountPictureSize desizedSize)`
* SignOutAsync: `Windows.Foundation.IAsyncAction SignOutAsync(), Windows.Foundation.IAsyncAction SignOutAsync(string clientId)`

### Properties

* State: `Windows.Security.Credentials.WebAccountState State {get;}`
* UserName: `string UserName {get;}`
* WebAccountProvider: `Windows.Security.Credentials.WebAccountProvider WebAccountProvider {get;}`
* Id: `string Id {get;}`
* Properties: `System.Collections.Generic.IReadOnlyDictionary[string,string] Properties {get;}`

MIT License. Copyright (c) 2021 Strontic.


